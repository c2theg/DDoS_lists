# DDoS_lists
# lists to help fight ddos

# -----  All are UDP based, unless identified with a (T) ----- 
#+------------------------+--------------------------------+------------------------------+----------+
#|        Protocol        | Bandwidth Amplification Factor |      Vulnerable Command      |  Port(s) |
#+------------------------+--------------------------------+------------------------------+----------+
#| DNS                    | 28 to 54                       | see: TA13-088A               |    53    | 
#| NTP                    | 556.9                          | see: TA14-013A               |    123   |
#| SNMPv2                 | 6.3                            | GetBulk request              |    161   |
#| NetBIOS                | 3.8                            | Name resolution              |    137   |
#| SSDP                   | 30.8                           | SEARCH request               |    1900  | 
#| CharGEN                | 358.8                          | Character generation request |    19    |
#| QOTD                   | 140.3                          | Quote request                |    17    |
#| BitTorrent             | 3.8                            | File search                  |   6881   |
#| Kad                    | 16.3                           | Peer list exchange           |   751    |
#| Quake Network Protocol | 63.9                           | Server info exchange         |   26000  |
#| Steam Protocol         | 5.5                            | Server info exchange         |   27015  |
#| Multicast DNS (mDNS)   | 2 to 10                        | Unicast query                |   5353   |
#| RIPv1                  | 131.24                         | Malformed request            |   520    |
#| Portmap (RPCbind)      | 7 to 28                        | Malformed request            |   111    |
#| LDAP                   | 46 to 55                       | Malformed request            |   389 T  |
#| CLDAP                  | 56 to 70                       | —                            |   389    |
#| TFTP                   | 60                             | —                            |   69     |
#| Memcached              | 10,000 to 51,000               | —                            |  11211   |
#| WS-Discovery           | 15,000                         | —                            | 139,445  |
#|                        |                                | —                            |1124, 3704|
#| Apple Remote Desktop   | 35.5                           | -                            |   3283   |
#+------------------------+--------------------------------+------------------------------+----------+
