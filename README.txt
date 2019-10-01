Updates will come soon.


I switch projects constantly, so this might end up abandoned. Sorry if that happens.

My Goals:

This will COPY your SWAT game directory into a container. It will then pull SEF from Github and install it into the directory.
Then it will use ENV values to setup the server to a specific gamemode and options. (I might end up just leaving it at setting up a CO-OP server and leave additional configuration to the users).

It will launch the Dedicated Server.bat and thats where it ends. You will need to port forward and such.

It will use the TCP/IP method for SEF and list the server publically with the name defined in ENV.

The goal is for this to leave as little possible configuration to the user. You will obviously still need to port forward.



You will need to source your own SWAT 4 Game as I cannot legally distribute it. All my testing is done with the GOG SWAT 4 Gold edition.
The Dockerfile will have an ENV for all files that need to be edited. Default values will all be configured with Gold edition in mind.
