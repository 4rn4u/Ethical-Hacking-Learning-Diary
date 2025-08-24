 > This Document will be updated every day keeping track of my study during the course with topics related to Ethical Hacking
 
 > **Disclaimer:** I use ChatGPT for writing/organization; all labs are my own (authorized environments) and verified.
 
 ---
 ---
 
### 18/08/25 Monday
Today we started Ethical Hacking and I set up my learning workflow. I checked and configured the Cisco course, created/organized my GitHub repo, and decided to pursue the **KLCP (Kali Linux Certified Professional)** (https://www.offsec.com/courses/pen-103/?utm_source=kali&utm_medium=web&utm_campaign=menu) using my OffSec voucher. Spent the afternoon going through the course and doing light practice in VMs labs.
- **Hours logged:** **7.5h** (3h class + 4.5h study, 16:00–20:30)
- **Class kick-off / setup:** syllabus review, repo & folder structure, time-tracking sheet, Cisco course access verified.
- **KLCP prep (theory & workflow):** Kali layout, packages, system services, basic networking, terminal productivity (history, pipes, redirection).
- **I practiced**: baseline recon and system checks; keeping outputs minimal/sanitized.

---
### 19/08/25 Tuesday
Focused on KLCP prep and core Kali/Linux workflows. Reviewed package management, service management, shell productivity, and basic network recon. Did short activities in a lab VM to practice commands.
- 4.5h study (17:00–21:30)
- KLCP topics: apt/dpkg basics, repositories, systemctl/services, users/groups/permissions, common tooling layout in Kali
- Lab reps: quick host recon → enumerate open services → note likely next steps

---
### 20/08/25 Wednesday
Deepened Linux fundamentals for privilege-escalation theory (for KLCP context, not exploiting real systems): permissions, SUID/SGID, PATH considerations, journaling evidence. All practice restricted to my lab VM(s).
- 3h class
- 5h study (16:30–21:30)
- Topics: UNIX permissions refresher, SUID/SGID concepts, sudoers hygiene, environment/PATH pitfalls, log locations
- Lab checklist (authorized VMs): identify uncommon SUID binaries, read service configs, verify PATH order, review journal

---
### 21/08/25 Thursday
**Exam day (KLCP).** Light review in the morning, then sat the certification exam in the morning. 
- 2h study/review (08:00-10:00)
- Did the KLCP exam (OffSec) (11:00-12:30)
It was a challenging exam but really enjoyed it! Really focus work!

---
### 22/08/25 Friday
Rest Day!

---
### 23/08/25 Saturday
Rest day!

---
### 24/08/25 Sunday
Shifting focus to wireless: I decided to pursue the **OSWP (OffSec Wireless Professional)** https://www.offsec.com/courses/pen-210/ and mapped out a prep plan. Kicked off the first wireless labs, getting comfortable with monitor mode and packet capture fundamentals. Spent time with the **airmon** tools (aircrack-ng suite) and refreshed **Wireshark** basics for 802.11 traffic. I'm using Wifi Challenge Lab (https://v1lab.wifichallenge.com/challenges)
- **Hours logged:** **6h** (15:00–21:00)
- **Activities:**
    - Defined OSWP study plan and milestones (802.11 fundamentals → tooling → structured labs).
    - Lab setup: verified wireless adapter, switched between managed/monitor modes, practiced passive recon only.
    - Wireshark refresher: interface selection, capture filters vs. display filters, identifying management vs. data frames.

