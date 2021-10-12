# Portscanner: test remote ports

Portscanner is a bash testing script for remote ports

```bash

portscanner -h

 Script: portscanner [OPTIONS]

 Usage: portscanner -s srv1,...,srv(n) -p port1,...,port(n) -t timeout
        portscanner -s /path/to/file -p port1,...,port(n),port1-port2 -t timeout

 Options:
  -s <STR,...,STR>      # servers or ips
  -p <INT,...,INT-INT>  # single ports or ranges
  -o <text|table>       # default table
  -t <INT>              # timeout. default 3 seconds
  -h                    # display this text

 Examples:
  portscanner -s vrpiatauv001.domain.com -p 80,443
  portscanner -s vrpiatauv001.domain.com,vrpiatauv002.domain.com -p 2260,2261 -t 5

```

