# Forwarding traffic from Chirpstack to TTN v3

You need [chirpstack-concentratord](https://github.com/brocaar/chirpstack-concentratord) and [chirpstack-udp-bridge](https://github.com/brocaar/chirpstack-udp-bridge). I couldn't find deb packages, so I had to cross-compile them for a Raspberry Pi 3. I looked at how [Gateway OS](https://github.com/brocaar/chirpstack-gateway-os/tree/master/layers/chirpstack/meta-chirpstack/recipes-chirpstack) configures them for hints.
