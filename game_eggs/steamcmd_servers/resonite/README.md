# Resonite headless client
## From https://resonite.com
Dive into a brand new digital universe with infinite possibilities, socialize and hang out with people around the world or to build, create and develop anything

# Notice

To use this egg you will need a beta code and a Steam account. Currently the beta code can only acquired by going to the Resonite Patreon, subscribing to the "Discoverer" level. Then you will be able to message the Resonite bot in-game "/headlessCode" and receive the beta code. The account will also need to have Resonite in its library. You can do this by running `app_license_request 2519830` in steamcmd if you have never installed Resonite on this Steam account.
For more information related to configuration go here: https://wiki.neos.com/Headless_Client/Server

This game does not require any port forwarding, but instead uses UDP NAT hole punching (and/or relay) on a random port. You can force a certain port in the config for direct connections, but most communcation is done via NAT hole punch using LiteNetLib (LNL).