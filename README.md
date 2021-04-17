# Forwarding traffic from Chirpstack to TTN v3

You need [chirpstack-concentratord](https://github.com/brocaar/chirpstack-concentratord) and [chirpstack-udp-bridge](https://github.com/brocaar/chirpstack-udp-bridge). I couldn't find deb packages, so I had to cross-compile them for a Raspberry Pi 3. I looked at how [Gateway OS](https://github.com/brocaar/chirpstack-gateway-os/tree/master/layers/chirpstack/meta-chirpstack/recipes-chirpstack) configures them for hints.

Go to [TTN v3](https://eu1.cloud.thethings.network/console/gateways) and define a gateway using your ID. I set the ID as the EUI as well, although I'm not sure if that's really necessary. Messages took a while to appear and I'm not entirely sure it's working as intended, the live data shows all uplink messages get dropped for one reason or another. Perhaps I just haven't forwarded an actual TTN packet yet. The gateway does show up as online, though.
