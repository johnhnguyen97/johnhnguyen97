# John Nguyen

Bowling Green, KY · [linkedin.com/in/john-huu-nguyen](https://www.linkedin.com/in/john-huu-nguyen/) · [github.com/johnhnguyen97](https://github.com/johnhnguyen97) · [nguyenetic.com](https://www.nguyenetic.com)

Systems engineer and programmer who modernizes legacy manufacturing systems. Led the conversion of a VBA/Access MES to a React + C# web app, recovered 3 production SQL Server databases from a failed storage cluster, and deployed a 170+ camera video platform. Works directly with Kobelco HQ in Japan. English, Vietnamese, studying Japanese.

## Experience

### Systems Engineer / Programmer, Kobelco Aluminum Products & Extrusions (KPEX)
Bowling Green, KY · October 2025 – Present

- Led the conversion of the plant's legacy VBA/Access MES front end to a web app (React + TypeScript on Vite, C# ASP.NET on IIS, SQL Server). Shipped the Die Maintenance module through UAT with a 100% data match against the legacy system in a live side-by-side audit; ran the UAT review with slides, handouts and EN/JP user guides.
- Recovered the DELMIA Apriso MES databases after a failed 2-node Storage Spaces Direct cluster by hex-editing raw pages, repairing boot pages, merging MDF fragments with a custom Python script and rebuilding logs. Recovered the GAGEpack database from 14 orphaned VHDXs on the same cluster.
- Brought the spectrometer database (no backups since 2022) from SUSPECT to ONLINE and corrected 288 misaligned records caused by a CSV format change.
- Reverse-engineered the Belec spectrometer software's Paradox database and built a snapshot importer that reads it directly, ending a recurring production data-loss failure caused by CSV hand-offs.
- Deployed Milestone XProtect across 170+ cameras and 4 recording servers with tiered storage to a QNAP NAS and role-based access; diagnosed throughput problems with Wireshark and fixed them with firewall rules.
- Built and clustered a Windows Server 2025 SQL dev VM on a Hyper-V failover cluster with NAS storage, entirely in PowerShell.
- Set up Database Mail job-failure alerts across 3 SQL Server instances; diagnosed an overnight Instron import outage; delivered redundant imports for 225-column Instron datasets a month ahead of hardware readiness.
- Replaced brittle PowerShell with Python transformers for lab spectrometer data, built LIMS CSV-to-SQL pipelines with validation and real-time Teams alerts, and cut an accounting workflow from about 2 hours to 3 minutes.
- Introduced Git, Azure DevOps, architecture tests, API tests and a documentation workflow to a company with no prior source control; wrote the JP/EN scope, schedule, cost and quality documents presented monthly to management.
- Proposed and drove Microsoft Entra ID authentication (app registration, Dynamics 365 F&O integration, MFA) with Kobelco HQ.
- Rebuilt fabrication's WIP and finished-goods labels into one validated standard with every team lead; built the KPEX Facility Map (live floor plan linked to NinjaOne and cameras), an integrated ticket system and an offline meeting-recording app.

### Founder and Software Engineer, Nguyenetic
Remote · August 2024 – Present

- Led development of a Medi-Cal eligibility automation system (Python, Bash, cron on Debian) with PDF report generation, structured storage, diagnostic logging and performance tracking.
- Delivered websites and digital marketing for small-business clients including EV Shield Wrap, Ichiban and KOHO.

### System Engineer I, City of Bowling Green
Bowling Green, KY · October 2023 – August 2024

- Led a $100K security modernization replacing coaxial cameras across 20 locations with Panasonic AI cameras on an NVR server for remote monitoring and playback.
- Cut server hardware cost 30% by designing and deploying the city's VMware virtual server environment.
- Built interactive dashboards with HTML/CSS alert templates for server health, storage, network and virtualization metrics, backed by custom SQL/MySQL queries; deployed SolarWinds on Hyper-V across departments.
- Wrote scheduled automation for camera configuration with zero downtime and delivered a monthly analytics reporting system for infrastructure planning.

### IT Intern, Barren River Area Development District
Bowling Green, KY · February 2023 – October 2023

- Cut issue-resolution time with JavaScript automation for IT service requests; automated documentation updates with Python.
- Mapped the full network topology into a single source of truth and resolved user tickets end to end, including cable installs, device wipes and deployments.

## Projects

- **KMES** (2025 – present): MES modernization at KPEX. React, TypeScript, Vite, C# ASP.NET, IIS, SQL Server, Azure DevOps.
- **Tashinamu**: Japanese learning app. Vue 3, TypeScript, Supabase, Vercel.
- **Medi-Cal Eligibility Automation** (2024): Python and Bash on Debian with scheduled runs and PDF reporting.

## Skills

- **Languages:** C#, TypeScript / JavaScript, Python, SQL, PowerShell, Rust, Java, Bash
- **Web:** React, Vue 3, ASP.NET, Node.js, Vite, REST APIs, Supabase, Vercel
- **Data:** SQL Server administration and recovery, ETL pipelines, MySQL, PostgreSQL, Microsoft Access, Paradox
- **Infrastructure:** Windows Server, Hyper-V failover clustering, Storage Spaces Direct, VMware, IIS, QNAP NAS, Linux (Debian, Ubuntu), NinjaOne, Milestone XProtect, Wireshark, SolarWinds
- **Platforms:** Azure DevOps, Git, Microsoft Entra ID, Dynamics 365 F&O, DELMIA Apriso, Bitwarden / Vaultwarden
- **Languages spoken:** English, Vietnamese, Japanese (studying)

## Education

**Western Kentucky University**, Bachelor of Science in Computer Information Technology, 2015 – 2022
