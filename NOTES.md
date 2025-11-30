# 📚 Cyber Security - PEC-CS702E [Year - 2025]

Let me help you can ace this subject, it'll not take more than 7 days for a solid preparation.

If you're here a day before exam just give me a read you will definitely pass, no tension guys 🤣🫂.

Let's go through an overview and some extra, out of syllabus topics MAKAUT asks first then we'll expand them unit wise. Trust me it'll help you remember everything.

---

## 📑 Contents

- [⭐ Unit 1 — Introduction to Cyber Security](#unit-1--introduction-to-cyber-security)
- [📘 Unit 2 — Hackers and Cyber Crimes](#unit-2--hackers-and-cyber-crimes)
- [⚡ Unit 3 — Ethical Hacking & Social Engineering](#unit-3--ethical-hacking--social-engineering)
- [🕵️ Unit 4 — Cyber Forensics & Auditing](#unit-4--cyber-forensics--auditing)
- [👩‍⚖️ Unit 5 — Cyber Ethics and Laws](#unit-5--cyber-ethics-and-laws)

---

## Botnets

- Networks of compromised computers (zombies) controlled by a hacker.
- Used for DDoS, spamming, crypto mining.

*Example:* Mirai botnet took down Netflix & Twitter in 2016.

---

## DoS vs DDos

### 🔹 DoS (Denial of Service)

- **What it is:** Attacker overwhelms a server/network/service with requests until it crashes or becomes unusable.
- **Example:** Sending repeated pings to a web server until it cannot handle real users.

---

### ✅ DoS — Prevention / Mitigation

1. **Rate Limiting:** Restrict how many requests a single IP can make in a time frame.
2. **Firewalls:** Block suspicious IP addresses or request patterns.
3. **Intrusion Detection Systems (IDS):** Identify unusual spikes in traffic.
4. **Redundancy:** Use backup servers/load balancers so one server isn’t overloaded.
5. **Traffic Filtering (Blackholing/Sinkholing):** Redirect malicious traffic away.

---

💡 **Mnemonic: Rate Limiting RIFT** → ***R**ate **L**imiting, **R**edundancy, **I**ntrusion Detection System (IDS), **F**irewalls, **T**raffic Filtering.*

---

### 🔹 DDoS (Distributed Denial of Service)

- **What it is:** Same as DoS, but done using **many devices** (botnets). Attack comes from multiple IPs worldwide, making it much harder to stop.
- **Example:** Hackers infect thousands of computers/IoT devices with malware, then command them to attack a target at once.

---

### ✅ DDoS — Prevention / Mitigation

1. **Content Delivery Networks (CDN):** Distribute requests across many servers worldwide (Cloudflare, Akamai).
2. **DDoS Protection Services:** Specialized providers (e.g., Cloudflare, AWS Shield, Akamai Prolexic) absorb/mitigate attacks.
3. **Anycast Routing:** Direct traffic to multiple data centers, dispersing load.
4. **Rate Limiting + CAPTCHA:** Force suspicious traffic to prove it’s human.
5. **Botnet Detection:** Use AI/behavior analysis to block abnormal request patterns.
6. **ISP-level Filtering:** Internet Service Providers can block bad traffic before it reaches you.

---

💡 **Mnemonic: BI ARC CD** *→ **B**otnet Detection, **I**SP-Level Filtering, **A**nycast Routing, **R**ate Limiting, **C**aptcha, **C**DN(Content Delivery Networks), **D**Dos Protection Services.*

---

### 🔑 Difference in Difficulty

- **DoS:** Easier to detect (all requests from one source).
- **DDoS:** Much harder to detect (traffic comes from thousands of sources). Needs specialized infrastructure.

---

### ⚡In short

- DoS = one attacker → easier to block.
- DDoS = army of attackers → needs advanced prevention (CDN, DDoS protection).

---

## 📊 Real-life DDoS Attacks

| **Attack**  | **Year** | **How it Happened** | **Impact** | **Prevention / Response** |
| :--- | :--- | :--- | :--- | :--- |
| **GitHub**  | 2018 | Attackers abused **Memcached servers** to amplify traffic → 1.35 Tbps flood | GitHub went down \~10 min | Used **Akamai DDoS protection** to absorb/filter traffic |
| **Dyn DNS** | 2016 | **Mirai botnet** (IoT devices: cameras, routers) flooded DNS servers | Took down Twitter, Netflix, PayPal, Reddit, Spotify (U.S.) | Worked with ISPs + security providers, filtered bad traffic |
| **Estonia** | 2007 | Politically motivated DDoS on gov, banks, media | Banking halted, gov services blocked nationwide | Built strong **national cyber defense**, monitoring & resilience |

### 💡 Takeaway

- These attacks show that **DDoS can cripple even the biggest players**.
- Prevention = mix of **cloud protection services, traffic filtering, redundancy, and global monitoring**.

---

### ⚡ Quick memory hook

- **GitHub = Biggest tech DDoS (fast recovery)**
- **Dyn = IoT botnet chaos (took down Netflix/Twitter)**
- **Estonia = First country-scale cyber war**

---

## Incoming & Outgoing Network Traffic

- **Incoming:** Data packets coming into your system (downloads, requests from others).

- **Outgoing:** Data leaving your system (uploads, sending emails, API calls).

👉 Monitoring both helps detect abnormal activity (like hidden malware sending data out).

---

## Spyware

Malicious software that secretly collects your info (keystrokes, browsing, credentials).

*Example:* A fake free game secretly logging your credit card inputs.

---

## Zero-Day Exploits

Attacks that exploit software vulnerabilities before the vendor even knows about them.

👉 *“Day zero” = no patch exists yet.*

*Exam line:* They are the most dangerous because no defense is ready.

---

## Penetration Testing

Ethical hacking technique to simulate attacks and **find weaknesses before real hackers do.**

**Steps:** Planning → Scanning → Exploiting → Reporting.

---

## Man-in-the-Middle (MITM)

Attacker secretly intercepts communication between two parties.

*Example:* On public Wi-Fi, hacker intercepts your banking login before sending it to the bank.

---

## Espionage

Unauthorized spying to steal confidential info (corporate/government).

*Example:* A competitor stealing your company’s new product design.

---

## Social Engineering Attacks

Tricking humans into giving access instead of hacking machines.

**Scenarios:**

- **Phishing:** - Fake communication (email, SMS, websites) designed to steal info. 👉 Always exam favorite.
- **Pretexting:** Pretending to be someone trustworthy (“I’m from IT, give me your password”).
- **Baiting:** Leaving an infected USB labeled “Salary\_Hike.pdf”.

---

## Malware

Malicious software in general. *Includes:* viruses, worms, Trojans, ransomware, spyware.

---

## Ransomware

Malware that encrypts your files and demands money (ransom) to unlock.

*Example:* WannaCry attack (2017).

---

## Worms

Self-replicating malware that spreads without human action.

*Example:* “ILOVEYOU” worm (2000).

---

## Trojans

Malware disguised as legitimate software.

*Example:* A “free antivirus” that actually steals your data.

---

💡 **How to think for exams:**
Most of these terms are *definitional* and *example-based*. Professors love asking:

- **Differentiate malware types (virus vs worm vs Trojan).**
- **Explain DoS vs DDoS.**
- **What is a zero-day exploit? Why dangerous?**
- **What are social engineering attacks with examples?**

---

## ❤️‍🩹 Backup & Recovery

Process of saving copies of data and restoring after loss/cyberattack.

👉 *Key for ransomware defense.*

### Core Concept: The "3-2-1 Rule"

Before diving in, it's crucial to know this golden rule of backup:

- **3** copies of your data (1 primary + 2 backups)
- **2** different storage media (e.g., hard drive + cloud)
- **1** copy stored off-site (e.g., in the cloud or a physical safe elsewhere)

This strategy ensures you are protected against a wide range of failures, from a single disk crash to a catastrophic event like a fire or flood.

---

### Backup Types: What Data Are You Capturing?

Backup types define the *scope* of the data being copied. They are often combined in a strategy to balance speed and storage space.

### Table 1: Backup Types - Purpose & Use Case

| Type | What it Backs Up | Best For |
| :--- | :--- | :--- |
| **Full Backup** | A complete copy of all selected data. | The initial backup. Weekly or monthly "base" backups. |
| **Incremental Backup** | Only data changed since the **last backup of any kind**. | Daily backups between full backups to save space and time. |
| **Differential Backup** | All data changed since the **last full backup**. | Situations where a balance between backup speed and restore simplicity is needed. |
| **Synthetic Full Backup** | A "virtual" full backup made by merging a past full backup with later incrementals. | Consolidating backup chains without the performance hit of a new full backup. |
| **Mirror Backup** | An exact, byte-for-byte copy. Reflects deletions. | Creating a perfect, up-to-date copy for immediate use (not history/archival). |

### Table 2: Backup Types - Advantages & Disadvantages

| Type | Pros | Cons |
| :--- | :--- | :--- |
| **Full Backup** | **Fastest restore time.** Simple recovery; all data is in one place. | **Slowest to create.** Uses the most storage space. |
| **Incremental Backup** | **Very fast to create.** Uses minimal storage space. | **Slower, complex restore.** Requires a full chain of backups. One corrupt file breaks the chain. |
| **Differential Backup** | **Faster restore than incremental.** Only needs the last full + last differential backup. | **Larger and slower than incremental.** Storage usage grows until the next full backup. |
| **Synthetic Full Backup** | No impact on production systems during creation. Simplifies restores. | Requires significant processing power on the backup server. |
| **Mirror Backup** | Exact replica. Very fast file-level restore. | No file history or versioning. Accidental deletions and corruptions are mirrored. |

---

**Analogy:** Think of a document you're writing.

- **Full:** You print the entire document every time.
- **Incremental:** You only print the pages you edited since your last print.
- **Differential:** After your first full print, you print *all* the edited pages since that first print.

---

### Backup Methods: How is the Data Captured?

Methods define the *technology* or *approach* used to perform the backup.

- **File-Level Backup:** Backs up individual files and folders. This is what most home users are familiar with (e.g., copying documents to a USB drive). The OS and backup software see the data as a collection of files.

- **Image-Level (Block-Level) Backup:** Backs up an entire storage volume (e.g., your C: drive) at the sector level. It captures *everything*: the OS, applications, settings, and all files. This is required for a **Bare-Metal Recovery** (restoring to a completely blank or new hard drive).

- **Continuous Data Protection (CDP):** Not a scheduled job. It constantly captures changes to data, logging every write operation. This allows you to restore data to **any point in time** (e.g., right before a corruption occurred), minimizing data loss ( Recovery Point Objective (RPO) of nearly zero).

- **Snapshot:** Captures the state of a system/data at a specific point in time. A point-in-time, read-only copy of a dataset. It's created nearly instantly. While often confused with backups, a snapshot alone is not a backup. It's typically stored on the *same primary storage system*. True backup requires copying that snapshot to a separate, independent system.

---

### Recovery Types: How Do You Get Your Data Back?

Recovery is the goal of backup. The type of recovery you perform depends on the nature of the failure.

- **File-Level Recovery:** The most common type. Restoring individual lost, corrupted, or accidentally deleted files or folders from a backup.

- **Volume Recovery:** Restoring an entire partition or storage volume.

- **Bare-Metal Recovery:** Restoring an entire system—operating system, applications, settings, and data—onto a new, empty server or computer hardware. This is the most comprehensive recovery type and relies on image-level backups.

- **Application Recovery / Granular Recovery:** Restoring a specific application and its data (e.g., a single Microsoft Exchange mailbox or a SQL database) without restoring the entire system. Modern backup tools can often "mount" a backup image and let you extract just the application data you need.

- **Disaster Recovery (DR):** The process of recovering an entire data center or IT infrastructure after a major catastrophic event (fire, flood, ransomware). This involves failing over operations to a secondary (DR) site, which has been receiving backups from the primary site.

### Common Backup Media & Locations

- **Local (DAS):** Direct-Attached Storage (external HDD, USB drive). Fast, but not off-site.
- **Network (NAS):** Network-Attached Storage. Centralized for multiple computers, but usually still on-site.
- **Tape:** Classic, cost-effective for large-scale archival. Physical and must be transported off-site.
- **Cloud Backup:** Services like Backblaze, AWS S3, Azure Backup. Excellent for off-site storage, scalability, and often handles versioning. Requires internet bandwidth.
- **Hybrid Backup:** A combination of local backup (for fast recovery) and cloud backup (for off-site protection). This is a modern best practice.

### Summary: A Typical Backup Strategy

A robust strategy for a business server might look like this:

1. **Perform a Full Backup** every weekend to a local NAS device (for fast recovery).
2. **Perform Incremental Backups** every night to the same NAS.
3. **Replicate** the backup data from the NAS to a cloud storage provider **daily** (for off-site protection and disaster recovery).
4. **Test Restores** quarterly to ensure the process works.

This strategy efficiently uses storage, provides multiple recovery points, and adheres to the 3-2-1 rule.

---

## Diving Deeper if You're Curious (Otherwise Skip this one)

### Key Terms: RTO and RPO

These two metrics are the cornerstone of any serious backup and disaster recovery plan. They define your business's tolerance for downtime and data loss.

- **RPO (Recovery Point Objective)**

  - **The Question it Answers:** "How much data can we afford to lose?"

  - **Definition:** The maximum acceptable amount of data loss measured in time. It determines how far back you need to recover to resume operations. It's about the *quantity of data*.

  - **Example:** If your RPO is 4 hours, you need to have backups at least every 4 hours. A system failure at 3:00 PM means you should be able to restore data from a backup taken no later than 11:00 AM. You lose, at most, 4 hours of work.

  - **Governs:** **Backup Frequency.** A low (tight) RPO requires frequent backups (e.g., incremental every hour, or even Continuous Data Protection).

- **RTO (Recovery Time Objective)**

  - **The Question it Answers:** "How long can we afford to be offline?"

  - **Definition:** The maximum acceptable amount of time for restoring operations after a failure. It's about the *duration of the downtime*.

  - **Example:** If your RTO is 2 hours, your processes and technology must be able to get the critical system back online within 2 hours of the disaster being declared.

  - **Governs:** **Recovery Method.** A low (tight) RTO requires fast recovery solutions like having identical hardware on standby, using image-based backups for bare-metal restore, or failing over to a live disaster recovery site.

**In Practice:** A system with an RPO of 5 minutes and an RTO of 1 hour is far more critical (and expensive to protect) than a system with an RPO of 24 hours and an RTO of 48 hours.

---

### Incremental vs. Differential in Practice

Let's make this concrete with a weekly backup example. Assume a **Full Backup** is performed on **Sunday night**.

| Day | Data Changed | **Incremental** Strategy | **Differential** Strategy                 |
| --- | ------------ | ------------------------ | ----------------------------------------- |
| Sun | -            | **Full Backup** (100 GB) | **Full Backup** (100 GB)                  |
| Mon | 5 GB         | **Inc. Backup** (5 GB)   | **Diff. Backup** (5 GB)                   |
| Tue | 3 GB         | **Inc. Backup** (3 GB)   | **Diff. Backup** (5 GB + 3 GB = **8 GB**) |
| Wed | 4 GB         | **Inc. Backup** (4 GB)   | **Diff. Backup** (5+3+4 GB = **12 GB**)   |
| **CRASH!** | | | |
| **To Restore:** | | **Sun Full** + **Mon Inc** + **Tue Inc** + **Wed Inc** | **Sun Full** + **Wed Diff** |

#### The Restore Process

- **Incremental:** You must restore *every single backup in the chain* in the exact correct order. If Tuesday's incremental backup is corrupt, you cannot restore data from Wednesday.

- **Differential:** You only need to restore two things: the last Full Backup and the *very last* Differential Backup. It's a two-step process, making it simpler and often faster.

---

### Modern Backup Challenges

- **Backing Up Virtual Machines (VMs):**
  - **Challenge:** You can't just install an agent on a VM and back it up like a physical server. The hypervisor (ESXi, Hyper-V) is managing the hardware, and the VM is just a set of files.
  - **Solution:** Modern backup software uses APIs (like VMware's VADP) to take **snapshot-aware backups**. The process is:
      1. Request a snapshot of the VM from the hypervisor (takes a second).
      2. The VM continues running normally.
      3. The backup software reads the stable snapshot file (e.g., a `.vmdk` file).
      4. The snapshot is deleted after the backup is complete.
  - This allows for **image-level, application-consistent** backups of VMs with near-zero downtime.

- **Protecting Data from Ransomware:**
  - **The Challenge:** Ransomware now specifically targets backups to prevent recovery. It encrypts or deletes connected backup repositories.
  - **The Solutions (The "3-2-1-1-0 Rule" extension):**
    - **Immutable Storage:** Backups are written to a format that cannot be altered or deleted for a predetermined period (e.g., 7 days). This is offered by many cloud providers (AWS S3 Object Lock, Azure Blob Immutability) and on-prem appliances.
    - **Air-Gapping:** Physically or logically disconnecting the backup storage from the network after the backup is complete. Tape is a classic air-gapped medium.
    - **Strict Access Control:** Backup systems should be on a separate network segment with credentials that are not used anywhere else on the domain.
    - **Frequent Recovery Testing:** Regularly test restoring files and systems to ensure the backups are valid and the process works *before* you are attacked.

---

## 🔹 Introduction to Cyber Security

- **Definition:** Cyber security = protecting systems, networks, and data from cyber threats.
- **Goal:** Ensure **CIA triad** – Confidentiality, Integrity, Availability.

  - **Confidentiality:** Only authorized access to data. (Passwords, encryption)
  - **Integrity:** Data must not be tampered with. (Hashing, checksums)
  - **Availability:** Systems must be up & running for authorized users. (Backups, redundancy)
- **Why Important?**

  - Our dependency on internet + digital systems → higher risk.
  - Attacks can lead to financial loss, data theft, reputation damage, even national security issues.
    *Exam Angle:* Often asked: “What is Cyber Security? State the objectives.”

---

## Basics of Cyber Security

- **Assets to Protect:**

  - Hardware (servers, PCs, routers)
  - Software (apps, OS)
  - Data (personal info, business secrets)
  - People (users, employees)

- **Threats:** Viruses, hacking, insider threats, natural disasters.
- **Vulnerabilities:** Weak passwords, outdated software, misconfigured firewalls.
- **Attacks:** Exploiting vulnerabilities to harm assets.

- **Defense Layers:**

  1. **Physical Security:** Lock server rooms, restrict device access.
  2. **Network Security:** Firewalls, IDS/IPS, VPNs.
  3. **Application Security:** Secure coding, patching.
  4. **Data Security:** Encryption, access control.
  5. **User Awareness:** Training people (phishing awareness).

👉 **Golden Line for Exams:** “Cyber security is not a single technology, but a multi-layered defense strategy.”

### Mnemonic for Defense Layers

PANDU: Physical, Application, Network, Data, User.

---

## 🔑 Encryption & Decryption

- **Encryption:** Converting readable data (*plaintext*) into unreadable format (*ciphertext*) using an algorithm + key.
- **Decryption:** Converting ciphertext back into plaintext using the key.

### Types

1. **Symmetric Encryption** (one key for both encryption & decryption)

   - Fast but key distribution is hard.
   - Example: AES, DES.

2. **Asymmetric Encryption** (two keys: public + private)

   - Public key encrypts, private key decrypts.
   - Example: RSA, ECC.
   - Used in digital signatures, SSL/TLS.

👉 **Golden Line for Exams:** Encryption ensures confidentiality, while hashing ensures integrity.

## 🔑 Ciphers & Cryptography

Ciphers are the **building blocks** of digital security. Whether it’s WhatsApp chats, banking apps, or your college’s exam portal, they all rely on **encryption algorithms (ciphers + keys)** to keep data safe.

1. **Cipher = Algorithm for secrecy**
   A cipher is just a **method (algorithm)** used to convert **plain text** (normal readable data) → into **cipher text** (scrambled/unreadable data).

   - Example: HELLO → IFMMP (Caesar cipher shift by 1).

2. **Key = Secret spice 🌶️**
   The **key** decides *how* the text is scrambled or unscrambled.

   - Without the right key, the cipher text is almost impossible (or very hard) to read.
   - Example: Caesar cipher with key=3 → shift every letter by 3.
3. **Common Terms You’ll See:**

   - **Plaintext** → original message
   - **Ciphertext** → encrypted message
   - **Encryption** → process of converting plaintext → ciphertext
   - **Decryption** → ciphertext → plaintext
   - **Key** → secret parameter that controls encryption/decryption

---

## Types of Ciphers

### 1. Substitution Cipher

- **How it works:** Each letter in the plaintext is **replaced** by another letter or symbol.
- **Example:**
  - **Plaintext:** HELLO
  - **Ciphertext:** IFMMP (Each letter shifted by +1, a.k.a. Caesar Cipher with shift=1)

---

### 2. Caesar Cipher (A Type of Substitution Cipher)

- **How it works:** Each letter is shifted a fixed number of places down the alphabet.

- **Example (Shift = 3):**

  - **Plaintext:** HELLO
  - **Ciphertext:** KHOOR
  - *H (+3) = K, E (+3) = H, L (+3) = O, L (+3) = O, O (+3) = R*

- **Caesar Cipher (X, Y, Z with +3 or +10 shifts)** → notice how the alphabet "wraps around":

  - `X + 3 = A`
  - `Y + 3 = B`
  - `Z + 3 = C`
  - `X (24) + 10 = 34 → 34 - 26 = 8 → H`
  - `Y (25) + 10 = 35 → 35 - 26 = 9 → I`
  - `Z (26) + 10 = 36 → 36 - 26 = 10 → J`

- **Formulas:**

  - **Encryption:**

    $$
    E(x) = (x + n) \mod 26
    $$
  - **Decryption:**

    $$
    D(x) = (x - n) \mod 26
    $$
  - where:

    - $x$ = position of the letter (A = 0, B = 1, …, Z = 25)
    - $n$ = shift value

- **Decryption Example (Shift = 3):**

  - **Ciphertext:** KHOOR
  - **Plaintext:** HELLO
  - *K (10) − 3 = H (7), H (7) − 3 = E (4), O (14) − 3 = L (11), O (14) − 3 = L (11), R (17) − 3 = O (14)*

---

### 3. Transposition Cipher

- **How it works:** The letters of the plaintext are **rearranged** (jumbled) in a specific pattern. No letters are changed, just their order.
- **Example (Rail Fence Cipher, Depth = 2):**
  - **Plaintext:** ATTACK TODAY
  - Write in a zig-zag:

    ```text
    A   T   C   O   A
      T   A   K   T   D   Y
    ```

  - **Ciphertext:** "ATCOA TAKTDY" (Read row-wise: Row1: A T C O A, Row2: T A K T D Y)

---

### 4. Feistel Cipher (Network)

- **How it works:** It's a **structure** (framework) used to build symmetric block ciphers. It splits data into two halves and processes them through multiple rounds of substitution and permutation.
- **Why important:** Many famous ciphers (like DES) are built using the Feistel network.
- **Example:** **DES (Data Encryption Standard)** is the most famous example of a Feistel cipher.

---

### Mnemonic for Classical Ciphers: "SCT"

- **S**ubstitution → **S**wap letters
- **C**aesar → **C**hange by shift
- **T**ransposition → **T**angle order

---

## Types of Modern Ciphers

### 1. AES (Advanced Encryption Standard)

- **Type:** Symmetric (same key for encrypt & decrypt).
- **Key Sizes:** 128, 192, 256 bits.
- **Strengths:** Very strong, fast, and secure → standard for modern encryption.
- **Uses:** Wi-Fi security (WPA2), file encryption, banking apps.
- **Extra:** Works on blocks of data (128-bit blocks).

---

### 2. DES (Data Encryption Standard)

- **Type:** Symmetric.
- **Key Size:** 56-bit → small, so brute-force possible.
- **Status:** Obsolete, replaced by AES.
- **Uses (Past):** Banking, e-commerce in early days.

---

### 3. RSA (Rivest-Shamir-Adleman)

- **Type:** Asymmetric (uses **public** + **private** key).
- **Security:** Based on difficulty of factoring large prime numbers.
- **Uses:**

  - Secure key exchange
  - Digital signatures
  - SSL/TLS certificates
- **Example:** When you log into your bank, RSA often encrypts the session key that later drives AES.

---

### 4. ECC (Elliptic Curve Cryptography)

- **Type:** Asymmetric (like RSA).
- **Strength:** Same security as RSA but with much smaller keys (faster, lightweight).
- **Uses:** Mobile devices, IoT, cryptocurrencies.
- **Example:** Bitcoin uses ECC for signing transactions.

---

### 5. SSL/TLS (Secure Sockets Layer / Transport Layer Security)

- **Type:** Protocols, not ciphers.
- **Work:** Use AES/RSA/ECC behind the scenes to:

  - Encrypt communication
  - Authenticate server identity

- **Example:** The 🔒 HTTPS in your browser = TLS working.

---

✅ **Quick Link**

- AES/DES → Symmetric (fast, one key).
- RSA/ECC → Asymmetric (slow but secure, two keys).
- SSL/TLS → Protocol that uses these for **secure communication**.

---

### Mnemonic

SSL DARE TLS: Secure Socket Layer, DES, AES, RSA, ECC, Transport Layer Security.

💡 *Write these five times in a notebook:*
Data Encryption Standard,
Advanced Encryption Standard,
Rivest-Shamir-Aldeman,
Elliptic Curve Cryptography.

---

## Full Cipher Summary Table

| Cipher Name         | Type                      | How It Works                                    | Example                              |
|---------------------|---------------------------|-------------------------------------------------|--------------------------------------|
| **AES**             | Symmetric Block           | Encrypts blocks with substitution & permutation | Encrypts WiFi traffic (WPA2)         |
| **DES**             | Symmetric Block (Feistel) | Old standard, 56-bit key                        | Old banking systems                  |
| **RSA**             | Asymmetric                | Uses public/private keys based on primes        | SSL certificates, digital signatures |
| **ECC**             | Asymmetric                | Uses elliptic curves for smaller keys           | Bitcoin, mobile encryption           |
| **Substitution**    | Classical                 | Replaces letters with others                    | A→D, B→E, C→F                        |
| **Caesar Cipher**   | Substitution Type         | Shifts letters                                  | HELLO → KHOOR (shift=3)              |
| **Transposition**   | Classical                 | Reorders letters                                | "HELP" → "H P L E" (rail fence)      |
| **Feistel Network** | Structure (not a cipher)  | Splits & processes data in rounds               | Used in DES, Blowfish                |

---

## 💥 Buffer Overflow

---

### Definition

A **buffer overflow** happens when a program writes **more data than a buffer (temporary memory space) can hold**, causing data to overwrite adjacent memory.

---

### Example

```c
char name[5];
strcpy(name, "DipsanaTheGreat");  
```

Here, `name` can only store 5 chars, but the program tries to store 15.
👉 This extra data overwrites memory beyond `name`, causing **crash** or even **malicious code execution**.

---

### Why Dangerous?

Hackers exploit buffer overflow to:

- **Inject malicious code** into memory.
- **Gain unauthorized access**.
- **Crash programs/OS (Denial of Service)**.

---

### Prevention

- Use safe programming practices (`strncpy` instead of `strcpy`).
- Compiler protections (Stack canaries, DEP, ASLR).
- Input validation (never trust user input blindly).

---

✨ Exam one-liner:
“Buffer overflow is a condition where more data is written to a buffer than it can hold, leading to corruption of adjacent memory and possible execution of malicious code. Prevented by safe coding practices and memory protection mechanisms.”

---

## 🔑 IDS & IPS

- **IDS (Intrusion Detection System):**

  - *Monitors* network traffic for suspicious activity.
  - Passive → alerts admins but doesn’t block.
  - Analogy: CCTV camera.

- **IPS (Intrusion Prevention System):**

  - *Monitors & actively blocks* malicious traffic.
  - Inline, real-time prevention.
  - Analogy: Security guard who not only spots the thief but stops him.

👉 IDS = Detect → Alert.
👉 IPS = Detect → Block.

---

## 🔹 Cyber Security Tools and Techniques

These are the shields and swords we use:

1. **Firewalls**

   - Block/allow traffic based on rules.
   - *Think*: Gatekeeper of your network.

2. **Antivirus/Anti-malware**

   - Detect and remove viruses, worms, Trojans.

3. **IDS/IPS** (already covered)

   - IDS = Detect, IPS = Detect + Block.

4. **VPN (Virtual Private Network)**

   - Encrypts internet traffic, hides IP.
   - Makes communication secure even on public Wi-Fi.

5. **Encryption Tools**

   - Protect data in storage and transit (AES, RSA, etc.).

6. **Penetration Testing Tools**

   - Simulate attacks to find weak points.
   - Ex: Metasploit, Burp Suite.

7. **Backup & Recovery Systems**

   - Protect against data loss and ransomware.

8. **Authentication Mechanisms**

   - Multi-Factor Authentication (MFA), biometrics.

👉 **Exam Note:** Tools fall into categories → *Prevention, Detection, Recovery.*

---

## 🔑 Encryption vs Hashing

### Encryption

- **Purpose:** Protect confidentiality (keep data secret).
- **Process:** Plaintext → Ciphertext using an algorithm + key.
- **Reversible:** Yes (you can decrypt back to original with the key).
- **Example:**

  - Message “I love CyberSec” → Encrypted (nonsense-looking text).
  - Only the person with the right key can read it.

---

### Hashing

- **Purpose:** Protect integrity (ensure data hasn’t been tampered with).
- **Process:** Input → Fixed-length hash value using a hash function.
- **Irreversible:** No way to get the original message back from the hash.
- **Example:**

  - File download site gives you file + SHA256 hash.
  - After downloading, you hash the file. If values match → file is original, not altered.

---

### ✨ Key Difference Line (Exam Gold)

- **Encryption ensures confidentiality** → No one else can read your secret data.
- **Hashing ensures integrity** → No one can tamper with your data without detection.

👉 Bonus: Sometimes they’re combined. Example: SSL/TLS uses both — encryption to keep messages secret, hashing to make sure messages aren’t altered in transit.

---

So basically:

- 🔒 Encryption = “Keep it secret.”
- 🛡️ Hashing = “Keep it safe from tampering.”

Alright 🚀 mini pop-quiz time! Don’t overthink, just go with instinct — short answers are fine:

---

## 🔹 Quiz: Encryption vs Hashing

1. **If you want to make sure no one can read your message while it’s being sent, what do you use?**

2. **If you want to make sure a file downloaded from the internet hasn’t been altered by an attacker, what do you use?**

3. **Can you get the original data back from encryption? From hashing?**

4. **Fill in the blanks:**

   - Encryption ensures \_\_\_\_\_\_\_\_.
   - Hashing ensures \_\_\_\_\_\_\_\_.

### Answers

✔️ **Q1:** Encryption — correct.  
✔️ **Q2:** Hashing — correct.  
✔️ **Q3:** Yes, encryption is reversible with a key. Hashing = one-way, permanent.  
✔️ **Q4:** Encryption → confidentiality, Hashing → integrity!

---

## 👩‍🏫 IDS vs IPS — Comparative Table (Quick Recap)

| Feature   | IDS (Intrusion Detection System) | IPS (Intrusion Prevention System)  |
| --------- | -------------------------------- | ---------------------------------- |
| Role      | Detects suspicious activity      | Detects + blocks malicious traffic |
| Mode      | Passive (alerts only)            | Active (inline, prevention)        |
| Analogy   | CCTV camera                      | Security guard                     |
| Placement | Out-of-band monitoring           | Inline with network traffic        |
| Action    | Sends alerts to admin            | Drops/blocks traffic in real time  |

⚡ **“CCTV vs Guard”** — IDS = camera, IPS = guard. Easy to recall in an exam.

---

## 🔹 Ethical Hacking & Social Engineering

### ✅ Ethical Hacking

- **Definition:** Authorized attempt to find and fix vulnerabilities in a system.
- **Done by:** White-hat hackers.
- **Goal:** Improve security, prevent cybercrimes.

**Phases of Ethical Hacking (Exam Favorite):**

1. **Reconnaissance** → Collect info (IP, domain, emails).
2. **Scanning** → Find open ports, services.
3. **Gaining Access** → Exploit vulnerability.
4. **Maintaining Access** → Backdoors, trojans (to test persistence).
5. **Covering Tracks** → Remove logs, traces.
6. **Reporting** → Document findings to the client.

👉 How to remember? **Student life simulator:**

1. **Recon** the syllabus
2. **Scan** what’s important
3. **Gain access** to marks
4. **Maintain access** with revision
5. **Cover tracks** by forgetting everything after exams
6. and finally… **report** card 💀

---

### 🕵️ Social Engineering

- **Definition:** Tricking people into giving access/info instead of hacking tech.
- **Why effective?** Humans are weakest link in cyber security.

**Common Attacks:**

1. **Phishing** → Fake emails/websites.

   - *Ex:* “Update your bank account here.”
2. **Pretexting** → Pretending to be authority.

   - *Ex:* Fake IT support asking for your password.
3. **Baiting** → Offering something tempting.

   - *Ex:* USB labeled “Confidential Salaries” left in office.
4. **Tailgating** → Following employee into secure area.

   - *Ex:* Carrying coffee, asking someone to hold the door.
5. **Vishing/Smishing** → Voice/SMS phishing.

👉 Exam angle: Often asked — *“Explain social engineering with examples.”*

---

## 🔹 Cyber Forensics & Auditing

### 🕵️ Cyber Forensics (like CSI, but digital)

- **Definition:** Collecting, preserving, analyzing, and presenting digital evidence in a legal manner.
- **Purpose:** Investigate crimes (hacking, fraud, cyberbullying, ransomware).
- **Golden Line:** “Forensics ensures digital evidence is admissible in court.”

**Steps (like a detective story):**

1. **Identification** → Spot where evidence exists (hard drive, email, logs, cloud).

   - Detective finds the crime scene.
2. **Preservation** → Secure and isolate evidence to prevent tampering.

   - Detective seals the crime scene.
3. **Collection** → Take forensic images, copy data bit-by-bit.

   - Detective collects fingerprints & samples.
4. **Examination** → Use tools (EnCase, FTK, Autopsy) to extract hidden/deleted files.

   - Detective dusts for fingerprints.
5. **Analysis** → Correlate findings, trace attack path.

   - Detective connects clues.
6. **Presentation** → Report evidence in court.

   - Detective testifies in trial.

### 👉 Mnemonic

“*Ident preserves CD collection while examine analyses presentations*”

*Do it five times:*
Decrypt it with the private keys in your mind: Identification, Preservation, Collection, Examination, Analysis, Presentation

---

### 📊 Cyber Auditing

- **Definition:** Systematic evaluation of an organization’s cyber security policies, controls, and practices.
- **Goal:** Ensure compliance with standards, find weaknesses, suggest improvements.
- **Types:**

  1. **Internal Audit** (done by organization itself).
  2. **External Audit** (done by 3rd party for certification/regulation).
- **Focus Areas:**

  - Network security
  - Access controls
  - Patch management
  - Incident response policies

👉 Difference in one line:

- **Forensics = Reactive** (after a crime).
- **Auditing = Proactive** (prevent future crimes).

### Mnemonics

1. **Incident, Response and Policies NAP** for auditing: Network, Access control, Patch management, Incident Response Policy
2. Fun Analogy 😂: During child birth **father is reactive and amma is proactive.** Father stands for forensics and amma stands for auditing.

---

## 🔹 Cyber Law & Ethics

### ⚖️ Cyber Law

- **Definition:** **Legal framework** dealing with crimes and disputes related to digital tech, internet, and information systems.
- **Need:**

  - Protect individuals/companies from cybercrimes.
  - Define punishments for hackers, fraudsters.
  - Regulate e-commerce, digital signatures, data privacy.

**Examples:**

- **IT Act 2000 (India):**

  - Legal recognition of electronic records, digital signatures.
  - Defines offenses like hacking, identity theft, publishing obscene material.
  - Amended in 2008 for stronger data protection & cyber terrorism.
- **GDPR (EU):**

  - Strict data privacy rules. Companies must protect user data.
- **HIPAA (US):**

  - Healthcare data protection.

---

### 🌱 Cyber Ethics

- **Definition:** Moral principles guiding how technology and internet should be used.
- **Examples:**

  - Don’t spread malware.
  - Respect privacy.
  - No piracy (movies/software).
  - Don’t cyberbully or harass online.
- **Golden Line:** “Cyber ethics promotes responsible behavior in cyberspace.”

---

### 📝 Exam Hot Questions

- “Explain Cyber Laws in India with reference to IT Act 2000.”
- “What are Cyber Ethics? Why are they important?”
- “Differentiate between Cyber Law and Cyber Ethics.”

👉 Difference in one line:

- **Cyber Law** = What you *must* do (rules, punishments).
- **Cyber Ethics** = What you *should* do (moral responsibility).

---

## Unit 1 — Introduction to Cyber Security

### 1. Introduction to Cyber Security

- Protection of systems, networks, and data from digital attacks.
- Goal → ensure **confidentiality, integrity, availability (CIA)**.
- Cybersecurity = *prevent + detect + respond* to threats.

---

### 2. Elements of Cyber Security

- **Application Security** (apps, software patching)
- **Information Security** (data protection)
- **Network Security** (firewalls, IDS/IPS)
- **Operational Security** (policies, processes)
- **End-user Education** (weakest link = humans).

---

### 3. Five Core Functions (NIST Framework)

**Order is important!**

1. **Identify** → assets, risks.
2. **Protect** → safeguards (firewalls, encryption).
3. **Detect** → anomalies, breaches.
4. **Respond** → incident management.
5. **Recover** → restore services.

💡 **Think:** *Identify → Protect → Detect → Respond → Recover = full security lifecycle.*

💡 **Mnemonic** **DR RIP** *→ **D**etect, **R**espond, **R**ecover, **I**dentity, **P**rotect*

---

### 4. Cyber Security Best Practices

- Strong passwords & MFA.
- Regular patching & updates.
- Backups (3-2-1 rule).
- Least privilege principle.
- Employee awareness (phishing, social engineering).

---

### 5. Importance & Challenges

- Importance: Protects privacy, finances, national security.
- Challenges: Sophisticated attackers, insider threats, skill gap, evolving tech (IoT, AI).

---

### 6. Cyberspace

- The **virtual environment** of interconnected networks.
- Includes Internet + intranets (organizations privatized network that uses internet technology) + cloud + IoT.
- Borderless & global → harder to regulate.

---

### 7. Cyber Threats

Cyber threats = malicious attempts to damage, steal, or disrupt systems.

### 1. Malware

- General term for malicious software.
- Purpose: steal, disrupt, damage.

- *Virus* → attaches to programs/files.
- *Worm* → self-replicates across networks.
- *Trojan* → disguised as legit software.
- *Ransomware* → encrypts data, demands payment.

### 2. Phishing

- Fake emails/websites tricking users to reveal sensitive info (passwords, credit card).
- *Ex:* A fake bank login page.

### 3. Denial of Service (DoS/DDoS)

- Overloading a system with traffic(botnets as discussed before) → crashes or becomes unavailable.
- *Ex:* Website flooded with millions of requests.

### 4. Man-in-the-Middle (MITM)

- Hacker intercepts communication.
- *Ex:* Public Wi-Fi attacker capturing login info.

### 5. SQL Injection

- Malicious SQL code inserted into input fields to steal/manipulate databases.
- *Ex:* Login form exploited to dump user database.

### 6. Zero-Day Attacks

- Exploit vulnerabilities before patches are released.

### 7. Insider Threats

- Disgruntled employees misusing access.

### 8. Password Attacks

- Brute force, dictionary attacks, credential stuffing.

### 9. Social Engineering

- Psychological manipulation.
- Scenarios:
  - **Phishing:** Fake communication (email, SMS, websites) designed to steal info. 👉 Always exam favorite.
  - **Pretexting:** Pretending to be someone trustworthy (“I’m from IT, give me your password”).
  - **Baiting:** Leaving an infected USB labeled “Salary\_Hike.pdf”.

---

### 💔 10. Dating Scam (Romance Scam / Catfishing)

**What it is:**
A type of social engineering and online fraud where a criminal creates a fake identity on a dating app or social media to form a romantic relationship with the victim. The goal is to gain their trust and eventually, their money.

**How it works (The Playbook):**

1. **The Bait:** The scammer creates an attractive fake profile (this is "catfishing").
2. **The Hook:** They contact the victim, shower them with love and attention, and quickly profess strong feelings.
3. **The Story:** Once trust is built, they create a crisis. Common stories include:
    - "I need money for a plane ticket to come see you."
    - "I have a medical emergency and can't afford the surgery."
    - "My business is failing, and I need a loan to save it."
4. **The Payoff:** They convince the victim to send money, often via wire transfers, gift cards, or even cryptocurrency, which are hard to trace and reverse.

**Why it's effective:** It preys on emotional vulnerability and the human desire for connection. The victim often doesn't realize they've been scammed until it's too late.

---

### 📦 11. OTP Scam (Delivery Scam)

**What it is:**
A very common and modern form of phishing where scammers impersonate delivery agents from companies like Amazon, Flipkart, or FedEx to steal your One-Time Password (OTP) and commit fraud.

**How it works (Step-by-Step):**

1. **The Trigger:** You place an online order. Scammers sometimes get basic info like your name, product, and phone number from data leaks or insecure channels.
2. **The Call/SMS:** You receive a call or SMS from a number that seems to be from the delivery company. They confirm your order details to sound legitimate.
3. **The Excuse:** They give a convincing reason why they need your OTP. For example:
    - "We need to verify your address before delivery."
    - "The OTP is to confirm the delivery time slot."
    - "We need it to process a refund for you."
4. **The Theft:** The moment you read out the OTP, the scammer uses it to:
    - **Confirm a fraudulent transaction** they initiated on your card.
    - **Gain access to your bank/wallet account** that uses OTP-based authentication.
    - **Activate a SIM swap** to take control of your phone number.

**The Golden Rule:** **NEVER, EVER share an OTP with anyone.** A legitimate delivery agent or bank executive will **NEVER** ask for it. The OTP is the final key to your castle; sharing it is like handing a thief your keys.

---

💡 Cyber threats evolve constantly → AI-driven attacks, IoT vulnerabilities are the new frontiers.

---

### 8. Cyberwarfare

- Nation-state sponsored attacks for espionage or disruption.
- Example: Stuxnet (Iran nuclear program).
- Tactics: DDoS, misinformation, critical infrastructure attacks.

---

### 9. CIA Triad

- **Confidentiality → Private** (authorized access: only the right people access data)
- **Integrity → Accurate** (unauthorized access: data can’t be tampered with)
- **Availability → Accessible** (systems/data available when needed)

💡 Balance is key: too much confidentiality may hurt availability.
Think: *Private, Accurate, Accessible = CIA.*

---

### 10. 😨 Cyber Terrorism

Using digital attacks to create **fear, disruption, or physical harm** to support a political, religious, or ideological cause. It’s terrorism through computers.

---

### 🎯 Goal: Why They Do It

| Cybercriminal 🤑 | Cyber Terrorist ☠️ |
| ---| :--- |
| Wants money, fame, or fun. | Wants to spread fear, force change, or promote an ideology. |
| Targets people, companies, banks. | Targets **critical infrastructure**: power, water, govt systems, public services. |

🧐 **Main motives:**

- **Spread Terror:** Make people feel unsafe and lose trust in their government’s ability to protect them.
- **Disrupt Economy:** Damage a country’s financial stability by attacking banks, stock markets, or big companies.
- **Intimidate Government:** Blackmail or threaten leaders to force political changes.
- **Advance an Ideology:** Promote extreme religious or political beliefs.
- **Military:** Hacking into defense systems.

---

### ⚙️ How They Attack

| Method                     | What It Does                                        | Real Impact                                       |
| -------------------------- | --------------------------------------------------- | ------------------------------------------------- |
| **Website Defacing**       | Hack & vandalize official sites.                    | Hurts trust + embarrasses the government.         |
| **Propaganda Spreading**   | Use social media to recruit or radicalize.          | Spreads hate and inspires real-world attacks.     |
| **Infrastructure Hacking** | Take control of power/water/transport systems.      | Can cause blackouts, contamination, or disasters. |
| **Fake News Campaigns**    | Spread lies to create panic or influence elections. | Can cause riots, violence, or social chaos.       |
| **DDoS Attacks**           | Overload websites to shut them down.                | Disrupts essential services and costs money.      |

---

### 🌐 Real Examples

- **Estonia Cyber Attack (2007)**  
  - **What happened:**
      Government websites, banks, and news outlets in Estonia were hit by massive DDoS waves by massive cyber attacks after a political dispute.
  - **Reason:**
      Political tensions after a Soviet-era statue was relocated.
  - **Impact:**
      Banking halted, news media blocked, gov services disrupted — first time a country was hit at this scale.
  - **Prevention used:**
      Estonia strengthened its **national cyber defense**, becoming one of the leading countries in cybersecurity today.

- **ISIS:** Used social media to spread terror propaganda and recruit members globally.
- **Stuxnet:** A sophisticated cyber weapon that physically damaged nuclear centrifuges in Iran, setting back their program years. It showed how a digital attack can cause real-world destruction.

---

### 🔑 Key Point: Intent Matters

The same attack can be classified differently based on who does it and why:

**Example: A DDoS attack...**

- ...launched by a `script kiddie` to show off to friends is **cybercrime** (vandalism).
- ...launched by a `hacktivist` group to protest a policy is **hacktivism** (digital activism).
- ...launched by a `state-sponsored group` to shut down a country's banks is **cyber warfare**.
- ...launched by an `extremist group` to cripple a city's power grid and demand political concessions is **cyber terrorism**.

---

### ✅ In a Nutshell

- Cyber terrorism = using hacking to **terrorize, coerce, pressure, or destabilize** a society or government. It’s not about money—it’s about power, fear, and ideology.

- It's the convergence(main cause) of **cyberspace** and **political violence.**

---

### 11. Cyber Security of Critical Infrastructure

Critical Infrastructure (CI) = systems essential for national security & daily life.

- **Sectors**: Power grids, oil & gas, hospitals, transport, water supply, telecom, finance.
- **Why vulnerable?**

  - Old legacy systems (SCADA/ICS not designed with security).
  - Interconnected → one weak link = chain collapse.
  - High impact → even short downtime = chaos.
- **Defense strategies**:

  - Segmentation (air-gapped networks).
  - Continuous monitoring.
  - Redundancy & failover systems.
  - Legal protection → In India: *National Critical Information Infrastructure Protection Centre (NCIIPC)*.

---

### 12. Cybersecurity — Organizational Implications

For organizations, cybersecurity is not just tech → it’s **business survival**.

- **Business losses**:

  - Financial (data breach costs, downtime).
  - Reputation (loss of customer trust).
- **Legal liabilities**:

  - **GDPR (EU)** → heavy fines for data misuse.
  - **IT Act 2000 (India)** → penalties for breaches.
- **Governance Frameworks**:

  - ISO 27001 (InfoSec Mgmt).
  - NIST CSF (Identify → Protect → Detect → Respond → Recover).
  - COBIT (IT governance).
- **Security Investment**:

  - **SOCs** (Security Operations Centers) → 24x7 monitoring.
  - Threat intelligence & red team exercises.
  - Employee training (since *humans = weakest link*).

💡 Bottom line: Cybersecurity is **not optional**, it’s a boardroom-level priority.

---

## Unit 2 — Hackers and Cyber Crimes

### 1. Types of Hackers

When people hear “hacker,” they usually imagine a person in a hoodie breaking into banks 🤣. But in reality, **hackers aren’t always bad**. They’re just people with technical skills who use them differently.

- **White Hat Hackers (Ethical Hackers):**

  - Work with permission.
  - Example: Companies hire them for penetration testing (to find flaws before criminals do).
  - They follow a scope and rules of engagement.

- **Black Hat Hackers (Criminals):**

  - Break into systems without consent.
  - Motives: money, fame, revenge, spying.
  - Example: Ransomware gangs like “Conti” or “REvil.”

- **Grey Hat Hackers:**

  - Somewhere in between.
  - They may break into a system **without permission**, but not always for evil. Sometimes they disclose flaws (responsibly or irresponsibly).
  - Example: A researcher hacks into a site, then emails the company, “Fix this or I’ll leak it.”

- **Script Kiddies:**

  - Beginners who don’t really understand hacking.
  - They use pre-built tools/scripts found online (like Kali Linux payloads) without knowing how they work.
  - More of a nuisance than a real threat, but can still cause harm.

- **Hacktivists:**

  - Hacking for activism.
  - Goal: spread ideology, embarrass organizations, protest.
  - Example: Anonymous group defacing websites for political causes.

- **State-Sponsored Hackers (Nation-State Hackers):**

  - Backed by governments.
  - Used for espionage, stealing secrets, disrupting enemy infrastructure.
  - Example: Alleged Russian groups (APT28, Fancy Bear), Chinese APTs, US NSA’s cyber operations.

---

### 👩‍🏫 Types of Hackers — Comparative Table

| Hacker Type          | Hat Color 🎩 | Intent / Goal                        | Example                                               |
| -------------------- | ------------ | ------------------------------------ | ----------------------------------------------------- |
| **White Hat**        | 🤍 White     | Legal, ethical, improve security     | Company hires them for penetration testing            |
| **Black Hat**        | 🏴 Black     | Illegal, malicious, steal data/money | Hacker stealing credit card info                      |
| **Grey Hat**         | ⚪ Grey      | Illegal methods but no bad intent    | Finds bug in govt website, reports without permission |
| **Script Kiddies**   | 👶 No hat    | No deep skills, just use tools       | Teen using ready-made malware from forums             |
| **Hacktivists**      | ✊ Variable  | Political/social agenda              | Anonymous defacing gov websites                       |
| **State-sponsored**  | 🕵️ Any hat   | Government spying/attacks            | China/USA hacking rival nations                       |
| **Cyber Terrorists** | 💣 None      | Spread fear, chaos                   | Attacking power grids or hospitals                    |

#### 💡 Tip to remember

Think of hackers like characters in a movie:

- White Hat = Hero,
- Black Hat = Villain,
- Grey Hat = Anti-hero,
- Script Kiddie = Side character messing things up,
- Hacktivist = Rebel,
- State-Sponsored = Government’s secret agents,
- Cyber-Terrorists = Daku Mangal Singh from Chota Bheem 🟠.

---

### 2. Hackers vs Crackers

This one’s a common confusion. Many people call all bad hackers "crackers," but the line is a bit blurry. Let’s clear it:

#### Hackers (Original Meaning)

- Not negative at first!
- Originally (1960s–70s at MIT), “hacker” meant **a tech enthusiast** who loved tinkering, coding, solving problems.
- Today it’s broader → could be good (ethical hacker) or bad (malicious hacker).

#### Crackers

- Term for those who **illegally break into systems** or **break software protections.**
- Example: Someone who “cracks” paid software to remove license checks.
- Purely negative connotation, unlike the word “hacker” which can be good or bad.

#### Did Crackers bless us (“torrent messiahs”)?

Crackers made the following possible too:

- Once upon a time, there exists a lot of movie watchers who survived the harsh prices by using torrent and VLC Media Player 😂.
- When you use a paid software for free via cracked torrent sites you're providing the price indirectly unknowingly by selling your privacy 😭.

---

⚖️ **Simple distinction:**

- **Hacker = skillful person** (good or bad, depends on intent).
- **Cracker = bad guy** (always malicious, especially breaking protections).

---

🎯 **Memory Trick:**
Think of “Cracker” like cracking a lock. If someone cracks your lock, they’re clearly not doing it for fun, they’re stealing something.

---

### 3. Cyber-Attacks and Vulnerabilities

🔑 **Core Idea:**
A cyber-attack exploits a **vulnerability** (weakness) in a system, app, or human.

- **Cyber-Attack** = malicious action (like phishing, DoS, malware injection).
- **Vulnerability** = weakness/flaw (like unpatched software, weak passwords, misconfigurations).

---

Cyber-attacks exploit weaknesses (vulnerabilities) in systems, apps, or human behavior.

- **Attack** = deliberate action (phishing, ransomware, DoS).
- **Vulnerability** = weakness (unpatched software, weak password, misconfigurations).
- **Exploit** = the actual tool/technique used to take advantage of a vulnerability.

👉 Example:

- Weak Wi-Fi password (**vulnerability**) → attacker uses brute force (**exploit**) → steals your Wi-Fi bandwidth (**attack**).

---

#### 🧩 Examples of Vulnerabilities

- Unpatched OS/software (e.g., Windows not updated).
- Misconfigured firewalls.
- Using “admin/admin123” as a password (😬).
- Outdated SSL certificates.
- Employees clicking malicious links.

---

#### 🕵️ Attack + Vulnerability Example

- **Attack:** SQL Injection.
- **Vulnerability:** Poorly coded login form that doesn’t sanitize input.

⚡ **Link it like this:**  
Vulnerability = unlocked door 🚪  
Cyber-Attack = thief walking in 🏃‍♂️

### 🔐 SSL Certificates (now mostly TLS)

SSL = **Secure Sockets Layer** (old term, but everyone still says “SSL”). TLS = **Transport Layer Security** (modern standard).

Basically, an **SSL/TLS certificate** is a **digital passport** for a website 🌍. It proves the site is who it says it is, and it enables **encrypted communication** between your browser and the server.

---

### 🧩 What it does

1. **Authentication** – Confirms the website is legit (not a fake phishing site).
2. **Encryption** – Data you send/receive (passwords, card numbers) is scrambled 🔒.
3. **Trust** – Shows up as the 🔒 padlock in your browser’s address bar.

---

### 🌟 Example

- You log into your bank site.
- Without SSL: Your username/password could be sniffed as plain text 😱.
- With SSL: Data is encrypted into unreadable gibberish ✨, only the bank’s server can decrypt it.

---

⚠️ If a site’s SSL is expired or missing, you’ll see **“Not Secure”** in the browser. That’s a vulnerability — attackers can exploit it (man-in-the-middle attacks, fake sites, etc.).

😁 — The **“s” in HTTPS** literally stands for **secure**, and that security is powered by SSL/TLS certificates.

---

### 4. Malware Threats

Malware = **malicious software**.

1. ### **Adware**

   - Hooks into browsers (extensions, registry run-keys, scheduled tasks).
   - Opens pop-ups, redirects search results, shows fake ads.
   - Often bundled with pirated software.

   #### 📢 Types of Adware

   Adware's main goal is to **generate revenue by showing ads**. Its "type" is defined by its level of intrusiveness and how it gets on your system.

   a. **Legitimate Adware (The Annoying but Legal Kind)**
      - **How it works:** This is often bundled with free software. You agree to install it in exchange for using the software for free. The ads are displayed within the program itself.
      - **Example:** Many free PDF converters or video players show ads inside their application window.

   b. **Spyware-Based Adware (The Illegal, Malicious Kind)**
      - **How it works:** This is installed without your consent, often through software bundles ("potentially unwanted programs" or PUPs) or exploits. It's more malicious because it **tracks your browsing habits** to serve you targeted ads.
      - **It can also:**
         - Redirect your browser searches.
         - Change your homepage to an ad-filled search engine.
         - Install browser toolbars that collect data.
      - **Example:** The **Fireball** adware infected millions of computers, taking over browsers to generate fake ad revenue.

   c. **Scareware**
      - **How it works:** This is a nasty type of adware that uses **fear and deception**. It bombards you with pop-up ads pretending to be system alerts, warning you of a (non-existent) virus. The goal is to trick you into buying fake antivirus software.
      - **Example:** "WARNING! YOUR COMPUTER IS INFECTED WITH 127 VIRUSES! CLICK HERE TO CLEAN IT NOW!" These pop-ups look official but are complete scams.

2. **Spyware/Keylogger**

   - Runs silently.
   - Keyloggers (record keystrokes), clipboard stealers, screen recorders.
   - Common in cracked apps and “free toolbars.”

3. **Ransomware**

   - Encrypts files with strong ciphers (AES, RSA).
   - Drops a ransom note (`readme.txt`).
   - Without the decryption key (held by attacker), files are locked forever.

4. **Rootkits**

   - Hide themselves deep inside OS (drivers, kernel modules).
   - Make malicious processes/files invisible to user and antivirus.

5. **Worms**

   - Spread *on their own* through networks (e.g., email, USB, unpatched servers).
   - Famous: WannaCry (2017).

6. **Trojans**

   - Fake software carrying hidden payload (backdoor, spyware, crypto-miner).
   - Example: “Free Game.exe” that secretly gives hacker remote access.

7. **Backdoors**

   - Secret entry points intentionally created (or planted by malware).
   - Allow attackers to bypass authentication later.

---

💡 **Why cracked/torrent software is risky?**  
Because attackers know: “People want it free → They’ll disable antivirus to install → Perfect chance to slip in malware.”

👉 **Real case:** WannaCry ransomware in 2017 hit hospitals, banks, railways.

---

### 5. Sniffing

In the simplest terms, **sniffing is the act of intercepting, capturing, and monitoring data packets as they travel across a network.** Think of it like tapping a phone line to listen to a conversation.

A specialized software tool called a **sniffer** (or more formally, a **packet analyzer**) is used to do this. It puts a device's network card into "promiscuous mode," allowing it to see all the data flowing through the network, not just the data intended for it.

---

#### The Car Analogy

Imagine a network is a highway, and data packets are cars carrying letters (your data).

- **Normal Operation:** Your house (computer) only accepts cars (data packets) that have your specific address on them.
- **Sniffing:** Someone sets up a camera on the highway that records every single car that passes by, reads all the letters inside, and notes where they're going and coming from. This camera is the **sniffer**.

---

#### Why is Sniffing Done? The Two Sides

Sniffing itself is a neutral tool. Its morality depends on **who is doing it** and **why**.

#### 1. The Good Side: Ethical & Administrative

Network administrators use sniffing for crucial maintenance and security tasks. This is **perfectly legal** with authorization.

- **Troubleshooting:** To find and fix network problems, like why a website is loading slowly.
- **Monitoring Performance:** To analyze network traffic and see if the network is getting overloaded.
- **Security Monitoring:** To detect malicious activity, like intrusion attempts or malware calling home.

#### 2. The Bad Side: Malicious & Unethical

This is what most people fear when they hear "sniffing." Hackers use it to steal sensitive information illegally.

- **Stealing Credentials:** Capturing usernames and passwords sent over unencrypted connections (like on some public Wi-Fi networks).
- **Session Hijacking:** Stealing session cookies to impersonate a user and gain unauthorized access to their accounts (like social media or email).
- **Espionage:** Reading confidential company emails or documents being sent over the network.
- **Mapping the Network:** Understanding the structure of a network to plan further attacks.

---

#### Types of Sniffing

| Type | How It Works | Analogy |
| :--- | :--- | :--- |
| **Passive Sniffing** | Listening to traffic on a network hub, where all data is broadcast to every device. Easy and undetectable. | Listening to a conversation in a crowded, noisy room where everyone is shouting. |
| **Active Sniffing** | Used on switched networks. Tricks the network switch into sending the sniffer traffic meant for other devices. More complex and detectable. | Tricking the post office into sending you everyone's mail instead of just your own. |

---

#### How to Protect Yourself from Malicious Sniffing

You can't always prevent sniffing, but you can make the captured data useless to the attacker.

1. **Use HTTPS (The Padlock):** Ensure websites you log into have `https://` and a padlock in the address bar. This **encrypts** the data between your browser and the website. A sniffer might capture the data, but it will look like gibberish without the encryption key.
2. **Use a VPN (Virtual Private Network):** A VPN encrypts *all* your internet traffic from your device to the VPN server. This is **crucial on public Wi-Fi networks** (airports, cafes), which are prime targets for sniffing.
3. **Avoid Unencrypted Protocols:** Be wary of websites that use `http://` (without the 'S'), especially for logins. Never enter sensitive information on such sites.
4. **Be cautious on Public Wi-Fi:** Assume any traffic on a public network is being watched. Do not do online banking, shopping, or check email without a VPN.

**In summary: Sniffing is the interception of network traffic. It's a powerful tool for good in the hands of network administrators but a dangerous weapon in the hands of hackers. Always use encrypted connections (HTTPS, VPN) to protect your data from it.**

### 6. Packet Sniffer

A **packet sniffer** (also known as a **network analyzer** or **protocol analyzer**) is the specific hardware or, more commonly, software tool used to perform sniffing.

If sniffing is the *act* of listening to network traffic, a packet sniffer is the *device* or *application* that makes it possible. It's the "camera on the highway" or the "tapped phone line" from our analogies.

---

### How Does a Packet Sniffer Work?

A sniffer works by exploiting a fundamental feature of how networks operate:

1. **Promiscuous Mode:** Normally, **a network interface controller (NIC)** — your computer's network card — only pays attention to data packets specifically addressed to it. A sniffer puts the NIC into **"promiscuous mode."** In this mode, the NIC ignores the destination address and captures **every single packet** that passes through the network segment it is connected to.
2. **Capture & Decode:** The sniffer captures these raw, binary data packets off the wire.
3. **Analysis:** The software then decodes the packets, organizing the raw data into readable formats according to the rules of network protocols (like Ethernet, TCP/IP, HTTP). It can display everything from which computers are talking to each other to the actual content of their conversation.

---

#### Common Packet Sniffer Tools

These tools are used by both **security professionals (ethical)** and **hackers (malicious)**.

| Tool Name | Primary Use | Platform |
| :--- | :--- | :--- |
| **Wireshark** | The world's most popular and widely-used network protocol analyzer. It is free, open-source, and incredibly powerful for deep analysis. | Windows, macOS, Linux |
| **tcpdump** | A command-line-based packet analyzer. It is the predecessor to Wireshark and is a powerful tool available by default on most Unix-like systems (Linux, macOS). | Linux, macOS, Unix |
| **TShark** | The command-line version of Wireshark. Useful for automating capture and analysis. | Windows, macOS, Linux |
| **Kismet** | A powerful tool specifically for sniffing wireless (Wi-Fi) networks. It can detect hidden networks and capture traffic. | Linux, macOS |
| **Cain & Abel** | A older but famous tool for Windows that could sniff passwords, perform ARP poisoning, and crack encrypted passwords. | Windows |

---

#### The Two Sides of a Packet Sniffer: A Tool is Just a Tool

| For Good (Ethical) | For Bad (Malicious) |
| :--- | :--- |
| **Network Diagnosis:** A sysadmin uses **Wireshark** to find why the network is slow and discovers a single computer is flooding the network with requests. | **Credential Theft:** A hacker uses **Wireshark** on a public Wi-Fi to capture unencrypted login packets for a website that uses `http://` instead of `https://`. |
| **Security Auditing:** A cybersecurity analyst uses **tcpdump** on a server to monitor for suspicious incoming connections and intrusion attempts. | **Espionage:** A malicious insider uses a sniffer to capture and read unencrypted email traffic within a corporate network. |
| **Software Development:** A developer uses **Wireshark** to debug why their new app is not communicating correctly with a server. | **Session Hijacking:** An attacker uses **Cain & Abel** to perform ARP spoofing and capture session cookies to hijack a user's logged-in account. |

#### How to Defend Against Malicious Packet Sniffing

The defense isn't to prevent the *sniffing* itself, but to render the *captured data useless*.

1. **Encryption, Encryption, Encryption:** This is the ultimate defense.
    - **HTTPS/SSL/TLS:** Ensures your web traffic is encrypted. Look for the padlock icon in your browser.
    - **VPN (Virtual Private Network):** Encrypts *all* traffic from your device to the VPN server, making it unreadable to any sniffer on your local network (e.g., public Wi-Fi).
    - **SSH (Secure Shell):** Encrypts remote command-line logins and file transfers.
    - **Encrypted Messaging:** Use apps like Signal, WhatsApp (with E2E encryption enabled).

2. **Network Segmentation:** Breaking a network into smaller subnets (segments) limits how much traffic a sniffer can see. A sniffer on the "Guest Wi-Fi" segment shouldn't be able to see traffic on the "Finance Department" segment.

3. **Switched Networks:** Modern networks use **switches**, which are smarter than old hubs. They send data only to the specific device it's intended for, making passive sniffing ineffective. (However, attackers use techniques like **ARP spoofing** to bypass this).

**In summary:** A **packet sniffer** is the tool that makes **sniffing** possible. It's a powerful double-edged sword, vital for managing and securing networks, but also a potent weapon for attackers. The best defense is to ensure your sensitive data is always encrypted in transit.

---

### 7. Gaining Access

Goal of most hackers = **get inside**.

- Brute force, credential stuffing.
- Exploiting software bugs.
- Social engineering (“Hey IT support, I lost my password…”).
- Phishing → fake login page.

👉 Think of it like breaking the lock to enter a house.

---

### 8. Escalating Privileges

Once inside → attacker wants **admin/root power**.

- **Vertical escalation** → normal user → admin.
- **Horizontal escalation** → one user → another user (same level).

👉 Example: From student login to faculty/admin portal.

---

### 9. Executing Applications

Running malicious code inside the target.

- Drop malware → execute it.
- Remote access tools (RATs).
- Scripts that steal data or open backdoors.

👉 It’s like planting a spy robot inside the system.

---

### 10. Hiding Files

After planting, hacker hides the traces.

- Rootkits → hide processes/files.
- Rename/move files.
- Store in unusual locations (e.g., system drivers).

👉 Think: “Invisible cloak” for malware.

---

### 11. Covering Tracks

Final step = remove evidence.

- Clear logs.
- Delete malware after mission.
- Fake timestamps.

👉 So investigators can’t trace them easily.

---

### 12. Virus

- **Analogy:** A biological virus. It needs a host to survive and spread.
- **Definition:** A piece of **malicious code** that attaches itself to a legitimate, executable file or program (e.g., a `.exe` file, a Word document with macros). It cannot run on its own.
- **Key Characteristic: Requires Human Action.** It relies on a user to execute the infected host file. Once executed, it replicates by inserting its code into other files on the same system.
- **Primary Purpose:** To spread to other files, corrupt data, and sometimes deliver a payload (like deleting files or displaying messages).

#### 🦠 Types of Viruses

1. **File Infector Virus**
    - **What it infects:** It attaches itself to executable files (like `.exe`, `.com`, `.scr` files).
    - **How it works:** When the infected file is run, the virus activates and can spread to other files. This can destroy the host file, corrupting programs.
    - **Example:** The classic **CIH** virus (also known as "Chernobyl").

2. **Boot Sector Virus**
    - **What it infects:** It infects the Master Boot Record (MBR) of a hard drive or the boot sector of a floppy disk.
    - **How it works:** It loads into memory every time the computer starts up, even before the operating system loads, making it very hard to remove.
    - **Example:** **Stoned** virus was a common boot sector virus.

3. **Macro Virus**
    - **What it infects:** It infects documents, not programs. It embeds malicious code in the macros of documents like Microsoft Word (`.doc`), Excel (`.xls`), or PowerPoint.
    - **How it works:** When you open the infected document and enable macros, the virus runs and can infect other documents.
    - **Example:** The **Melissa** virus spread via email attachments and infected Word documents.

4. **Multipartite Virus**
    - **What it infects:** A hybrid virus that can infect both **boot sectors** and **files**.
    - **Why it's dangerous:** It uses multiple methods to spread, making it more complex and harder to eradicate.

5. **Polymorphic Virus**
    - **Its Special Power: It changes itself.** It encrypts its code differently each time it infects a new file. This changing signature makes it very difficult for traditional antivirus software to detect.
    - **Example:** The **Storm Worm** used polymorphic code to avoid detection.

6. **Metamorphic Virus**
    - **Even more advanced than polymorphic.** It doesn't just encrypt itself differently; it completely **rewrites its own code** each time it infects a new file. It's like a criminal who gets a full plastic surgery after every crime.

---

### 12. Worm

- **Analogy:** A self-replicating parasite. It doesn't need a host; it's a standalone organism.
- **Definition:** A **standalone malicious program** that replicates itself to spread to other computers. It operates independently.
- **Key Characteristic: Self-Replicating and Spreads Automatically.** It exploits vulnerabilities in network services or operating systems (e.g., EternalBlue) or tricks users (e.g., email attachments) to spread without any human interaction after the initial execution. This makes worms incredibly dangerous for generating massive network-wide infections.
- **Primary Purpose:** To spread as widely as possible, often overwhelming networks (a "denial-of-service" effect). It can also carry a destructive payload.
- **Is a Worm a Virus?** No. This is a key distinction. **All worms are not viruses, but all viruses are not worms.** A worm is a type of malware that is defined by its **method of spreading (self-replication over networks)**. A virus is defined by its **method of infecting (requiring a host file)**.

### 🐛 Types of Worms

A worm is defined by its **self-replicating nature** and its ability to spread without a host file. Their types are often categorized by their **method of propagation**.

1. **Email Worms**
    - **How they spread:** They spread by sending copies of themselves to all contacts in a victim's email address book.
    - **Trickery:** They often use compelling subject lines like "I love you," "Your invoice," or "Your video."
    - **Famous Example:** The **ILOVEYOU** worm (2000) caused billions in damage by overwriting files and spreading via email.

2. **Network Worms (or Internet Worms)**
    - **How they spread:** They exploit vulnerabilities in network services to spread across the internet or a local network. They don't need user interaction.
    - **How it works:** The worm scans the internet for computers that have a specific weakness (e.g., an unpatched Windows flaw), then copies itself to that machine.
    - **Famous Example:** **WannaCry** was a ransomware *worm*. It used the "EternalBlue" exploit to spread rapidly across networks.

3. **File-Sharing Worms (P2P Worms)**
    - **How they spread:** They copy themselves into shared folders on peer-to-peer (P2P) file-sharing networks (like BitTorrent or old-school LimeWire).
    - **Trickery:** They disguise themselves with names of popular movies, songs, or cracked software.
    - **Example:** A user downloads "Latest_Movie.mp4.exe" from a torrent site, which is actually a worm.

4. **Instant Messaging (IM) Worms**
    - **How they spread:** Similar to email worms, but they send malicious links to all contacts on messaging apps like WhatsApp, Telegram, or Facebook Messenger.
    - **Trickery:** The message is often something urgent or curious, like "Is this you in this video?" with a link.

5. **IRC Worms**
    - **Old-school but classic:** They spread through Internet Relay Chat (IRC) channels by sending infected files or scripts to other users.

---

### 12. Trojan Horse (or Trojan)

- **Analogy:** The ancient Greek story. It looks like a desirable gift but hides soldiers inside.
- **Definition:** A type of malware that **disguises itself as legitimate or desirable software** (e.g., a free game, a cracked program, a fake software update).
- **Key Characteristic: Deception and No Self-Replication.** It does not replicate itself or infect other files. Its power lies in tricking the user into installing it. Once inside, it performs a malicious action on the victim's system.
- **Primary Purpose:** To create a **backdoor**, steal data (banking info, passwords), spy on the user (keylogging), or download other malware. Its purpose is specific and targeted.

#### 🎭 Types of Trojan

1. **Backdoor Trojan**
    - **Purpose:** Creates a "backdoor" on your system, giving the attacker remote control. It's the most common type.
    - **Example:** The attacker can run commands, steal files, or use your computer as part of a botnet.

2. **Banking Trojan**
    - **Purpose:** Specifically designed to steal your online banking credentials and credit card information.
    - **How:** It often uses a **web inject** technique—it modifies the web pages you see in your browser on the fly, adding extra fields to capture your PIN or password.
    - **Example:** **Zeus** is a famous banking Trojan.

3. **DDoS Trojan (Botnet Trojan)**
    - **Purpose:** Infects your computer to turn it into a **zombie** or **bot**. The attacker then controls thousands of these bots to launch Distributed Denial-of-Service (DDoS) attacks against websites.
    - **Example:** The **Mirai** botnet that took down major websites.

4. **Downloader Trojan**
    - **Purpose:** Its main job is to download and install other malicious software onto your system. It's the "first wave" of an attack.
    - **Example:** You download a fake game installer (the downloader), which then secretly installs a ransomware and a keylogger.

5. **Ransom Trojan (Ransomware)**
    - **Purpose:** Locks your files or system and demands a ransom to unlock them.
    - **Example:** **WannaCry**.

6. **Info-Stealing Trojan**
    - **Purpose:** Steals any valuable information from your computer: saved browser passwords, documents, keystrokes (keylogging), screenshots, and instant messaging logs.
    - **Example:** Many spyware tools fall into this category.

**Key Point:** Most modern Trojans are **blended threats**—a single Trojan can act as a backdoor, downloader, and info-stealer all at once.

---

### 12. Backdoor

- **Analogy:** A secret entrance built into a castle that bypasses the main gate and its guards.
- **Definition:** Not malware itself, but a **method or vulnerability** that bypasses normal authentication and security mechanisms. It provides remote, unauthorized access to a system for an attacker.
- **Key Characteristic: Provides Covert Access.** It can be installed by a Trojan, a virus, a worm, or even intentionally by a developer for debugging (though this is a major security risk).
- **Primary Purpose:** To give an attacker persistent, stealthy control over a compromised system. The malware that creates the backdoor is often just the delivery mechanism; the backdoor itself is the real threat.

👉 Backdoor = like giving yourself a spare key 🔑.

---

### 🧠 Combined Malware Summary Table

| Malware Family | What it Is / How it Spreads | Key Types | Main Goal |
| :--- | :--- | :--- | :--- |
| **Virus** | **Parasite.** Must attach to a clean file and needs a human to run it. | File Infector, Boot Sector, Macro, Multipartite | **Infect & Corrupt:** Spread to other files and damage them. |
| **Worm** | **Self-Replicator.** Spreads automatically over networks without human help. | Email, Network, P2P, IM | **Spread & Overwhelm:** Propagate as fast as possible to cause chaos. |
| **Trojan** | **Imposter.** Tricks you into installing it by pretending to be legitimate software. | Backdoor, Banking, DDoS, Downloader | **Steal & Control:** Create backdoors, steal data, or download other malware. |
| **Adware** | **Annoying Salesman.** Generates revenue by showing unwanted ads. | Legitimate (bundled), Spyware-based, Scareware | **Generate Ad Revenue:** Show ads, often by tracking your browsing. |
| **Backdoor** | **Secret Passage.** Not standalone malware, but a feature left behind by other malware. | (N/A - a feature) | **Covert Access:** Give attackers persistent, hidden access to a system. |

---

### How They Work Together: A Common Scenario

Often, these threats work in combination:

1. A user is tricked into downloading and running a **Trojan** (e.g., "free_game_installer.exe").
2. The Trojan doesn't appear to do anything obvious but secretly installs a **backdoor** on the system.
3. The attacker uses the backdoor to upload a **worm** to the computer.
4. The **worm** then spreads automatically across the corporate network, infecting dozens of other machines.
5. The worm carries a **virus** as its payload, which infects and corrupts files on every machine it reaches.

This layered approach makes modern malware highly effective and dangerous. Understanding these differences is the first step in defending against them.

---

### 13. Types of Cyber Attacks

1. **DoS/DDoS** → flooding system/network.
2. **Phishing/Spear phishing** → fake emails/websites.
3. **Man-in-the-middle** → intercepting comms.
4. **SQL injection** → inserting malicious queries in database.
5. **Zero-day exploit** → exploiting unknown vulnerabilities.
6. **Password attacks** → brute force, dictionary.
7. **Insider threats** → employees misusing access.

---

#### **Phishing: The "Wide Net" Scattergun Approach**

- **Target:** Anyone and everyone.
- **Method:** Sending massive volumes of generic emails, texts, or social media messages, hoping to catch a small percentage of people.
- **The Bait:** The messages are not personalized. They often create a sense of urgency or fear, like:
  - "Your account has been compromised! Click here to secure it."
  - "You have a package delivery issue. Confirm your address here."
  - "You've won a prize! Claim it now."
- **Analogy:** Casting a giant fishing net into the ocean to catch whatever fish you can.

---

#### **Spear Phishing: The "Harpoon" Precision Attack**

- **Target:** A specific individual, organization, or small group.
- **Method:** The attacker does their homework. They use publicly available information (from LinkedIn, company websites, social media) to craft a highly convincing and personalized message.
- **The Bait:** The message appears to come from a trusted source and references specific details to build trust. For example:
  - An email to an accountant pretending to be the CEO, urgently requesting a wire transfer for a "confidential acquisition."
  - An email to an HR staffer with a malicious resume attachment, supposedly from a highly-recommended candidate.
  - An email to a system administrator pretending to be from the IT vendor, asking them to reset a password on a fake login portal.
- **Analogy:** A fisherman using a speargun to target one specific, high-value fish.

---

#### **A More Extreme Version: Whaling**

You might also hear the term **"Whaling,"** which is a type of spear phishing that targets the "big fish"—CEOs, CFOs, other high-level executives. The level of research and personalization is even higher, as the potential payoff for the attacker is much greater.

---

**In a nutshell:**

- **Phishing:** "Dear Customer, your account is on hold."
- **Spear Phishing:** "Hi [Your Full Name], I loved your presentation at the [Real Conference Name] last week. Here's that report you asked for. [Malicious Link]"
- **Whaling:** "John, this is urgent. I need you to wire $50,000 to account X for the confidential merger we discussed. This is top priority. - [Spoofed CEO's Name]"

---

### 🔍 14. Advanced Persistent Threats (APTs)

**What it is:**
An **Advanced Persistent Threat (APT)** is not just a single attack, but a **long-term, targeted campaign** where an attacker (often state-sponsored) gains unauthorized access to a network and remains undetected for a long period—months or even years.

Think of it as a **digital spy movie**. It's not a smash-and-grab robbery; it's a spy moving into an apartment across the street from their target, watching their every move for years.

#### Key Characteristics (The "APT" Name Explained)

- **Advanced:** Uses sophisticated, custom-made malware and techniques that bypass standard security.
- **Persistent:** The goal is to maintain long-term access, not just get in and out quickly.
- **Threat:** Carried out by a coordinated, well-funded human team (a *threat actor*), not just an automated script.

#### How it Works: The APT Lifecycle

1. **Initial Compromise:** Usually through a highly targeted spear-phishing email.
2. **Establish Foothold:** Install a backdoor to maintain access.
3. **Escalate Privileges:** Gain admin rights to move freely.
4. **Internal Reconnaissance:** Map the network and find valuable data.
5. **Lateral Movement:** Move from one system to another to reach the target.
6. **Data Exfiltration:** Slowly and stealthily steal data.
7. **Maintain Presence:** Ensure they can get back in even if discovered.

**Why it's dangerous:** Because they are so stealthy, they can steal intellectual property, government secrets, or sensitive data over a long time without anyone noticing.

**Real-World Example:** The **SolarWinds hack** (2020) is a classic APT. Hackers compromised a software update, which then gave them backdoor access to thousands of companies and government agencies that used that software.

---

### ⛏ 15. Cryptojacking

**What it is:**
**Cryptojacking** is the unauthorized use of someone else's computer (or smartphone, or server) to **mine cryptocurrency**. It's like someone sneaking into your house to steal electricity, but in the digital world.

Attackers don't want your data; they want your **computing power** (CPU/GPU cycles) to generate money for them.

#### How it Works

There are two main methods:

1. **Web-based (In-browser mining):**
    - A website you visit runs a JavaScript code in your browser.
    - While you're on the site, your CPU usage spikes, mining crypto for the site owner.
    - Your computer might slow down and get hot.
    - This is often done by shady websites or even ads on legitimate sites.

2. **Malware-based:**
    - You download a malicious file (e.g., a pirated software, a fake game).
    - It installs a hidden mining program (often a Monero miner, as it's hard to trace).
    - The program runs silently in the background whenever your computer is on.

**Why it's common:** It provides a direct financial reward for attackers with a lower risk than ransomware (it's quieter and often not noticed by the victim).

**How to spot it:** Your device is unusually slow, fans are running loudly for no reason, and your electricity bill might go up!

---

### Some fun story

You might be surprised to hear about a friend's early experiences with computers. His very first PC was technically genuine hardware, but it came with an unauthorized copy of Windows. He noticed something was wrong almost immediately—his Chrome browser would pop up with ads every couple of minutes. It turned out to be adware.

He followed online tutorials to clean it up. The scary part was realizing how sophisticated some of these attacks were. They slowly tried to disable Windows Defender, and at one point, his computer wouldn’t even restart properly. He even found changes deep in the system—like in the Registry, where Windows manages app and system settings—with values being altered from 0 to 1. He kept deleting those entries like a daily routine check until he finally decided to just install a clean version of Windows 10 himself.

He's much more careful now and eventually built his current PC from scratch to avoid those kinds of issues.

The whole situation reminded him of his math teacher back in the day. The teacher used to download movies from, let’s say, less-than-trustworthy torrent sites. While some sites can be relatively safe, the teacher didn’t realize how risky some of those places were. Eventually, his laptop got hijacked, and all his files were encrypted. The hacker left a `readme.txt` asking for ₹2000 to return his data. He asked my friend for help, but at that time, neither of them knew how to deal with ransomware. It was a tough lesson in digital safety.

---

#### Diagnosis: What Kind of Adware Was It?

Based on the symptoms—**"PC with an unauthorized Windows copy"** and **"Chrome popping up with ads every couple of minutes"**—this was almost certainly a case of **Spyware-Based Adware** (the malicious kind), specifically bundled as a **Potentially Unwanted Program (PUP)**.

Let's break down why:

1. **The Delivery Method: Software Bundling (The "Trojan Horse" Method)**

   - **How it got there:** The unauthorized Windows copy (the "cracked" or pirated version) didn't just contain Windows. The person who created the install ISO file **bundled** additional software with it to make money.
   - **The Deal:** You get Windows for free, but in exchange, you also silently agree to install a bunch of adware, browser toolbars, and other PUPs that generate revenue for the software cracker.
   - **This is the most common way** this type of adware spreads. It doesn't need to exploit a vulnerability; it tricks you into installing it yourself.

2. **The Specific Type: Browser Hijacker & Ad-Injector**

   - **Ad-Injection:** The adware modified browser settings (Chrome in this case) to inject additional, unwanted advertisements into every webpage he visited, and to pop up new ad windows.
   - **Browser Hijacking:** It likely also changed his default search engine and homepage to a shady, ad-filled search portal that pays the hijacker for traffic.

3. **The Technical Mechanism: How It Works**

   The adware probably installed these components on his system:

   - **Browser Extensions:** It secretly installed malicious extensions in Chrome that had the permission to "read and change all your data on the websites you visit." This is how it injected ads.
   - **Scheduled Tasks:** It created scheduled tasks in Windows to run itself again at regular intervals, ensuring it would re-appear even if he tried to remove it.
   - **Registry Modifications:** It added itself to the Windows Registry run keys, so it would launch every time the computer started.

---

#### Summary of his experience

- **Adware hijacking Chrome** (classic nuisanceware)
- **Tampering with Windows Registry**(The Registry, where 0/1 values toggle features/security controls 🟢🔴)
- **Disabled Windows Defender** (malware LOVES to kill protections first)
- **Ransomware** on teacher’s laptop (yep, textbook “pay me or lose your files” situation 💸)

> **Unauthorized Software ➔ Software Bundle ➔ Malicious PUP/Adware ➔ Browser Hijacker & Ad-Injector**

---

### Quiz (Unit 2 Recap)📝

1. Which attack type involves secretly listening to network traffic?  
   a) Spoofing  
   b) Sniffing  
   c) DoS  
   d) SQL Injection

2. What’s the difference between a Worm and a Virus?

3. When an attacker upgrades from “normal user” to “admin,” what’s that called?

4. Which malware pretends to be useful but contains hidden malicious code?

5. Name **two ways hackers cover their tracks** after an attack.

#### Solutions ✅

1. **Sniffing**
2. Worms are self-replicating without human help; Viruses need a trigger (file execution, sharing, etc.).
3. **Privilege Escalation** (when a hacker gains admin/root from normal user).
4. Trojan Horse.
5. Covering tracks = deleting logs, altering timestamps, fake entries, and sometimes even planting *“anti-forensics malware”* to wipe traces.

---

## Unit 3 — Ethical Hacking & Social Engineering

### 🔹 1. Ethical Hacking Concepts and Scopes

👉 **What is Ethical Hacking?**

- **Hacking** = breaking into systems.
- **Ethical hacking** = doing the same thing but *legally* and *with permission* to improve security.
- Ethical hackers are also called **White Hat hackers**.

👉 **Why is it done?**

- To **find vulnerabilities** before black hats exploit them.
- To **strengthen systems** by patching those weaknesses.

👉 **Scope** (very important for exams ⚡):

- Defines what an ethical hacker *can* and *cannot* do.
- Example: You’re hired to test a bank’s website:

  - **In-scope** → test login, SQL injection, session handling.
  - **Out-of-scope** → DoS attacks, customer data deletion.

👉 **Types of scope**:

- **Black-box testing** → hacker has no info (like an outsider).
- **White-box testing** → hacker has full info (like source code, architecture).
- **Gray-box testing** → partial info (like credentials but not full architecture).

---

### 🔹 2. Threats and Attack Vectors

👉 **Threat** = any potential danger that can exploit a weakness.  
👉 **Attack Vector** = the *pathway* or *method* hackers use to deliver that attack.

Think of it like this:

- **Threat** = burglar wants to rob your house.
- **Attack vector** = he uses an *unlocked window* or *fake delivery guy disguise*.

---

✅ **Common Attack Vectors**

1. **Network-based**

   - Exploiting weak Wi-Fi, sniffing packets, MITM (man-in-the-middle).

2. **Web-based**

   - SQL injection, XSS (cross-site scripting), file uploads.

3. **Email/Phishing**

   - Fake login pages, malicious attachments.

4. **Removable Media**

   - Infected USB drives (classic way of spreading worms).

5. **Social Engineering**

   - Manipulating humans instead of machines (fake tech support call).

6. **Insider Threats**

   - Disgruntled employees misusing access.

7. **Physical Access**

   - Someone plugging directly into your machine/server.

---

⚡ **Key takeaway**: Threats exist everywhere, but attack vectors are the **entry doors** hackers choose.

---

### Quiz – Threats & Attack Vectors

Answer in short (one word/sentence is fine):

1. A hacker sends you a phishing email with a fake login page.  
   👉 What’s the **attack vector**?

2. Your system has a weak, outdated Wi-Fi password.  
   👉 What’s the **attack vector**?

3. A disgruntled employee leaks company data.  
   👉 What’s the **threat type** here?

4. Which is broader in scope: **threat** or **attack vector**?

#### 🔥 Answers

1. ✅ **Social Engineering** → phishing = classic SE attack vector
2. ✅ **Network-based** → weak Wi-Fi is a doorway in
3. ✅ **Insider Threat** → disgruntled employee = textbook case (disgruntled meaning angry or dissatisfied)
4. ✅ **threat is the “what” (danger)**, **attack vector is the “how” (path/doorway)**.

---

### 3. Information Assurance (IA)

Think of IA as the **umbrella** of everything we’ve been talking about so far. It’s not just about *defending systems*, it’s about **ensuring information stays trustworthy, available, and protected at all times**.

🔑 **The 5 Pillars of Information Assurance (CIA + 2)**

1. **Confidentiality** → Only the right people can see the info.
   *Ex:* Encryption, passwords.

2. **Integrity** → Info must be accurate, unchanged by unauthorized people.
   *Ex:* Hashing, checksums.

3. **Availability** → Info and systems must be accessible when needed.
   *Ex:* Backups, redundancy, DDoS protection.

4. **Authentication** → Verify the identity of users.
   *Ex:* Login, biometrics, multi-factor authentication.

5. **Non-repudiation** → Proving that someone actually did an action, so they can’t deny it later.
   *Ex:* Digital signatures, logs.

💡 Real-world example:
When you do **online banking**, IA ensures:

- Nobody else can see your balance (Confidentiality).
- Your balance isn’t secretly altered (Integrity).
- You can access it anytime (Availability).
- Bank confirms it’s really *you* (Authentication).
- And you can’t deny making a transfer once it’s signed (Non-repudiation).

👉 IA = **protecting information through these five pillars**.

#### 💡 Mnemonic

NRACIA: Non-repudiation, Authentication, Confidentiality, Integrity, Availability

---

### 4. 📌 What is Threat Modelling?

It’s the process of **thinking like an attacker** to figure out:

1. What assets you have (what’s valuable).
2. Who might attack you.
3. How they could attack you (vectors).
4. How bad it would be if they succeed.
5. How to stop them.

---

#### ⚡ Steps in Threat Modelling

1. **Identify Assets** → What do you want to protect?
   *Ex:* Customer data, bank details, source code.

2. **Identify Threats** → Who/what can harm it?
   *Ex:* Hackers, disgruntled insiders, malware, natural disasters.

3. **Identify Vulnerabilities** → Weak points in the system.
   *Ex:* Weak passwords, outdated software, open ports.

4. **Identify Attack Vectors** → How the attack could be carried out.
   *Ex:* Phishing emails, SQL injection, stolen credentials.

5. **Assess Risks** → What happens if they succeed?
   *Ex:* Data breach → reputation loss + legal penalties.

6. **Mitigate Threats** → Apply countermeasures.
   *Ex:* Patch systems, add firewalls, train employees.

💡**Mnemonic:** A-TV-ARM: Assets, Threats, Vulnerabilities, Attack Vectors, Risks, Mitigation

---

#### 🔑 Popular Threat Modelling Methodologies

- **STRIDE (by Microsoft)** → Looks at threats as:

  - **S**poofing identity
  - **T**ampering with data
  - **R**epudiation (denying actions)
  - **I**nformation disclosure
  - **D**enial of Service
  - **E**levation of privilege

- **DREAD** → Risk rating model
  
  - **D**amage
  - **R**eproducibility
  - **E**xploitability
  - **A**ffected users
  - **D**iscoverability

---

#### 💡 Real-life analogy

Imagine protecting your house:

- Asset = Jewelry inside.
- Threat = Thief.
- Vulnerability = Weak lock on the door.
- Attack vector = Breaking the lock.
- Risk = Jewelry stolen.
- Mitigation = Upgrade to strong lock + CCTV.

👉 That’s exactly what threat modelling does for computer systems.

---

### 5. EISA - Enterprise Information Security Architecture

It’s a **blueprint** (or framework) that shows how security fits into every part of an organization’s IT systems.
Think of it as **city planning for security** → where to place roads, traffic signals, and checkpoints so everything runs smoothly and safely.

---

#### 🏗️ Key Components of EISA

1. **Policies & Standards**

   - High-level rules.
   - Example: “All employees must use strong passwords.”

2. **Processes & Procedures**

   - Step-by-step actions to follow.
   - Example: “If someone forgets a password, IT must verify ID before reset.”

3. **Technology Controls**

   - Actual tools used for security.
   - Firewalls, IDS/IPS, antivirus, encryption.

4. **People**

   - Employees must be trained to follow security practices.
   - Example: Security awareness training.

5. **Governance & Compliance**

   - Ensuring everything follows laws and regulations.
   - Example: GDPR, HIPAA, ISO 27001.

**💡 Mnemonic:**
Learn this, it helps:

1. Learn PPT GPT then associate it with Chat GPT
2. GPT = Government People Tech
3. Chat GPT maintains **Policies and Standards** with following **procedures and** executing vector trees as **processes** in background

---

#### ⚡ Layers in Security Architecture

1. **Business Layer** → Why security is needed (protecting business goals).
2. **Information Layer** → Data classification, storage, backups.
3. **Application Layer** → Security in apps (auth, validation).
4. **Technology Layer** → Networks, servers, endpoints.
5. **Physical Layer** → CCTV, biometrics, physical access.

**💡 Mnemonic:** BlueTooth API → BT API  
***B**usiness, **T**echnology, **A**pplication, **P**hysical, **I**nformation*

---

#### 🎯 Goals of EISA

- Ensure **confidentiality, integrity, availability** (CIA triad).
- Provide **standardized security practices** across the organization.
- Reduce **risks, costs, and redundancy**.
- Make sure security supports business objectives (not block them).

---

💡 **Analogy:**
If threat modelling is like planning *how thieves might break into your house*,
EISA is like *designing the entire neighborhood* with police stations, CCTV, streetlights, and locks on every house.

---

### 6. 📌 What is VAPT?

It’s like a **health check-up for systems**:

- **Vulnerability Assessment (VA)** → Finding weaknesses (like a doctor running tests).
- **Penetration Testing (PT)** → Actually trying to exploit them (like a stress test).

---

#### 🛠️ Vulnerability Assessment (VA)

- **Goal:** Identify, classify, and prioritize vulnerabilities.
- **Methods:**
  - Automated scanning tools (Nessus, OpenVAS, Qualys).
  - Manual reviews (config checks, patch levels).
- **Output:** List of vulnerabilities + risk ratings (low, medium, high, critical).

---

#### ⚔️ Penetration Testing (PT)

- **Goal:** Simulate real-world attacks to check if vulnerabilities can be exploited.

- **Approach:**

  1. **Reconnaissance** → Collect info (IP, domain, emails).
  2. **Scanning** → Find open ports, services.
  3. **Gaining Access** → Exploit vulnerability.
  4. **Maintaining Access** → Backdoors, trojans (to test persistence).
  5. **Reporting** → Document findings to the client.

  **Mnemonic:** Remember Student Life Simulator?
    1. **Recon** Syllabus
    2. **Scan** Important Portions
    3. **Gain** Marks
    4. **Maintain access** by revision
    5. **Report** Card  
   You can ignore the forget everything part (cover tracks) for this one 🤣.

- **Types:**

  - Black Box (no info given).
  - White Box (full info given).
  - Grey Box (partial info given).

---

#### 🧠 Difference Between VA and PT

- VA → **Broad but shallow** (finds *all possible* weak spots).
- PT → **Deep but narrow** (tests if weak spots can actually be hacked).

---

⚡ **Analogy:**
VA is like **checking doors and windows** in your house to see if they’re unlocked.
PT is like **hiring a burglar** to test if they can actually break in.

---

### 7. 📨 What is a Ping Packet?

**In Simple Terms:**
A **ping** is like shouting "Hello, are you there?" across a crowded room and waiting to hear a "Yes, I'm here!" in response. It's a basic command to check if another computer on the network is reachable and how long it takes to get a response.

**Technically:**

- It uses **ICMP (Internet Control Message Protocol)** packets.
- You send an **ICMP Echo Request** packet to a target IP address.
- If the target is online and willing to respond, it sends back an **ICMP Echo Reply** packet.

**Why Hackers Use It:**
In the **Reconnaissance** phase, a hacker uses ping sweeps (sending pings to a range of IP addresses) to create a "map" of which machines are alive on a network before targeting them.

**Example:**
`ping 192.168.1.1`
This command will send packets to your router and show you the response time, confirming it's online.

---

### 8. 🗺️ What is Nmap?

**In Simple Terms:**
**Nmap (Network Mapper)** is a super-powered scanner that doesn't just shout "Are you there?" but goes up to a machine, checks all its doors and windows (ports), and even figures out what's behind them (services and operating systems).

**What it does:**

- **Discovers hosts** on a network (like a ping sweep on steroids).
- **Scans ports** to find which ones are open, closed, or filtered.
- **Identifies services** running on those ports (e.g., is it a web server, SSH server, database?).
- Can even guess the **operating system** of the target computer.

**Why Hackers & Admins Love It:**

- **Hackers** use it to find weak points (open ports running vulnerable software).
- **SysAdmins** use it for security audits to find and close holes in their own network.

**Example Command:**
`nmap -sS 192.168.1.105`
This sends a "stealth" SYN scan to the target IP to see which ports are open without fully connecting, making it harder to detect.

---

### 9. 📟 What are nslookup and dig?

These are tools for interrogating the **DNS (Domain Name System)**, which is the phonebook of the internet. They translate human-readable domain names (like `google.com`) into machine-readable IP addresses (like `142.251.42.206`).

#### nslookup (Name Server Lookup)

- A classic, simpler tool available on almost all operating systems.
- Good for quick, simple DNS queries.

**Example:**
`nslookup google.com`
This will ask your default DNS server for the IP address of `google.com`.

#### dig (Domain Information Groper)

- A more powerful and flexible tool, preferred by network administrators for its detailed output.
- Provides more information than `nslookup`, such as TTL (Time to Live), authoritative name servers, and record types.

**Example:**
`dig google.com`
This will give you a detailed breakdown of the DNS resolution process for `google.com`.

**Why Hackers Use Them (DNS Interrogation):**

- **Finding Subdomains:** Attackers use them to find hidden or forgotten subdomains (like `admin.example.com`, `test.example.com`), which might be less secure.
- **Mapping Network Infrastructure:** The DNS records can reveal a lot about a company's network structure, like where their mail servers are (`mail.example.com`) or their main web servers.

---

#### Recap

| Tool/Command | Purpose | Analogy |
| :--- | :--- | :--- |
| **`ping`** | Check if a host is online and responsive. | Shouting "Hello?" across a room. |
| **`nmap`** | Discover hosts, scan ports, identify services and OS on a network. | A detective checking all doors and windows of a building and noting what's behind them. |
| **`nslookup`/`dig`** | Query DNS servers to translate domain names to IPs and get other DNS records. | Looking up a name in a phonebook to find their address and other contact details. |

These are the essential "digital binoculars" and "lock-picking kits" used in the first stage of hacking—gathering information. They are crucial for both attacking and defending a network.

---

### 🕵️ 10. Footprinting & Reconnaissance

**What it is:**
This is the **first and most important phase** of ethical hacking or a cyber attack. It's the process of **gathering information** about a target before launching any attack. You can't attack what you don't know.

Think of it as **casing a bank before robbing it**. You'd note the security guards' routines, the number of doors, the alarm types, etc. In hacking, you're gathering digital clues.

#### Types of Reconnaissance

- **Passive Reconnaissance:** Gathering information without directly interacting with the target. This is stealthy and hard to detect.
  - **Examples:** Searching Google, looking at social media profiles (LinkedIn for employee names), checking the Wayback Machine for old versions of the website, reading news articles about the company.

- **Active Reconnaissance:** Interacting directly with the target system to learn about it. This is riskier because it can be logged and detected.
  - **Examples:**
    - **Ping Sweeps:** Sending ping packets to see which IP addresses are alive on a network.
    - **Port Scanning:** Using tools like `Nmap` to find out which ports are open on a system (e.g., port 80 for web, port 22 for SSH).
    - **DNS Interrogation:** Querying DNS servers to find out about a target's network structure (e.g., `nslookup`, `dig`).

**Why it's crucial:** The more information a hacker gathers in this phase, the more effective and targeted their attack will be. For ethical hackers, this phase helps identify the attack surface.

---

### 11. 🎭 Types of Social Engineering

Social engineering = **hacking the human mind instead of the machine.**

---

#### 1️⃣ Phishing

- Fake emails/websites that look legit.
- Example: “Your bank account is locked, click here to reset.”
- Subtypes: Spear phishing , Whaling , Vishing (voice), Smishing (SMS).

---

🔎 **Subtypes of Phishing**

Phishing is like an umbrella, and these are the flavors:

1️⃣ **Spear Phishing 🎯** (*targeted*)

- Targeted, not random.
- Attacker researches *you* specifically (your name, workplace, hobbies).
- Example: “Hey Dipsana, here’s your GitHub PR report” → but it’s a trap link.

2️⃣ **Whaling 🐋** (*big shots*)

- Big fish only — CEOs, CFOs, directors, higher level executives.
- Attackers mimic business emails.
- Example: Fake “CEO request” asking finance to wire funds to an account.

3️⃣ **Vishing 📞** (*Voice Phishing*)

- Done via phone calls.
- Example: “Hello, this is your bank. Please confirm your OTP.”
- Popular with fake “customer care” scams.

4️⃣ **Smishing 💬** (*SMS Phishing*)

- Text message attacks.
- Example: “Your package is delayed, click here to reschedule” → malicious link.

---

⚡ **Quick Mnemonic for these: “SVWS – Some Very Wicked Scams”**

- **S**mishing
- **V**ishing
- **W**haling
- **S**pear phishing

---

#### 5️⃣ Pretexting

- Creating a **fake scenario/story** to trick you.
- Example: Hacker pretends to be IT support asking for your login.

---

#### 6️⃣ Baiting

- Offering something tempting.
- Example: “Free movie download” → but it’s malware.
- Or a USB drive labeled *Salary Data 2025* left in the office.

---

#### 7️⃣ Tailgating / Piggybacking

- Physically following someone into a restricted area.
- Example: Hacker waits at the door, says “Hey, I forgot my ID, can you hold the door?”

---

#### 8️⃣ Quid Pro Quo

- Exchange of favors.
- Example: “I’ll fix your printer if you give me your login.”

---

#### 9️⃣ Impersonation

- Hacker pretends to be someone with authority.
- Example: Acting as CEO and emailing the finance team to release funds.

---

⚡ **Mnemonic:**
**PPT BQI** (like a “PowerPoint BQI file”)

- **P**retexting
- **P**iggybacking/**T**ailgating
- **B**aiting
- **Q**uid Pro Quo
- **I**mpersonation

---

### 12. 🔒 Insider Attacks

Think of insiders as *wolves in sheep’s clothing* — they’re already inside the castle, so they don’t need to “hack in.”

#### Types of Insider Threats

1. **Malicious Insider 🐺**

   - Has intent to harm.
   - Example: Disgruntled employee stealing customer data to sell.

2. **Negligent Insider 😬**

   - No bad intent, just careless.
   - Example: Employee clicking on phishing links, weak passwords, misplacing laptops.

3. **Compromised Insider 🎭**

   - Legit account but taken over by an outsider.
   - Example: Attacker steals credentials via phishing → now has “legit employee” access.

---

#### 🚨 Why Insider Attacks Are Dangerous

- They bypass perimeter defenses (firewalls, IDS/IPS).
- Insiders often have privileged access to sensitive data.
- Very hard to detect — looks like “normal” activity.

---

#### ⚔️ Prevention Strategies

- **Principle of Least Privilege (PoLP)** → give only the access they need, nothing more.
- **Monitoring & Logging** → track unusual access patterns.
- **Strong IAM (Identity & Access Management)** → enforce MFA, regular password resets.
- **Employee Training** → many attacks succeed because of negligence.
- **Exit Policies** → revoke access immediately when someone leaves the org.

---

⚡ Mnemonic: **“I.N.C”** or **“M.N.C”** → Types of insiders

- **I** → Intentional (**M** → Malicious)
- **N** → Negligent
- **C** → Compromised

---

#### 🕵️‍♀️ Insider Threats — Analogy

💡 Think type of insiders as human traits  Good, Evil and Lazy:

- **Lazy 😴 (Negligent)** → careless, clicks shady links, weak passwords.
- **Good 😇 (Compromised)** → account stolen, attacker uses it as a mask.
- **Evil 😈 (Malicious)** → deliberate sabotage, stealing, selling data.

---

### 13. 🛡 Preventing Insider Threats

Think of it like **“The 4D Shield”**:

1. **Deny Excess Access 🔐**

   - Principle of Least Privilege (only what’s needed).
   - Role-based access control.

2. **Detect Odd Behavior 👀**

   - Log monitoring (sudden downloads, odd working hours).
   - AI/UEBA (User & Entity Behavior Analytics) for patterns.

3. **Defend with Policies 📜**

   - Security awareness training.
   - Regular audits, password hygiene.
   - Immediate access revocation (the official cancellation of a decree, decision, or promise) on exit.

4. **Double-Check Identity 🔑**

   - MFA, strong authentication.
   - Zero-trust model (“never trust, always verify”).

💡 **Mnemonic: ABP India** *→ **A**ccess, **B**ehavior, **P**olicies, **I**dentity.***

---

### 14. 🎯 Social Engineering Targets

Hackers focus on the weakest link = **Humans** 🧑‍🤝‍🧑

- **New Employees** → don’t know policies yet.
- **Finance/HR Staff** → they have sensitive personal & financial data.
- **IT/Admins** → god-level privileges, jackpot target.
- **Executives (Whaling)** → busy people, more likely to approve quickly.

In a nutshell, types of people that works in a company: newbie 👶, finance (salary)💰, bosses 👩‍💼, technical IT guys 🧑‍💻.

---

### 15. 🛡 Defense Strategies Against SE

- **Awareness Training** → recognize phishing, vishing, smishing.
- **Verification Culture** → “trust but verify” (call back, double-check requests).
- **Simulated Attacks** → companies run fake phishing tests to train staff.
- **Strong Policies** → no sensitive info shared over mail/phone.
- **Incident Reporting** → encourage reporting suspicious messages (no shame in asking!).

#### Mnemonics for **Defence Strategies** (Pick any one and learn it)

- Mnemonic 1: **AVSSI**
  - **A**wareness
  - **V**erification
  - **S**imulations
  - **S**trong policies
  - **I**ncident reporting

- Mnemonic 2: **VCAT PAIR 🐱**

  - **V**erification **C**ulture
  - **A**wareness
  - **T**raining
  - **P**olicies
  - **A**ttacks
  - **I**ncident **R**eporting.

- Bonus: **A TSP in CAR 🚗** *→ **A**wareness **T**raining, **S**ecurity **P**olicies, **C**ulture, **A**wareness, **R**eporting.*

---

### 🛡️ 16. OWASP Top 10

**What it is:**
The **OWASP Top 10** is a standard awareness document for developers and web application security. It represents a broad consensus (agreement) about the **most critical security risks to web applications**. Think of it as a "Most Wanted" list for web vulnerabilities.

It's created by the **Open Web Application Security Project (OWASP)**, a non-profit foundation that works to improve software security.

**Why it's a BIG deal:**
If you are working with web apps (which everyone is), you *must* know these. They are the most common ways web apps get hacked. It's updated every few years; the current list is from **2021**.

#### The OWASP Top 10 2021 List

Here are the ten categories. You don't need to be an expert on each, but you should know what they are.

1. **A01:2021-Broken Access Control**
    - **What it is:** Users can access data or functions they aren't supposed to. E.g., by changing a URL parameter from `userid=123` to `userid=124` to see another user's data.
    - **Simple Fix:** Always check permissions on every request.

2. **A02:2021-Cryptographic Failures**
    - **What it is:** This was previously called "Sensitive Data Exposure." It means failing to properly protect sensitive data (like passwords, credit card numbers) with encryption, both in transit and at rest.
    - **Simple Fix:** Use strong encryption (TLS for transit, AES for storage) and never store data you don't need.

3. **A03:2021-Injection**
    - **What it is:** Sending malicious data to an interpreter (like a database) that tricks it into executing unintended commands. **SQL Injection** is the most famous type.
    - **Simple Fix:** Use parameterized queries (don't just splice user input into a command string).

4. **A04:2021-Insecure Design**
    - **What it is:** This is new. It's about flaws in the application's architecture and design, not its code. It's building a house with a weak foundation.
    - **Simple Fix:** Incorporate threat modeling and secure design patterns from the very start.

5. **A05:2021-Security Misconfiguration**
    - **What it is:** Leaving default settings, open cloud storage, unused pages, or revealing error messages with too much information to attackers.
    - **Simple Fix:** Harden everything. Have a repeatable setup process for all environments.

6. **A06:2021-Vulnerable and Outdated Components**
    - **What it is:** Using libraries, frameworks, and other software components with known vulnerabilities (e.g., an old version of WordPress with a known bug).
    - **Simple Fix:** Regularly scan and update your dependencies.

7. **A07:2021-Identification and Authentication Failures**
    - **What it is:** Problems with login functions. E.g., allowing weak passwords, not having multi-factor authentication (MFA), or letting attackers brute-force their way in.
    - **Simple Fix:** Implement strong MFA and strong password policies.

8. **A08:2021-Software and Data Integrity Failures**
    - **What it is:** trusting software updates from untrusted sources without verifying their integrity. The SolarWinds attack is a perfect example.
    - **Simple Fix:** Use digital signatures to verify the integrity of software and data.

9. **A09:2021-Security Logging and Monitoring Failures**
    - **What it is:** Not having good logs or not monitoring them. If you don't log attacks, you can't detect them or know what happened after a breach.
    - **Simple Fix:** Ensure all login, access control, and server-side input validation failures are logged and monitored.

10. **A10:2021-Server-Side Request Forgery (SSRF)**
    - **What it is:** Tricking a server into making requests to an internal or third-party system that it shouldn't be able to access. It's like using a trusted employee to sneak into a restricted area.
    - **Simple Fix:** Sanitize and validate all user input, especially URLs.

**Exam Tips:**

1. Don't worry if you're struggling to memorize them. Don't memorize the exact words. Memorize the important ones: **Injection**, **Broken Access Control**, and **Cryptographic Failures**.

2. Now if you want to memorize more you can create mind maps. Let's recall **Information Assurance (IA)** where we studied **NRACIA**. You can see few topics linked to it i.e. **Identification and Authentication Failures** and **Software and Data Integrity Failures**.

3. **Forgery** is a crime we are daily aware of. Illegal foreign immigrants from other countries forcefully penetrate the border and create fake passports and identity cards. You can see **Server Side Request Forgery** linked to it.

4. Everyone starts to fall behind with an old mindset. We must keep ourselves upto date with the real world. Similary **components can become outdated and vulnerable**.

5. Last is **Sequrity Misconfiguration** and **Insecure Design**, think of **IDS/IPS** and **Software Engineering**.

There you go my studious friend. Ace your exams 💪.

---

## Unit 4 — Cyber Forensics & Auditing

### 1) Introduction to Cyber Forensics

**What it is:**
The scientific process of **identifying, preserving, collecting, examining, analyzing, and presenting** digital evidence so it’s **legally admissible**.

💡 *Just get an overview, even if you forget goals & principles you can make it up by using the mnemonic.*

**Remember the mnemonic?**  
*Ident preserves CD collections while examine analyzes presentations*

🎯 **Goals (mnemonic: P.I.E.R.)**

- **P**reserve evidence (no alteration)
- **I**dentify relevant sources
- **E**xtract/examine artifacts
- **R**eport clearly & credibly

🎯 **Core principles (mnemonic: C.A.R.E.)**

- **C**hain of custody (who handled what, when)
- **A**uthenticity (prove evidence is genuine → hashes)
- **R**epeatability (another expert can reproduce)
- **E**vidence integrity (use write-blockers, imaging)

**Major branches:** computer, **memory (RAM)**, **network**, **mobile**, **cloud**, **malware** forensics.

---

### 2) Computer Equipment & Associated Storage Media

#### 🔹 Where evidence lives

- **Endpoints:** desktops, laptops, servers, VMs.
- **Removable:** USB, SD/microSD, external HDD/SSD, optical discs(CDs & DVDs).
- **Internal storage:** HDD/SSD/NVMe (note: **SSD TRIM** can wipe deleted data blocks).
- **Enterprise (business companies):** RAID, NAS/SAN.
- **Cloud:** Drive/OneDrive/S3, SaaS logs.
- **Mobile/IoT:** phones, wearables, cameras, routers.

**Elaborations:**

1. **RAID is a low-level technology** that operates at the **disk level**, while **NAS and SAN are high-level technologies** that operate at the **network level**. RAID can improve the performance and reliability of a single device or server, while NAS and SAN can improve the performance and reliability of multiple devices or servers.

2. **Software as a service (SaaS) is a way of delivering software over the internet.** Instead of installing and maintaining software on your computer, you access it online through a subscription with a cloud service provider.

---

#### 🔹 File Systems

✨ **The Core Concept: The Librarian's Rulebook**

Imagine a massive library (your hard drive).

- The **books** are your files (photos, documents, etc.).
- The **file system** is the librarian's rulebook. It dictates:
  - How books are placed on shelves (how data is written to the disk).
  - How to find a specific book quickly (how data is read).
  - How to keep a list of all books and their locations (the "table of contents").
  - How much information can be written in one book's index card (file size limits).
  - How big the shelves can be (volume size limits).

Now, let's meet the different librarians and their rulebooks.

---

#### 1. NTFS (New Technology File System)

✨ **The Modern, Strict Librarian (Windows' Standard)**

- **Primary Use:** The default system for internal hard drives on modern Windows computers.
- **Key Features:**
  - **Large File Support:** Can handle individual files larger than 4GB (e.g., DVD ISOs, HD movies).
  - **Large Drive Support:** Can handle massive hard drives (theoretically up to 16 Exabytes).
  - **Security & Permissions:** Supports file-level encryption (EFS) and detailed user permissions (e.g., "User A can read this file, but User B cannot").
  - **Journaling:** Keeps a "journal" of changes. If the computer crashes, the librarian can check the journal to fix errors and prevent data corruption. This is very reliable.
- **Forensic Importance:** A goldmine. The journal, permission changes, and detailed metadata can provide a timeline of user activity. Its **Master File Table ($MFT)** is a central database of every file on the drive, including "deleted" entries.

#### 2. FAT32 (File Allocation Table 32)

✨ **The Old, Simple, Universal Librarian**

- **Primary Use:** USB flash drives, SD cards, and older versions of Windows (95, 98).
- **Key Features:**
  - **Maximum Compatibility:** Works with *everything*—Windows, macOS, Linux, game consoles, smart TVs, car stereos. This is its biggest strength.
  - **Limitations:** **Cannot handle files larger than 4GB.** Cannot create partitions larger than 8TB. No built-in security or permissions.
- **Forensic Importance:** Often found on removable media. Its simplicity means less metadata is stored, but its widespread use makes it very common in investigations.

#### 3. exFAT (Extended File Allocation Table)

✨ **The Modern, Simple, Universal Librarian**

- **Primary Use:** Designed to be the modern replacement for FAT32 on **large-capacity USB drives and SD cards** (especially those 64GB and larger).
- **Key Features:**
  - **Best of Both Worlds:** Like FAT32, it maintains wide compatibility across operating systems. Like NTFS, it **removes the 4GB file size limit** and supports huge drives.
  - **Lightweight:** It doesn't have the advanced features (journaling, permissions) of NTFS, which makes it faster for simple read/write tasks on removable devices.
- **Forensic Importance:** As common as FAT32 now for external storage. It stores more metadata than FAT32 but less than NTFS.

#### 4. ext4 (Fourth Extended Filesystem)

✨ **The Powerful, Open-Source Librarian (Linux's Standard)**

- **Primary Use:** The default file system for most Linux distributions.
- **Key Features:**
  - **Journaling:** Like NTFS, it uses journaling for reliability.
  - **Excellent Performance:** Highly efficient for handling large numbers of small files (like system files) and avoids fragmentation better than NTFS.
  - **Flexibility:** Supports massive file and volume sizes.
- **Forensic Importance:** Crucial for investigating Linux-based systems, servers, and Android devices. Linux's "everything is a file" philosophy means a lot of system activity is logged in files on this system.

#### 5. APFS (Apple File System)

✨ **The Sleek, Modern, Optimized Librarian (macOS & iOS)**

- **Primary Use:** The default file system for all modern Apple products (macOS, iOS, iPadOS, watchOS).
- **Key Features:**
  - **Optimized for SSDs:** Designed for speed and efficiency on solid-state drives (SSDs), which are used in all modern Apple devices.
  - **Space Sharing:** Multiple volumes (e.g., your main drive and Time Machine backup) can share space on the same physical drive seamlessly.
  - **Clones:** Can create file "clones" instantly, without taking up extra space. This is key to how Time Machine works.
  - **Strong Encryption:** Built-in support for full-disk and single-file encryption.
- **Forensic Importance:** A complex but critical system for any Apple-related investigation. Understanding its cloning, space-sharing, and encryption features is essential to finding and recovering evidence.

#### 👉 Why This Matters for Forensics

A forensic analyst must know these rulebooks because **each one hides evidence in different places:**

- **NTFS:** Evidence is in the **$MFT**, journal, and permission logs.
- **FAT32/exFAT:** Evidence is more limited; focus is on file slack space and unallocated clusters.
- **APFS:** Evidence could be in **file clones** or snapshots.
- **ext4:** Evidence is in the **journal** and **inode** structures.

Using the wrong tool to image a drive or not understanding its structure could corrupt data or miss critical evidence. The file system is the map, and the investigator needs to know how to read it.

---

#### 🔹 Artifact Goldmines (Windows examples)

These are **clues left behind** on a computer:

- **Event Logs** → record of system activity.
- **Registry** → stores config & usage history.
- **Prefetch** → tells which programs ran recently.
- **Recent Files, Recycle Bin** → obvious evidence.
- **Browser history/cookies** → websites visited.
- **Pagefile/hibernation** → may contain chat fragments, passwords.
- **USB history, Jump lists** → external devices plugged in, files opened.

---

#### 🔹 Acquisition (collecting data)

- **Dead acquisition** → power OFF, take a copy of the hard drive.
- **Live acquisition** → while ON, grab **RAM**, volatile info, maybe encryption keys.

---

#### 🔹 Integrity

Evidence must remain **untouched**:

- Use **write-blockers** (prevents modifying drive).
- Save in formats like **RAW, E01, AFF**.
- Verify with **hashes (MD5, SHA-256)** → if the hash matches, no tampering.

---

#### 🔹 Challenges

- **Full-disk encryption** (BitLocker, FileVault) → need keys or live capture.
- **SSDs (TRIM)** → data erased more aggressively.
- **Cloud storage** → proprietary formats, hard to access.
- **Mobiles** → locked/encrypted, proprietary OS.

---

### 3. Role of Forensics Investigator

A **forensic investigator** is like a digital detective. Their role is not just finding evidence, but making sure it’s **valid in court**. Key responsibilities:

1. **Identification**

   - Spot potential sources of evidence (computers, USBs, logs, cloud, etc.).

2. **Preservation**

   - Ensure no tampering. Use **write blockers, hashes**.

3. **Collection**

   - Acquire the evidence properly (imaging drives, copying logs, seizing devices).

4. **Examination**

   - Dig deep into files, recover deleted data, analyze logs.

5. **Analysis**

   - Make sense of what’s found — linking user activity, timeline reconstruction.

6. **Presentation**

   - Prepare reports, present in **simple and clear terms** for non-technical people (judges, lawyers).

7. **Maintain Chain of Custody**

   - Every transfer of evidence must be documented (who handled it, when, where).

---

💡 **In short**:
The investigator’s job = **Find → Preserve → Analyze → Report** while keeping it legally valid.

**Remember the GOLD mnemonic?**
"*Ident preserves CD collections while examine analyzes presentations*" ;)

---

### 4. Forensics Investigation Process

Think of this as the **step-by-step workflow** investigators follow (very structured, like a recipe).

### 🔑 **Phases**

1. **Identification**

   - Spot where evidence may exist (laptop, phone, email logs, cloud storage).
   - Example: noticing suspicious login records.

2. **Preservation**

   - Prevent data loss or tampering.
   - Tools: **write blockers, imaging software**, sealing devices.
   - Calculate **hash values (MD5/SHA1)** to prove integrity.

3. **Collection**

   - Acquire evidence in a legally sound way.
   - Make **bit-by-bit copies** instead of touching originals.
   - Record everything in **chain of custody forms**.

4. **Examination**

   - Extract useful data → look for hidden, deleted, or encrypted files.
   - Use forensic tools (EnCase, FTK, Autopsy).

5. **Analysis**

   - Correlate data: timelines, IP addresses, communication patterns.
   - Build the story → *what happened, when, how, and who did it*.

6. **Presentation**

   - Create a clear **forensic report** (non-technical language).
   - Must be **understandable to judges, jury, auditors**.

---

**Remember the GOLD mnemonic?**
"*Ident preserves CD collections while examine analyzes presentations*" ;)

---

### 5. Collecting Network-Based Evidence

Unlike pulling files from a hard drive, this is about grabbing data **while it’s flying around in the network**.

#### 🔑 Key Evidence Sources

- **Firewall logs** – blocked/allowed traffic.
- **IDS/IPS alerts** – intrusion attempts.
- **Router & switch logs** – IP addresses, packet details.
- **Email headers** – sender/receiver trace.
- **Web server logs** – requests, suspicious URLs.
- **VoIP / chat transcripts** – in cyber harassment or fraud cases.

#### ⚡ Challenges

- Data is **volatile** (packets disappear in milliseconds).
- **Encryption (HTTPS, VPNs)** hides content.
- Need **real-time capture tools** (e.g., Wireshark, tcpdump).

#### 🛠️ Best Practices

1. Use **packet sniffers** (Wireshark, tcpdump).
2. Capture in **PCAP format** (forensic standard). **PCAP = Packet CAPture** (standard format for storing captured network traffic).
3. Sync all systems with **NTP (Network Time Protocol)** → timestamps match.
4. Record **hash values** of captured files.
5. Ensure chain of custody → logs about who collected what, when, and how.

📌 **Mini Trick**: *“Logs + Packets + Time = Strong Network Evidence”*

Exactly 👍 — **PCAP = Packet CAPture** (standard format for storing captured network traffic).

---

### 6. Writing Computer Forensics Reports

This is where all the hard technical work gets translated into something a **judge, manager, or non-tech stakeholder** can actually understand.

#### 🔑 Goals of the Report

- Be **clear** (no unnecessary jargon).
- Be **factual & objective** (no assumptions).
- Be **legally sound** (can hold up in court).

#### 📑 Typical Report Structure

1. **Introduction**
   - Case ID, investigator name, date, scope of investigation.

2. **Objectives**
   - Why was the investigation conducted?
   - Example: “To determine whether unauthorized access occurred.”

3. **Methodology**
   - Tools and techniques used (e.g., EnCase, Wireshark, Autopsy).
   - Mention adherence to standards (ISO, NIST).

4. **Findings**
   - Facts only. Example: *“Log analysis revealed 5 failed login attempts from IP 192.168.1.5 at 02:10 AM.”*
   - Include screenshots, hashes, tables.

5. **Analysis**
   - Interpret findings in context.
   - Example: *“The repeated failed logins suggest a brute-force attack attempt.”*

6. **Conclusion**
   - Final summary of what the evidence supports.

7. **Recommendations**
   - E.g., patch systems, stronger passwords, monitoring.

8. **Appendices**
   - Raw logs, extra screenshots, hash values.

#### ✨ Best Practices (Mnemonic: **C-FACED**)

- **C**lear
- **F**actual
- **A**ccurate
- **C**oncise
- **E**asy-to-read
- **D**efensible in court

---

### 7. Auditing

#### 🔎 What is Auditing in Cybersecurity?

Auditing = A **systematic, independent examination** of systems, applications, processes, and policies to check whether they comply with security standards and work as intended.

Think of it like: *“An investigator for prevention, not just detection.”*

**Bada se chota ja raha haa**, scope is decreasing → `System (parent)` → `processes (bacche)` → `policies(concepts → anewale bacche)`.
You liked it don't you 🤣?!

#### 🛠️ Types of Audits

- **Internal Audit** → Done by the organization itself (self-check).
- **External Audit** → Performed by third parties (objective assessment).
- **Compliance Audit** → Checks against standards/regulations (e.g., ISO 27001, PCI DSS).
- **Operational Audit** → Checks efficiency and effectiveness of security operations.
- **Technical Audit** → Focuses on system configurations, access logs, vulnerabilities.

💡 **Mnemonic: ROTIE**
**R** → Rules aka Compliance
**O** → Operational
**T** → Technical
**I** → Internal
**E** → External

#### 🎯 Audit Objectives

- Ensure **confidentiality, integrity, availability (CIA)**.
- Check **policy compliance**.
- Detect **anomalies / misuse / insider threats**.
- Verify **effectiveness of controls**.

💡 **Mnemonic: CIA, EC PC, MIA**
**CIA** → Confidentiality, Itegrity, Availability
**EC PC** → Effectiveness Control, Policies Compliance
**MIA** → Misuse, Insider Threats, Anomalies

#### 📝 Audit Checklist (Mnemonic: SCARF)

- **S**tandards compliance (ISO, NIST, PCI, GDPR, etc.)
- **C**ontrols check (access, firewall, encryption, logging)
- **A**ccuracy of records (logs, backups, evidence)
- **R**isk identification (weaknesses, threats)
- **F**ollow-ups (are issues fixed after past audits?)

---

### 8. Planning an Audit Against a Set of Audit Criteria

Audit planning = the **blueprint** 📝 before actually auditing.

#### 🛠️ Steps in Planning (Mnemonic: SCOPE + CROPS)

1. **S**et audit **O**bjectives → What do we want to check? (compliance, risks, efficiency)
2. **C**hoose **C**riteria → ISO 27001, NIST, PCI DSS, org policies, laws.
3. **O**rganize **S**cope → Systems, apps, departments, time period.
4. **P**repare **R**esources → Assign auditors, schedule interviews, tools.
5. **E**xecute **P**lan → Timelines, deliverables, reporting method.

#### 🎯 Why plan?

- Avoids missing critical areas.
- Ensures objectivity (no bias).
- Keeps audit efficient & cost-effective.
- Provides clear path for evidence collection.

Perfect! 👌 You nailed the **definition + scope flow** idea 💡 (big → small, parent → child). Also your "Set, Choose, Organize, Prepare, Execute" is already clean enough — don’t stress on the micro details; just remember it’s the **audit roadmap**.

---

### 9. Information Security Management System (ISMS)

Think of ISMS as the **skeleton of an organization’s security** 🦴 — policies, procedures, controls, and processes working together to keep info safe.

**Don't confuse it with EISA!**
EISA is the architecture, this is the management.

#### 🔑 Core Elements (Mnemonic: Plan Do Check Act)

1. **Plan** → Define security objectives, risks, controls (ISO 27001, NIST etc.).
2. **Do** → Implement security controls (access control, encryption, training).
3. **Check** → Monitor & audit (logs, SIEM, incident reports).
4. **Act** → Improve continuously (patching, policy updates, new controls).

#### 🎯 Objectives of ISMS

- Ensure **CIA triad** (Confidentiality, Integrity, Availability).
- Manage risks systematically.
- Ensure compliance with laws, standards (GDPR, ISO 27001).
- Build trust with stakeholders.

---

#### ISMS Audit Process

Think of it as a **security health check-up** 🩺 for the organization’s ISMS.

🪜 **Steps (Mnemonic: PEP-CAR 🚗)**

1. **P**lan → Define audit scope, objectives, criteria.
2. **E**valuate → Collect evidence (interviews, logs, configs).
3. **P**erform testing → Verify controls in action.
4. **C**ompare → Match findings vs ISO 27001 / policy requirements.
5. **A**nalyze → Identify gaps, risks, weaknesses.
6. **R**eport → Prepare clear, factual, actionable audit report (C-FACED 😉).

🌀 **Types of ISMS Audit**

- **Internal audit** → By org itself (self-check).
- **External audit** → By independent third-party.
- **Certification audit** → To get ISO 27001 compliance.

---

### 🔟 Introduction to ISO 27001:2013

👉 It’s an **international standard** for **Information Security Management Systems (ISMS)**.
Think of it as a **rulebook + framework** 📘 for securing information.

#### Purpose

- Helps organizations **protect confidentiality, integrity, and availability (CIA)** of data.
- Ensures **risk-based approach** to security.
- Builds **customer trust** and meets **compliance requirements**.

#### Key Clauses (Main Sections)

1. **Context of the Organization** – Understand internal & external issues.
2. **Leadership** – Management commitment, policies, responsibilities.
3. **Planning** – Risk assessment, risk treatment plan.
4. **Support** – Resources, awareness, communication, documentation.
5. **Operation** – Implement security controls.
6. **Performance Evaluation** – Monitoring, measurement, audits, reviews.
7. **Improvement** – Corrective actions, continual improvement.

💡 **Mnemonic: CLIPS OP**
**C** → Context of Organization
**L** → Leadership
**I** → Improvement
**P** → Performance Evaluation
**S** → Support
**O** → Operation
**P** → Planning

#### Annex A Controls (114 controls, 14 domains)

- Examples: Access Control, Cryptography, Physical Security, Supplier Relationships, Compliance.

---

### Unit 4 Mini-Quiz

1. What does ISO 27001:2013 primarily deal with?
   a) Software development lifecycle
   b) Information Security Management System
   c) Network troubleshooting

2. Which three pillars does ISO 27001 focus on?
   a) Efficiency, Productivity, Innovation
   b) Confidentiality, Integrity, Availability
   c) Policies, Controls, Awareness

3. Who conducts an **external audit** for ISO 27001 compliance?
   a) The internal IT team
   b) Independent third-party auditor
   c) End users

4. Which section of ISO 27001 talks about **management commitment**?
   a) Context of organization
   b) Leadership
   c) Improvement

5. How many controls are in **Annex A** of ISO 27001:2013?
   a) 114
   b) 99
   c) 14

#### 🔥 Solutions

1️⃣ **b) ISMS**  
2️⃣ **b) Confidentiality, Integrity, Availability** (CIA).  
3️⃣ **b) Independent third-party auditor**  
4️⃣ **b) Leadership**  
5️⃣ **a) 114**

---

## Unit 5 — Cyber Ethics and Laws

### 1. Introduction to Cyber Laws

- Cyber Law = **legal framework** that governs how technology, internet, and digital activities are used.

- Covers:
  - **Cybercrimes** (hacking, phishing, identity theft).
  - **Data protection & privacy**.
  - **Digital transactions** (validity of e-contracts, e-signatures).
  - **Regulation of e-commerce & e-governance**.

- In India → **IT Act, 2000** (amended in 2008) is the primary law.

---

### 2. E-Commerce and E-Governance

🔹 **E-Commerce (Electronic Commerce)**

- Buying & selling of goods/services online.
- Includes: Online banking, shopping, ticket booking, etc.
- Cyber law ensures:
  - **Legality of digital contracts** (Section 10A, IT Act).
  - **Authenticity of e-signatures & records**.
  - **Consumer protection & fraud prevention**.

🔹 **E-Governance (Electronic Governance)**

- Use of ICT (Information & Communication Tech) by govt. for public services.
- Examples: Adhaar, GST filing, DigiLocker, online bill payments.
- Cyber law ensures:
  - **Secure e-records** (Sections 4–7, IT Act).
  - **Accountability & transparency**.
  - **Digital signatures for govt. docs**.

---

### 3. Certifying Authority (CA) and Controller

🔹 **Certifying Authority (CA):**

- Licensed entity under IT Act 2000.
- Issues **Digital Certificates** for verifying identity in online transactions.
- Ensures authenticity, confidentiality & integrity of electronic records.
- Example: NIC, TCS-CA, e-Mudhra.

🔹 **Controller of Certifying Authorities (CCA):**

- Government authority regulating all CAs.
- Functions:

  - Grants licenses to CAs.
  - Monitors their activities.
  - Lays down rules for digital signatures & encryption.
  - Maintains the **Root Certifying Authority of India (RCAI)**.

**Analogy 🤭** — CCA is the **dad**, CA are the **kids**, and RCAI is like the **grandparent root** cert from which all trust begins!

---

### 4. Offences under IT Act 2000 🚨

Some key offences:

- **Unauthorized access** → hacking into systems without permission.
- **Identity theft** → misusing someone’s digital signature, password, or credentials.
- **Cyber fraud & cheating** → online scams, fake e-commerce.
- **Obscenity & pornography** → publishing or transmitting obscene content online.
- **Spreading viruses/worms** → knowingly introducing malicious software.
- **Denial of Service (DoS) attacks** → disrupting services intentionally.
- **Tampering with electronic records** → altering data without consent.

👉 Basically, anything that breaks confidentiality, integrity, authenticity, or law = **cyber offence**.

💡 **Tip:**
*IT Act 2000 (amended 2008) is the mother law of cyberspace in India* — like IPC (Indian Penal Code) but for the digital world. So even *if we're unable to recall every offense we can made up and add some new ones* like nudity in public places, fake news, stalking, etc.

---

### 5. 📊 Computer Offences & Penalties under IT Act, 2000 (Grouped by Theme)

| **Section**  | **Offence / Provision**                                 | **Penalty / Description**                                | **Theme** |
| :----------- | :------------------------------------------------------ | :------------------------------------------------------- | :-------- |
| **Sec. 43**  | Unauthorised access, data theft, virus introduction     | **Civil compensation** to affected person                | **Compensation / Fines** |
| **Sec. 43A** | Failure to protect sensitive personal data              | **Civil compensation** for negligence in implementing reasonable security practices. | **Compensation / Fines** |
| **Sec. 44**  | Failure to furnish information or comply with orders    | Penalty up to **₹1.5 lakh**                              | **Compensation / Fines** |
| **Sec. 65**  | Tampering with computer source documents                | Imprisonment up to **3 years** or fine up to **₹2 lakh** | **3-Year Gang (Dishonesty)** |
| **Sec. 66**  | Computer-related offences (dishonest/fraudulent intent) | Imprisonment up to **3 years** or fine up to **₹5 lakh** | **3-Year Gang (Dishonesty)** |
| **Sec. 66B** | Receiving stolen computer or communication device       | Imprisonment up to **3 years** + fine up to **₹1 lakh**  | **3-Year Gang (Dishonesty)** |
| **Sec. 66C** | Identity theft                                          | Imprisonment up to **3 years** + fine up to **₹1 lakh**  | **3-Year Gang (Dishonesty)** |
| **Sec. 66D** | Cheating by personation using computer resource         | Imprisonment up to **3 years** + fine up to **₹1 lakh**  | **3-Year Gang (Dishonesty)** |
| **Sec. 72A** | Disclosure of information in breach of lawful contract  | Imprisonment up to **3 years** or fine up to **₹5 lakh** | **3-Year Gang (Dishonesty)** |
| **Sec. 66E** | Violation of privacy                                    | Imprisonment up to **3 years** or fine up to **₹2 lakh** | *(Privacy - Fits 3-Year theme)* |
| **Sec. 67**  | Publishing obscene material in electronic form          | First offence: **Up to 3 years** + fine **₹5 lakh**<br>Subsequent: **Up to 5 years** + fine **₹10 lakh** | **5-Year Club (Obscenity)** |
| **Sec. 67A** | Publishing sexually explicit act                        | Up to **5 years** + fine up to **₹10 lakh**              | **5-Year Club (Obscenity)** |
| **Sec. 67B** | Child pornography                                       | Up to **5 years** + fine up to **₹10 lakh**              | **5-Year Club (Obscenity)** |
| **Sec. 66F** | Cyber terrorism                                         | Imprisonment up to **life**                              | **Life (Terrorism)** |
| **Sec. 69**  | Failure to assist in decryption/interception            | Imprisonment up to **7 years** + fine                    | **7-10 Years (vs. Govt)** |
| **Sec. 70**  | Protected system — unauthorized access                  | Imprisonment up to **10 years** + fine                   | **7-10 Years (vs. Govt)** |
| **Sec. 72**  | Breach of confidentiality and privacy                   | Imprisonment up to **2 years** or fine up to **₹1 lakh** | **2-Year Twins** |
| **Sec. 73**  | Publishing false Digital Signature Certificate          | Imprisonment up to **2 years** or fine up to **₹1 lakh** | **2-Year Twins** |
| **Sec. 74**  | Publication for fraudulent purpose                      | Imprisonment up to **2 years** or fine up to **₹1 lakh** | **2-Year Twins** |
| **Sec. 75**  | Act applicable to offence committed outside India       | Extraterritorial jurisdiction — if involves Indian computer or network | **(Misc - Jurisdiction)** |
| **Sec. 76**  | Confiscation of computer, devices, etc.                 | Equipment used in cyber crime can be confiscated         | **(Misc - Penalty)** |

#### ✅ Theme — Memory Sheet

Try to remember as many as you can and write it several times on a notebook. If you want to remember all of them you'll have to do it the hard way but I can help you a bit by creating memory maps for you.

| Punishment / Theme           | Sections                       | Memory Hook                               |
| :--------------------------- | :----------------------------- | :---------------------------------------- |
| **3-Year Gang** (Dishonesty) | **65, 66, 66B, 66C, 66D, 72A** | **"66 = Dishonest Digital Deeds"**        |
| **5-Year Club** (Obscenity)  | **67, 67A, 67B**               | **"67 = Naughty Stuff"**                  |
| **Life** (Terrorism)         | **66F**                        | **"F for Fear"**                          |
| **7-10 Years** (vs. Govt)    | **69, 70**                     | **"Don't fight the GOV"**                 |
| **Compensation / Fines**     | **43, 43A, 44**                | **"The 40s are about money"**             |
| **2-Year Twins**             | **72, 73, 74**                 | **"The 70s twins for privacy and fraud"** |

---

### 6. ⚖️ IT Act, Section 43A (Data Breach Liability)

**What it is:**
**Section 43A of the IT Act, 2000** is a crucial rule that holds companies accountable if they are negligent with your sensitive personal data.

**In Simple Terms:**
If a company (called a **"body corporate"** in the law) is storing your sensitive data (like passwords, financial info, health records) and fails to maintain **"reasonable security practices and procedures"** to protect it, they can be sued.

**What happens if they fail?**
If a data breach occurs because of their negligence, the company must pay **compensation** (financial damages) to the person whose data was affected.

**Why it's important:**

- This was India's first major step towards recognizing the **right to data privacy**.
- It makes businesses legally responsible for protecting the data they collect.
- It's the legal basis you can use to sue a company that leaks your data.

**Example:**
If a shopping website's database gets hacked because they stored passwords in plain text (instead of encrypting them), and your credit card info is stolen, you can claim compensation under Section 43A for their negligence.

---

### 7. 📚 Intellectual Property Rights (IPR) in Cyberspace

- **What it means**: Protecting creations of the mind in the digital world.
- Examples:

  - **Copyrights** → software code, music, e-books.
  - **Patents** → unique algorithms, hardware designs.
  - **Trademarks** → domain names, logos.
  - **Trade secrets** → source code, business models.

In cyberspace, risks are higher: piracy, plagiarism, counterfeit software, domain squatting. That’s why **WIPO + IT Act + Indian Copyright Act** apply.

#### 💡 Key words

- **Plagiarism** → Stealing someone’s work/ideas and pretending it’s yours.
  👉 e.g., Copy-pasting code or blog without credit.
- **Counterfeit software** → Fake / pirated versions of paid software.
  👉 e.g., Cracked MS Office or Photoshop.

#### 🏛 WIPO

**World Intellectual Property Organization** → UN agency that sets global rules for IPR (so creators’ rights are protected across countries).

#### 🪙 Indian Copyright Act

Law in India that protects creators of music, films, books, software, etc. Works hand-in-hand with IT Act to fight piracy online.

> ✅ So IPR in cyberspace = protecting **content, inventions, brand identity, and secrets** from piracy, plagiarism, fake software, or misuse online.

---

### 8. Cyber Ethics at Network Layer — IPSec

- **IPSec (Internet Protocol Security)** = a protocol suite for secure communication over IP networks.
- Works at **Network Layer** → secures data as it travels.

- Provides **CIA** (the big 3 you learned):
  - **Confidentiality** → encrypts packets.
  - **Integrity** → ensures no tampering.
  - **Authentication** → confirms sender identity.

- Two modes:
  - **Transport Mode** → encrypts just the message/data.
  - **Tunnel Mode** → encrypts whole packet (used in VPNs).
- Ethics angle → Using IPSec means you respect privacy, ensure secure transactions, prevent eavesdropping/hacking. Not using it → unethical, risky.

😂 **Fun Analogies**

🌀 Ever wondered why we always see "Entering Proton Tunnel" message infinite number of times?
That’s Proton VPN just putting our data in a secret encrypted tube so no one peeks 👀(not even your ex).

😏 DNS Adguard - I know what you do 😂
In our phones we have three modes of **DNS: off, auto and custom**. That **Auto DNS mode is our transport layer** where our **IPSec bodyguards** inform others by whispering into each other's ears👂🔒. I wonder how they maintain the integrity of the data. Tough job… but someone’s gotta do it. 🫠

---

### 📘 9. Personal Data Protection Bill (PDPB) / Act

**What it is:**
The **PDPB** is a proposed comprehensive law that aims to be India's version of the EU's famous **GDPR (General Data Protection Regulation)**. It's a much more detailed and powerful extension of the idea behind Section 43A.

**Its Core Principles (The Big Ideas):**

1. **Consent:** Companies must take your clear, free consent before collecting or using your personal data. They can't hide it in long terms & conditions.
2. **Purpose Limitation:** They can only use your data for the specific purpose they told you about. They can't collect it for one reason and use it for another.
3. **Right to be Forgotten:** You have the right to ask a company to delete your personal data.
4. **Data Localization:** Critical personal data must be stored on servers within India.
5. **Data Protection Authority:** The bill proposes creating a powerful regulatory body to enforce these rules and punish violations.

**Status:** It has been passed as the **Digital Personal Data Protection (DPDP) Act, 2023**. This is the law now, making it even more critical to understand.

**Why it's a BIG deal:**
It fundamentally shifts power back to the individual. It gives you control over your own data and imposes heavy penalties on companies that misuse it.

---

### 10. 🌐 How governments block websites

In India (and most countries), blocking happens at the **ISP (Internet Service Provider)** level:

1. **DNS Filtering** → ISPs configure their DNS servers to not resolve banned domains. (So adult websites → won’t give you an IP).
2. **IP Blocking** → They blacklist certain IP ranges so requests never reach the server.
3. **Deep Packet Inspection (DPI)** → Advanced filtering → looks inside traffic to block based on content/keywords.

👉 VPNs bypass this by creating an **encrypted tunnel**, so ISPs can’t see *what* you’re accessing. They only see encrypted traffic going to a VPN server.

That’s why the sites may be “banned,” but enforcement is imperfect, and individuals aren’t usually arrested for bypassing unless they engage in **illegal distribution** (like running servers, selling access, etc.).

---

### 🧩 Unit 5 Recap (memory map)

1. **Cyber Security Goals** → CIA (Confidentiality, Integrity, Availability).
2. **Security Threats** → Unauthorized access, malware, DoS, data theft.
3. **Cyber Crime & IT Act 2000 (amended 2008)** → defines offences & penalties.
4. **IPR in Cyberspace** → Copyright, Patent, Trademark, Trade Secrets.
5. **Organizations** → WIPO, Indian Copyright Act.
6. **Cyber Ethics** → Responsible online behavior.
7. **Network Layer Ethics – IPSec** → Encrypts data, CIA, Tunnel vs Transport.

---

### ⚡ Unit 5 - Quick Quiz

1. IPSec provides which three core security services?
2. Which mode of IPSec is commonly used in VPNs?
3. What does WIPO stand for?
4. Name **two examples** of Intellectual Property Rights.
5. Under IT Act 2000, publishing obscene content online can lead to how many years of jail (approx)?

#### ✅ Solutions

1. CIA
2. Tunnel Mode
3. World Intellectual Property Organization
4. IPR:
   - **Copyright** → ensures no piracy of videos, audios, basically anti torrent and his son telegram 😉.
   - **Patent** → protects *inventions/innovations* (like a new algorithm, device, or chemical formula).
   - **Trademark** → logos, brand names, domains.
   - **Trade Secret** → protects *confidential business info* (source code, recipes, business strategies). Example: Coca-Cola’s formula.

5. Upto 5 years.

✨ Funny mnemonic for IPRs (C-P-T-T): **“Cool Programmers Teach Tech”**

- **Cool** → Copyright
- **Programmers** → Patent
- **Teach** → Trademark
- **Tech** → Trade Secret
