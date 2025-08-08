# 📁 Assignments & Learning — Final Project Cycle

**Main Motive:** FINAL PROJECT (maximum group member limit: **3**)  
_All assignments should be stored in their own **separate subfolder** inside the repository._

---

## 🗂️ Assignments thus far

### Week 1 Assignments
> **Note:** For Week 1, work individually or in small groups as instructed by mentors.

#### 🧩 Assignment 1
**- Task:** Research, study, and after using the allotted tools, make a POC (proof of concept) and upload it to your repo.  
**- Deliverable:** POC + README in a separate subfolder.

#### 🧪 Assignment 2
**- Task:** Malware analysis.  
**- Deliverable:** Analysis report (behavior, indicators, IOC list, mitigation steps) + sample handling notes.

#### 🔎 Assignment 3
**- Task:** Threat Intelligence POC.  
**- Deliverable:** TI playbook / report, sources used, and scripts or automation (if any).

#### 🔗 Assignment 4
**- Task:** Homography detection tool — POC and tool.  
**- Description:** Build a detection POC that identifies homographic (look-alike) links. The tool should have **two modes**:
  * **Detection mode** — scan links and flag likely homographs.
  * **Analysis/Report mode** — produce a detailed report and suggested mitigations.
**- Deliverable:** Tool source, usage doc, and example reports.

---

### Week 2 Assignments

#### 🧪 Assignment 1 — Lab Project
**- Task:** Group lab project.  
**- Group size limit:** **4** members max for this lab project.  
**- Deliverable:** Project code, lab instructions, demo video or instructions to reproduce.

#### 🔗 Assignment 2 — Homography Link Generator Tool
**- Task:** Create a homography **link generator** tool (POC) that demonstrates how look-alike links can redirect to something visually close to `YouTube.com` for training/awareness purposes.  
**- Safety & Ethics:** THIS MUST BE USED ONLY FOR EDUCATIONAL, DEFENSIVE, OR AWARENESS PURPOSES — host POCs offline or in a controlled environment and never deploy maliciously.  
**- Deliverable:** Tool code (clearly labelled test/demo mode), README with safe usage, and a mitigation note explaining how to detect and defend against such links.

---

## ✅ Learning / Scoping Items

### Week 1 — Foundations
1. **Learn about GitHub and basic Linux commands.**  
   - Terminal navigation, commits, branches, PRs.

2. **Create a GitHub repo with a clear tree structure.**  
   - Each assignment in its own subfolder, clear README files.

3. **Team selection:** Choose **Red Team** or **Blue Team**.  
   - Red = offensive (pentesting, exploit dev).  
   - Blue = defensive (IR, detection, hunting).

4. **Research / Learn:** Digital Forensics & OSINT and the tools involved.  
   - Practice OSINT workflows and forensic evidence collection.

5. **Research / Learn:** Malware Analysis. Study shared materials:
   - https://youtu.be/ta8AJplqMjk?feature=shared  
   - https://labs.taszk.io/articles/post/full_chain_bb_part1/  
   - https://www.terabox.app/sharing/link?surl=6meoltiWK18hoz-6RgqWFQ  
   - https://www.malwr4n6.com/post/macos-malware-analysis-pkg-files  
   - https://learn.microsoft.com/en-us/sysinternals/

6. **Learn about different security frameworks**, how they work, and try to utilize those skills in assessments and reports.

---

### Week 2 — Tools & Advanced Topics
1. **Linux power usage:** piping, `grep`, `awk`, `sed`, process management, journaling and log parsing.

2. **Tools to learn & practice:** `sqlmap`, Wireshark, Burp Suite, and hardware tools (e.g., Flipper Zero) — responsible, ethical use only.

3. **Automotive security & hardware hacking:**  
   - Basics of ECU, OBD port, wired/wireless attack surfaces.  
   - CVE research for vehicle models (safe lab testing only).

---

## 🧾 Repo & Submission Guidelines
* Each **assignment** must be contained in a separate subfolder named: `weekX_assignmentY_<short-title>`.
* Add a **README.md** in each assignment folder with:
  - Objective
  - Steps run
  - Tools used
  - How to reproduce (or note if reproduction is restricted)
  - Results and conclusion
* For group submissions, include `team_members.md` listing names, roles, and contribution summary.
* Mark any sensitive artifacts (malware samples, PII) as **NOT FOR PUBLIC** or store them in secure, private storage — provide sanitized examples or indicators in the public repo.



