# Bots of Engineering / Technology  (docx S5 candidate menu)

These are the **Major sub-functions** of Engineering / Technology from the spec. Each is a bot — a
child decision system that can be instantiated to do the actual work.

## Install flow (matches the Orientation Protocol)
1. **Orient** — the agent runs the Kojiki Orientation Protocol (name / industry /
   jurisdiction / siblings).
2. **Research** — the agent researches the field and decides which sub-functions this
   specific org needs.
3. **Install** — instantiate only the chosen bots:
   ```bash
   cd bots
   python3 install_bots.py brand growth performance-marketing
   ```
   (use the slugs listed below; omit args to install all). Each installed bot becomes a
   full decision system under `bots/<slug>/` with README + AGENT.md + schemas + a stub
   decision record, and registers under this department's group_id for handoffs.

Total candidates: 9.

- `software-engineering` — **Software Engineering**  ·  titles: CTO, VP Engineering, Head of Engineering, Engineering Director, Engineering Manager, Staff Engineer, Principal Engineer, Software Engineer, Architect, SRE
- `architecture` — **Architecture**  ·  titles: CTO, VP Engineering, Head of Engineering, Engineering Director, Engineering Manager, Staff Engineer, Principal Engineer, Software Engineer, Architect, SRE
- `platform` — **Platform**  ·  titles: CTO, VP Engineering, Head of Engineering, Engineering Director, Engineering Manager, Staff Engineer, Principal Engineer, Software Engineer, Architect, SRE
- `infrastructure` — **Infrastructure**  ·  titles: CTO, VP Engineering, Head of Engineering, Engineering Director, Engineering Manager, Staff Engineer, Principal Engineer, Software Engineer, Architect, SRE
- `devops` — **DevOps**  ·  titles: CTO, VP Engineering, Head of Engineering, Engineering Director, Engineering Manager, Staff Engineer, Principal Engineer, Software Engineer, Architect, SRE
- `sre` — **SRE**  ·  titles: CTO, VP Engineering, Head of Engineering, Engineering Director, Engineering Manager, Staff Engineer, Principal Engineer, Software Engineer, Architect, SRE
- `qa` — **QA**  ·  titles: CTO, VP Engineering, Head of Engineering, Engineering Director, Engineering Manager, Staff Engineer, Principal Engineer, Software Engineer, Architect, SRE
- `technical-program-management` — **Technical Program Management**  ·  titles: CTO, VP Engineering, Head of Engineering, Engineering Director, Engineering Manager, Staff Engineer, Principal Engineer, Software Engineer, Architect, SRE
- `developer-experience` — **Developer Experience**  ·  titles: CTO, VP Engineering, Head of Engineering, Engineering Director, Engineering Manager, Staff Engineer, Principal Engineer, Software Engineer, Architect, SRE
