# Rcon client for Quake Live dedicated servers

This is a simple command line interface rcon client to connect to Quake Live dedicated servers. Rcon enables to read and set server cvars and execute server commands like `say`.

It is based on https://github.com/carmethene/quakelive-rcon.git which is based on the original `zmq_rcon.py` that is delivered with the Quake Live dedicated server and can be found in the root directory of the server installation.

Carmthene cleaned up the output of the script and added resolving of colors.

## Improvements

- Remove unused code
- Add command `exit` which terminates the console