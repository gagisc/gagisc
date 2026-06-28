```
        _    .  ,   .           .
    *  / \_ *  / \_      _  *        *   /\'__        *
      /    \  /    \,   ((        .    _/  /  \  *'.
 .   /\/\  /\/ :' __ \_  `          _^/  ^/    `--.
    /    \/  \  _/  \-'\      *    /.' ^_   \_   .'\  *
  /\  .-   `. \/     \ /==~=-=~=-=-;.  _/ \ -. `_/   \
 /  `-.__ ^   / .-'.--\ =-=~_=-=~=^/  _ `--./ .-'  `-
/jgs     `.  / /       `.~-^=-=~=^=.-'      '-._ `._
```
[Mountains](https://www.asciiart.eu/art/ec00171f6c37d765) - by Joan G. Stark

# hi, I'm Ashraf — [gagisc](https://gagisc.github.io)

I optimize data centers to reduce energy and maintenance costs. My day-to-day is the unglamorous plumbing that keeps computers running: power, cooling, and the monitoring stack that watches both.

Right now I'm focused on how to optimize and maintain every piece of gear that conditions, backs up, and distributes data, power and cooling in a datacenter. I keep a public working notebook at **[gagisc.github.io](https://gagisc.github.io)** where those notes live and link to each other.

---

## what I build

| project | what it does |
|---|---|
| [Power-Guardian](https://github.com/gagisc/Power-Guardian) | detects power anomalies across Eaton ePDU G3, APC Smart-UPS SRT and Schneider Galaxy systems; flags over-provisioned PDUs to recover stranded energy |
| [dc-energy-savings](https://github.com/gagisc/dc-energy-savings) | FLIR thermal video + DS18B20 sensors on a Raspberry Pi — reduced hotspot detection latency by 60% and reactive cooling costs by 18% |
| [dc-power-monitor](https://github.com/gagisc/dc-power-monitor) | lightweight SNMP-based power and temperature dashboard with configurable alerting and a mock-collector mode for testing without hardware |
| [dc-cooling-optimizer](https://github.com/gagisc/dc-cooling-optimizer) | reads historical temperature and power data, identifies hot/cold spots and over-utilized racks, and outputs concrete setpoint and consolidation recommendations with estimated kW savings |
| [dc-cable-audit](https://github.com/gagisc/dc-cable-audit) | discovers cabling topology via LLDP/CDP, flags missing neighbors, speed mismatches, and undocumented connections before they become incidents |
| [network-switch-patcher](https://github.com/gagisc/network-switch-patcher) | safe, dry-run-first CLI for pushing tested remediations to Juniper and Cisco switches — err-disabled ports, BPDU guard, LLDP, jumbo frames |
| [intune-selfheal](https://github.com/gagisc/intune-selfheal) | detects Intune enrolment failures and auto-remediates with sync, MDM token refresh, or extension restart; logs everything to Grafana |

---

## where I've worked

- **Hyundai Group of Companies** - Maintained multi-site, multi-continent spanning data centers from installs all the way to maintanence and continuous improvement cycles
- **Power Corporation of Canada subsidaries** - Maintained systems, changes and updates to a canada-wide spanning infrastructure with a near 99.8% uptime maintained across non-redundant infrastructure via prediction, analysis and maintanence. A lot of what I base my public facing projects on

---

## the notebook

Most of what I know about data center operations is written down and public:

- [Data center power systems](https://gagisc.github.io/data-center-power-systems) — the full map
- [Field notes](https://gagisc.github.io/field-notes) — real problems, limited clever fixes
- [IOC operations](https://gagisc.github.io/ioc-operations) — monitoring, ticketing, RCA, SLA
- [The new data center buildout](https://gagisc.github.io/the-new-data-center-buildout) — liquid cooling, 800V DC, on-site generation, silicon photonics

---

## beyond the floor

I like drawing, which taught me attention to fine details, reading boooks and watching horror. Attention to detail is a habit that makes most of the fixes in [Field notes](https://gagisc.github.io/field-notes) work. I also make things online and share them at [gagisc.github.io/crafts](https://gagisc.github.io/crafts).

---

**reach me:** [gagisc@outlook.com](mailto:gagisc@outlook.com) · Discord `@gagisc` · [gagisc.github.io](https://gagisc.github.io)
