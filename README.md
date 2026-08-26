[![Omi](https://github.com/Open-Markets-Initiative/Directory/blob/main/About/Images/Logo.png)](https://github.com/Open-Markets-Initiative/Directory)

# Omi Example Data

[![Organizations](https://img.shields.io/badge/Organizations-19-blue)](#organizations) [![Protocols](https://img.shields.io/badge/Protocols-73-green)](#organizations) [![Packets](https://img.shields.io/badge/Packets-461-orange)](#organizations)

Sample market data for testing.

Each folder holds packet captures for one organization, organized by protocol and version. Most captures are single message pcaps, named after the message they carry, ready for use as test fixtures.

## Layout

A fixture path reads as the protocol it exercises:


```
<Organization>/<Exchange>.<Protocol>[.<Encoding>].<Version>/<MessageName>.pcap
```

For example `Asx/AsxDerivatives.Ntp.v1.05/AddOrderMessage.pcap`. The encoding appears only where it is needed to keep the name unique, where one exchange and protocol are published in more than one encoding.

## Organizations

> [Asx](Asx) · [B3](B3) · [Box](Box) · [Cboe](Cboe) · [Cme](Cme) · [Coinbase](Coinbase) · [Eurex](Eurex) · [Ice](Ice) · [Iex](Iex) · [Imperative](Imperative) · [Jnx](Jnx) · [Memx](Memx) · [Miax](Miax) · [Nasdaq](Nasdaq) · [Nyse](Nyse) · [OtcMarkets](OtcMarkets) · [Siac](Siac) · [Tmx](Tmx) · [Txse](Txse)

---

## Sources

Packet captures have been collected from publicly available sources. If any information is in violation of copyright please let us know and we will remove it.

## Open Markets Initiative

The Open Markets Initiative (Omi) is a group of technologists dedicated to enhancing the stability of electronic financial markets using modern development methods.

For a list of Omi projects: [Omi Projects](https://github.com/Open-Markets-Initiative/Directory/tree/main/Projects "Open Markets Initiative Projects")

For details of Omi rules and regulations: [Omi Directory](https://github.com/Open-Markets-Initiative/Directory "Open Markets Initiative Directory")

