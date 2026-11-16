<div align="center">

# Mina Ashraf Monir

### Software Engineer & IT Specialist

<p align="center">
  Multi-disciplinary engineer with <strong>4+ years</strong> of hands-on experience architecting high-reliability <strong>offline-first mobile &amp; desktop applications</strong>, <strong>real-time full-stack venue systems</strong>, and <strong>enterprise IT infrastructure</strong> across 25–50 endpoint environments.
</p>

<p align="center">
  <a href="https://portfolio.minaashraf285.workers.dev/"><img src="assets/btn-portfolio.svg" alt="Portfolio" height="36" /></a>&nbsp;
  <a href="https://portfolio.minaashraf285.workers.dev/files/Universal_CV_Mina_Ashraf.pdf"><img src="assets/btn-cv.svg" alt="Universal CV (PDF)" height="36" /></a>&nbsp;
  <a href="https://portfolio.minaashraf285.workers.dev/files/IT_Specialist_Resume_Mina_Ashraf.pdf"><img src="assets/btn-resume.svg" alt="IT Specialist Resume (PDF)" height="36" /></a>&nbsp;
  <a href="https://www.linkedin.com/in/mina-ashraf-monir/"><img src="assets/btn-linkedin.svg" alt="LinkedIn" height="36" /></a>&nbsp;
  <a href="mailto:minaashraf285@gmail.com"><img src="assets/btn-email.svg" alt="Email" height="36" /></a>
</p>

<p align="center">
  <sub><strong>Support &amp; Donations</strong></sub><br />
  <a href="https://github.com/sponsors/mina-android"><img src="assets/btn-sponsors.svg" alt="GitHub Sponsors" height="36" /></a>&nbsp;
  <a href="https://paypal.me/minaashraf285"><img src="assets/btn-paypal.svg" alt="PayPal" height="36" /></a>
</p>

<img src="assets/showcase.gif" alt="Application Showcase Carousel" width="320" />

</div>

---

## Engineering Focus & Philosophy

I build native, cross-platform, and on-premise systems designed around **offline autonomy**, **deterministic concurrency**, and **strict user privacy**.

- **Local-First Reliability**: Applications operate primarily against indexed local databases (`SQLite` in WAL mode) and on-premise LAN infrastructure (`PostgreSQL` + `Docker Compose`) so critical workflows never fail when internet connectivity drops.
- **Privacy by Design**: Zero third-party behavioral analytics, trackers, cloud lock-in, or unsolicited telemetry. User data stays on the user's hardware.
- **Systems-Level Pragmatism**: Bridging software architecture with real-world hardware and network operations—from serialized database row locks and sub-second WebSocket state engines to silent `ESC/POS` thermal printing, `ARP/ICMP` socket diagnostics, and `ZFS` storage telemetry.

---

## Featured Systems & Open-Source Projects

### Flagship Production & Open-Source Software

