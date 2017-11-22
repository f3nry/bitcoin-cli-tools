# bitcoin-cli-tools

This is a collection of tools that I've found useful in working with a bitcoin core node.


_They are only known to work on Debian with a vanilla install of Bitcoin Core._

## Commands

See `bin/` for source.

### bitcoin-tail-logs

Prints the last 1000 log messages and then tails the debug logs from the bitcoin node.


Currently, it uses the default debug logfile on Unix: `/var/lib/bitcoind/debug.log`

### bitcoin-peer-ips

Print ip:port information about all connected IPs.
