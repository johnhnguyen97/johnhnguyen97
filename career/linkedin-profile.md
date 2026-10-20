# LinkedIn profile: John Nguyen

Copy-paste ready. Built with the `linkedin-profile-optimizer` method (headline formula, 7-step About, action verb + metric bullets, 3-item Featured, pinned skills).

Profile: https://www.linkedin.com/in/john-huu-nguyen/
Goal: job seeking (systems / software engineering roles) + authority in manufacturing IT.

Anything in `[fill: ...]` is a number only you know. Fill it or delete the clause before pasting.

---

## 1. Headline (197 / 220 chars)

```
Systems Engineer / Programmer at Kobelco (KPEX) | I modernize legacy manufacturing systems: MES web apps in React + C#, SQL Server recovery, Hyper-V and PowerShell automation | EN / VN, learning JP
```

Why this one: leads with what you do and who it is for, carries the search nouns recruiters type (Systems Engineer, MES, SQL Server, React, C#, PowerShell, Hyper-V), and the language line is a real differentiator for Japanese-managed plants.

---

## 2. About (first 265 chars is the hook)

```
When a 2-node storage cluster died and took the plant's Apriso MES databases with it, I rebuilt them from raw disk pages. No backups, no vendor support, a hex editor and a Python script.

That is the kind of work I do at Kobelco Aluminum Products & Extrusions (KPEX): keep a manufacturing plant running on systems nobody else wants to touch, then replace them with something better.

What I have shipped there so far:

• Led the conversion of a 20-year-old VBA/Access MES front end to a web app (React + TypeScript, C# ASP.NET on IIS). The first module passed UAT with a 100% data match against the legacy system in a live side-by-side audit.
• Recovered 3 production SQL Server databases after a failed Storage Spaces Direct cluster, including one with no backups since 2022.
• Replaced a CSV hand-off that kept losing production data with an importer that reads the spectrometer's Paradox database directly.
• Deployed Milestone XProtect across 170+ cameras and 4 recording servers.
• Introduced Git, Azure DevOps and a documentation workflow to a company that had never used source control, and drove Entra ID authentication with Kobelco HQ in Japan.

Before KPEX I ran a $100K AI camera modernization for the City of Bowling Green and cut its server hardware cost 30% with VMware.

Outside work I build Tashinamu, a Japanese learning app (Vue 3, Supabase), and run Nguyenetic, a small web and digital marketing studio. I speak English and Vietnamese and am studying Japanese because half my project docs go to HQ in Japan.

Specialties: manufacturing IT, MES (DELMIA Apriso), SQL Server administration and recovery, C# / ASP.NET, React / TypeScript, Python ETL, PowerShell, Hyper-V failover clustering, Windows Server, Milestone XProtect, Azure DevOps, Entra ID.

If your plant still runs on Access databases and CSV hand-offs, I have probably seen your problem. DM me, or see what I have built at nguyenetic.com.
```

Word count: about 320. Mobile cutoff lands after "...a hex editor and a Python script." which is the whole pitch.

---

## 3. Experience

### Systems Engineer / Programmer, Kobelco Aluminum Products & Extrusions (KPEX)
Bowling Green, KY · October 2025 – Present

```
Software and systems engineer for an aluminum extrusion plant. I own the MES modernization project, SQL Server administration and recovery, Hyper-V infrastructure, and the plant's camera and endpoint platforms.

• Led the conversion of the plant's legacy VBA/Access MES front end to a web app (React + TypeScript on Vite, C# ASP.NET on IIS). Shipped the Die Maintenance module through UAT with a 100% data match against the legacy system in a live side-by-side audit, and ran the UAT review with slides, handouts and EN/JP user guides.
• Recovered the Apriso MES databases after a failed Storage Spaces Direct cluster: hex-edited raw pages, repaired boot pages, merged MDF fragments with a custom Python script and rebuilt the logs. Recovered the GAGEpack database from the same broken 2-node cluster (14 VHDXs).
• Brought the spectrometer database, which had no backups since 2022, from SUSPECT back to ONLINE and corrected 288 misaligned records caused by a CSV format change.
• Reverse-engineered the Belec spectrometer software's Paradox database and built a snapshot importer that reads it directly, which ended a recurring production data-loss failure caused by CSV hand-offs [fill: how often it failed per month].
• Deployed Milestone XProtect across 170+ cameras and 4 recording servers with tiered storage to a QNAP NAS and role-based access for security staff; diagnosed throughput problems with Wireshark and fixed them through firewall rules.
• Built and clustered a Windows Server 2025 SQL dev VM on a Hyper-V failover cluster with NAS storage, entirely in PowerShell.
• Set up Database Mail with job-failure alerts across 3 SQL Server instances and diagnosed an overnight Instron import outage; implemented redundant imports for 225-column Instron datasets a month before the hardware arrived.
• Replaced brittle PowerShell with Python transformers for lab spectrometer data and built LIMS CSV-to-SQL pipelines with validation and real-time Teams alerts; cut an accounting workflow from about 2 hours to 3 minutes.
• Introduced Git, Azure DevOps, architecture tests and API tests to a company that had never used source control. Wrote the scope, schedule, cost and quality documents (JP/EN) that management presents monthly as the Access System Modernization Assessment.
• Proposed and drove Entra ID authentication (app registration, D365 F&O integration, MFA) with Kobelco HQ in Japan.
• Rebuilt fabrication's WIP and finished-goods labels into one validated standard with every team lead, and wrote the SOP for a failing controller.
• Built the KPEX Facility Map (a live, configurable floor plan linked to NinjaOne and the camera system), an integrated ticket system, click-to-open PROMEX links, and an offline meeting-recording app. Shipped a same-day user request in about 30 minutes.
```

Skills to attach to this role: SQL Server, C#, ASP.NET, React, TypeScript, PowerShell, Hyper-V, Python, Azure DevOps, Milestone XProtect, DELMIA Apriso, Windows Server.

Media to attach: a screenshot of the KMES Die Maintenance module (blur part numbers), the UAT slide deck cover, the Facility Map.

### Founder / Software Engineer, Nguyenetic
Remote · August 2024 – Present

```
Freelance software engineering, web development and digital marketing. Clients include EV Shield Wrap, Ichiban and KOHO.

• Led development of a Medi-Cal eligibility automation system (Python, Bash, cron on Debian) that checks eligibility, generates PDF reports and stores results in a structured archive [fill: checks per month or hours saved].
• Built and shipped client websites and marketing campaigns for 3 small businesses [fill: one traffic or lead number].
• Instrumented the eligibility system with diagnostic logging and performance tracking.
```

Skills: Python, Linux, Web Development, Digital Marketing, SEO, Vue.js, Supabase.

### System Engineer I, City of Bowling Green
Bowling Green, KY · October 2023 – August 2024

```
• Led a $100K security modernization that replaced coaxial cameras across 20 locations with Panasonic AI cameras on an NVR server for remote monitoring and playback.
• Cut server hardware cost 30% by designing and deploying the city's VMware virtual server environment.
• Built interactive dashboards with HTML/CSS alert templates for server health, storage, network and virtualization metrics, backed by custom SQL/MySQL queries.
• Wrote scheduled automation scripts for camera configuration with zero downtime, and deployed SolarWinds monitoring on Hyper-V across city departments.
• Delivered a monthly analytics reporting system used for infrastructure planning.
```

Skills: VMware, Hyper-V, SolarWinds, MySQL, Network Engineering, Project Management.

### IT Intern, Barren River Area Development District
Bowling Green, KY · February 2023 – October 2023

```
• Cut issue-resolution time by writing JavaScript automation for IT service requests.
• Mapped the full network topology (devices, connections, configurations, dependencies) into a single source of truth.
• Automated documentation updates with Python and resolved user tickets end to end, including cable installs, device wipes and deployments.
```

Skills: JavaScript, Python, Technical Documentation, Networking, IT Support.

---

## 4. Projects (LinkedIn "Projects" section)

**KMES: MES modernization at KPEX** (2025 – present)
React + TypeScript (Vite) front end, C# ASP.NET back end on IIS, SQL Server. Replaces a VBA/Access MES front end. First module through UAT with a 100% data match.

**Tashinamu** (ongoing)
Japanese learning app. Vue 3, TypeScript, Supabase, Vercel. [fill: link]

**Medi-Cal Eligibility Automation** (2024)
Python + Bash on Debian. Automated eligibility checks with PDF reporting and structured storage.

---

## 5. Education

Western Kentucky University, Bachelor of Science, Computer Information Technology, 2015 – 2022.

---

## 6. Skills (pin the first 3)

Pinned: **SQL Server**, **C#**, **React.js**

Then add, in this order: TypeScript, ASP.NET, PowerShell, Python, Hyper-V, Windows Server, Azure DevOps, Git, Manufacturing Execution Systems (MES), DELMIA Apriso, Database Recovery, ETL, Milestone XProtect, Microsoft Entra ID, Dynamics 365, Vue.js, Supabase, Node.js, Rust, Java, Linux, VMware, Network Engineering, Wireshark, NinjaOne, Technical Documentation, Project Management, Cross-functional Collaboration, Vietnamese, Japanese.

Endorse-trade with 2 or 3 coworkers so every pinned skill has at least one endorsement. Skills with zero endorsements do not count in recruiter search.

---

## 7. Featured (3 items)

1. **nguyenetic.com** as a link. Title the thumbnail "Web and digital work for small businesses".
2. **Tashinamu** (GitHub repo or live app). Title: "Japanese learning app I built with Vue 3 + Supabase".
3. **A post about the Apriso database recovery** (write it once, pin it). Title: "How I rebuilt a production SQL Server database from raw disk pages". Draft outline in `career/post-apriso-recovery.md`.

---

## 8. Custom URL, photo, banner

- URL: you already have `linkedin.com/in/john-huu-nguyen`. Keep it. Changing it breaks links on your old resumes.
- Photo: 400x400 minimum, face about 60% of frame, taken within the last 3 years.
- Banner: 1584x396. Put text in the right two-thirds: "Manufacturing systems, modernized. MES · SQL Server · React + C#" and a small nguyenetic.com.

---

## 9. Recommendation requests (send 3)

**To your KPEX manager** (the one who called you the expert on the Instron import):

```
Hi [Name],

I'm updating my LinkedIn and would value a short recommendation from you, if you're open to it.

If it helps, the things I'd most like it to touch on:
- the Apriso and spectrometer database recoveries after the S2D cluster failure
- the KMES Die Maintenance module passing UAT with a 100% data match
- how I work with the plant floor and with HQ in Japan

Happy to draft two or three lines you can edit. Takes you a minute, means a lot to me.
```

**To a fabrication team lead** (labels project):

```
Hi [Name],

Would you be willing to write a short LinkedIn recommendation? Specifically about the WIP and finished-goods label rebuild: how I worked through it with each team and what changed on the floor afterward.

I can send a draft you can edit if that's easier.
```

**To a Nguyenetic client** (EV Shield Wrap, Ichiban or KOHO):

```
Hi [Name],

I'm tidying up my LinkedIn and would appreciate a recommendation about the work I did on [site / campaign]. Two or three sentences on what you needed and what you got is perfect.

Happy to write one for your business first.
```

---

## 10. Numbers that would make this land harder

Fill these when you have them. Each one upgrades a bullet from "did a thing" to "fixed a cost".

| Item | Number needed |
|---|---|
| Paradox importer | How many times per month the CSV hand-off lost data before the fix, or how many records per failure |
| Spectrometer DB recovery | Rows or years of test data at risk |
| KMES | Number of daily users of the Access MES, or screens converted |
| XProtect | Hours of retention, or storage in TB |
| Labels rebuild | Mislabels per week before and after |
| Medi-Cal automation | Checks per month, or staff hours saved |
| Nguyenetic | One traffic, lead or revenue figure per client |
