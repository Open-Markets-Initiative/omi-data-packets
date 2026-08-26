[![Omi](https://github.com/Open-Markets-Initiative/Directory/blob/main/About/Images/Logo.png)](https://github.com/Open-Markets-Initiative/Directory)

# Omi Example Data

[![Organizations](https://img.shields.io/badge/Organizations-19-blue)](#organizations) [![Captures](https://img.shields.io/badge/Captures-461-green)](#organizations)

Sample market data for testing.

Each folder holds packet captures for one organization, organized by protocol and version. Most captures are single message pcaps, named after the message they carry, ready for use as test fixtures.

## Layout

A fixture path reads as the protocol it exercises:


```
<Organization>/<Exchange>.<Protocol>[.<Encoding>].<Version>/<MessageName>.pcap
```

For example `Asx/AsxDerivatives.Ntp.v1.05/AddOrderMessage.pcap`. The encoding appears only where it is needed to keep the name unique, where one exchange and protocol are published in more than one encoding.

## Conventions

| Pattern | Meaning |
| --- | --- |
| `<MessageName>.pcap` | Single message, Udp multicast encapsulation |
| `<MessageName>.Tcp.pcap` | Single message, Tcp encapsulation |
| `MultipleMessages.pcap` | Several messages in one packet, exercising block iteration |
| `all_message_types.pcap` | Every message type of a protocol in one capture |

## Organizations

| Folder | Protocols | Captures |
| --- | --- | --- |
| [Asx](Asx) | 1 | 21 |
| [B3](B3) | 4 | 15 |
| [Box](Box) | 1 | 1 |
| [Cboe](Cboe) | 10 | 73 |
| [Cme](Cme) | 5 | 24 |
| [Coinbase](Coinbase) | 4 | 42 |
| [Eurex](Eurex) | 4 | 16 |
| [Ice](Ice) | 2 | 15 |
| [Iex](Iex) | 4 | 27 |
| [Imperative](Imperative) | 1 | 2 |
| [Jnx](Jnx) | 2 | 10 |
| [Memx](Memx) | 1 | 10 |
| [Miax](Miax) | 3 | 19 |
| [Nasdaq](Nasdaq) | 11 | 81 |
| [Nyse](Nyse) | 8 | 43 |
| [Otc](Otc) | 2 | 9 |
| [Siac](Siac) | 7 | 42 |
| [Tmx](Tmx) | 2 | 7 |
| [Txse](Txse) | 1 | 4 |

## Sources

Packet captures have been collected from publicly available sources. If any information is in violation of copyright please let us know and we will remove it.

## Open Markets Initiative

The Open Markets Initiative (Omi) is a group of technologists dedicated to enhancing the stability of electronic financial markets using modern development methods.

For a list of Omi projects: [Omi Projects](https://github.com/Open-Markets-Initiative/Directory/tree/main/Projects "Open Markets Initiative Projects")

For details of Omi rules and regulations: [Omi Directory](https://github.com/Open-Markets-Initiative/Directory "Open Markets Initiative Directory")