| System | Stack | Highlights & Production Impact | Links |
| :--- | :--- | :--- | :--- |
| **Theatre System** | `Electron` `Node.js` `PostgreSQL` `WebSockets` `Docker` | Unified festival management platform deployed live across on-premise LAN terminals at **St. Markos Church Neiruz Festival 2026** (400 attendees/show, 9,200 tickets). Synchronizes box office ticketing, gate barcode admissions, jury scoring, and stage projector feeds with sub-second jittered WebSockets, `SELECT ... FOR UPDATE` row locks, and driverless `ESC/POS` thermal ticket printing. | [Case Study](https://portfolio.minaashraf285.workers.dev/projects/theatre-system.html) |
| **Expensy** | `Flutter` `Dart` `SQLite WAL` `Provider` | Local-first personal finance and budget manager for Android (**66+ ★ on GitHub**, `GPL-3.0`). Features debit card balance inheritance from linked bank accounts, term deposits with automated yield schedules, rollover category budgets with daily allowance pacers, debt tracking, and `.xlsx`/`JSON` backups with zero cloud telemetry. | [GitHub](https://github.com/mina-android/Expensy) &bull; [Releases](https://github.com/mina-android/Expensy/releases/latest) &bull; [Case Study](https://portfolio.minaashraf285.workers.dev/projects/expensy.html) |
| **IT Box** | `Flutter` `SQLite` `ARP/ICMP` `PDF` | Offline-first IT inventory, subnet calculator, and network diagnostics hub (**Deployed in production at Rada PR**, `GPL-3.0`). Tracks 25–50+ enterprise endpoints, warranties, and loaned peripherals alongside 1D/2D barcode auditing, IPv4 CIDR calculation, non-root `ARP/ICMP` discovery, Cisco IOS `.cfg` parsing, a 1U–42U rack visualizer, and vector PDF reporting. | [GitHub](https://github.com/mina-android/IT-Box) &bull; [Releases](https://github.com/mina-android/IT-Box/releases/latest) &bull; [Case Study](https://portfolio.minaashraf285.workers.dev/projects/it-box.html) |
| **NAS Dash** | `Flutter` `TrueNAS API` `WSS` `ZFS` | Native Android monitoring and control companion for **TrueNAS SCALE** servers (`GPL-3.0`). Streams live per-core CPU, RAM, ZFS ARC hit ratios, and disk S.M.A.R.T. health over encrypted WebSockets (`WSS`), inspects ZFS pool/VDEV topologies, manages catalog apps, enforces biometric reboot guards, and performs zero-drop LAN-to-VPN (`WireGuard` / `NetBird` / `Tailscale`) handoff. | [GitHub](https://github.com/mina-android/NAS-Dash) &bull; [Releases](https://github.com/mina-android/NAS-Dash/releases) &bull; [Case Study](https://portfolio.minaashraf285.workers.dev/projects/nas-dash.html) |
| **FitVerse** | `Flutter` `Gemini AI` `Health Connect` `Firestore` | Biometric fitness coaching platform (`MIT`) combining 50Hz accelerometer DSP peak detection for live repetition counting, **Android Health Connect** synchronization, a 90+ anatomical exercise library, local SQLite caching with Cloud Firestore sync, and context-aware **Google Gemini AI** training and nutrition analysis. | [GitHub](https://github.com/mina-android/fitverse) &bull; [Releases](https://github.com/mina-android/fitverse/releases/latest) &bull; [Case Study](https://portfolio.minaashraf285.workers.dev/projects/fitverse.html) |
| **UnInsta** | `Flutter` `JSON Streaming` `Offline-First` | Privacy-preserving Instagram relationship analyzer (`GPL-3.0`). Directly unpacks and streams official Instagram `ZIP`/`JSON` export archives 100% on-device to identify non-reciprocal followers, pending requests, and mutual connections without account credentials, web scraping, or ban risk. | [GitHub](https://github.com/mina-android/UnInsta) &bull; [Releases](https://github.com/mina-android/UnInsta/releases) &bull; [Case Study](https://portfolio.minaashraf285.workers.dev/projects/uninsta.html) |

### Additional Engineering Work

- **KMT Of Egypt (Bilingual Web Platform & Payload CMS)**: Production bilingual web platform (English & Arabic with full LTR/RTL support) built with `Next.js 15`, `Payload CMS 3`, `TypeScript`, `PostgreSQL`, and `Docker Compose`, featuring an automated `/api/sync-youtube` background worker that monitors YouTube RSS feeds and schedules publications.
- **Icefox (Privacy-Hardened Android Browser)**: Hardened Android browser maintained on `Kotlin`, `Android SDK`, and `Mozilla GeckoView` (forked from Iceraven / Mozilla Fenix), stripping cloud account sync, autofill telemetry, and background trackers.

---

## Core Technical Competencies

- **Programming Languages**: Dart, Python, JavaScript / TypeScript, Kotlin, C++, Java, SQL, Bash / Shell, HTML5 & CSS3 / Tailwind CSS
- **Frameworks & Libraries**: Flutter (Android, Windows, macOS, Web), Electron, Node.js, Express.js, Next.js 15, React, Payload CMS 3, Provider, Material Design 3
- **Databases, Storage & Cloud**: PostgreSQL (serialized row locking & indexing), SQLite (WAL mode & FFI), ZFS Storage Pools, Firebase (Cloud Firestore & Auth), Cloudflare Workers & Pages, Redis
- **Systems & IT Infrastructure**: Windows Server, Windows 10/11 Pro & Enterprise, Linux (Debian / Ubuntu), macOS, TrueNAS SCALE, Docker & Docker Compose, ESC/POS Thermal Printing, 1D/2D Barcode Scanners, Custom PC Architecture & Component-Level Diagnostics
- **Networking & IT Operations**: TCP/IP, DNS & DHCP, IPv4 CIDR Subnetting, LAN / WLAN Deployment, Router & Switch Configuration (Cisco IOS), WireGuard / NetBird / Tailscale VPN, ARP / ICMP Socket Operations, Wireshark, Structured Cat6/RJ-45 Cabling, Air-Gapped & Automated Backup Strategies, Enterprise SaaS & License Management

---

## Professional Experience & Credentials

- **IT Specialist (Full-Time)** — **Rada Public Relations** *(Feb 2026 – Present · Cairo, Egypt)*  
  Directing IT operations across 25–50 multi-platform endpoints (Windows 11, macOS), enterprise SaaS license optimization, structured LAN/WLAN and network printer infrastructure, standardized endpoint provisioning, and daily operations powered by **IT Box**.
- **IT Specialist (Part-Time)** — **El Helal Import & Export** *(Sep 2023 – Jul 2025 · New Cairo, Egypt)*  
  Administered on-premise Windows Server shares and access control for 30+ staff, architected isolated air-gapped backup routines securing customs and accounting records against ransomware, and maintained office switching and Wi-Fi infrastructure.
- **IT Specialist (Part-Time)** — **Rada Public Relations** *(Nov 2021 – Jul 2025 · Cairo, Egypt)*  
  Delivered Level 1/2 hardware, OS, and network troubleshooting for 40+ workstations, structured Cat6 cabling termination, WPA3/WPA2 wireless deployment, and automated cloud multimedia backups.
- **Education**: **B.Sc. in Computer Science** — *Cairo Higher Institute, New Cairo, Egypt (Graduated 2026)*
- **Technical Credentials**: **CCNA (Cisco Certified Network Associate)** — *Self Learning* &bull; **MCSA (Microsoft Certified Solutions Associate)** — *Self Learning*
- **Beyond the Terminal**: Passionate about photography and photo editing in Adobe Lightroom and Photoshop ([@mina.s_pov](https://www.instagram.com/mina.s_pov)), focusing on composition, lighting, and natural retouching.

---

## Connect, Résumé & Support

- **Portfolio & Case Studies**: [portfolio.minaashraf285.workers.dev](https://portfolio.minaashraf285.workers.dev/)
- **Career Documents**: [Universal Technical CV (PDF)](https://portfolio.minaashraf285.workers.dev/files/Universal_CV_Mina_Ashraf.pdf) &bull; [IT Specialist Resume (PDF)](https://portfolio.minaashraf285.workers.dev/files/IT_Specialist_Resume_Mina_Ashraf.pdf)
- **Email**: [minaashraf285@gmail.com](mailto:minaashraf285@gmail.com)
- **LinkedIn**: [linkedin.com/in/mina-ashraf-monir](https://www.linkedin.com/in/mina-ashraf-monir/)
- **GitHub**: [github.com/mina-android](https://github.com/mina-android)
- **Telegram**: [@mina_ashraf285](https://t.me/mina_ashraf285) &bull; [Projects Channel (@m_a_projects)](https://t.me/m_a_projects)
- **Reddit**: [u/mina_android285](https://www.reddit.com/user/mina_android285/)
- **Instagram**: [@mina.s_pov (Photography)](https://www.instagram.com/mina.s_pov) &bull; [@mina.ashraf.monir1 (Personal)](https://www.instagram.com/mina.ashraf.monir1)
- **Sponsorship**: [GitHub Sponsors](https://github.com/sponsors/mina-android) &bull; [PayPal](https://paypal.me/minaashraf285)

---

<div align="center">
  <sub>Maintained by <strong>Mina Ashraf Monir (mina-android)</strong> &bull; Cairo, Egypt &bull; Software built for reliability, autonomy, and performance.</sub>
</div>
