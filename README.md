# Passive Web Application Security Audit Ledger: testphp.vulnweb.com

## 📋 Assessment Overview
This repository contains the professional engineering logs, assessment data mappings, and executive delivery summaries compiled during the passive, read-only security configuration review of the platform space `http://testphp.vulnweb.com`. 

* **Audit Registry Reference:** Project 001
* **Compliance Standards Alignment:** NIST SP 800-115 Information Security Assessment Framework
* **Strategic Repository Link:** https://github.com/bondidhanush01-bit/-FUTURE_CS_01.git
* **Canva Executive Document:** [/report/Vulnerability_Assessment_Report.pdf](./report/Vulnerability_Assessment_Report.pdf)

---

## 🚫 Audit Safety & Scope Restraints
In complete alignment with standard safety auditing protocols, the following high-risk, intrusive assessment operations were **explicitly excluded and prohibited** throughout the lifecycle of this project:
* **No Exploitation:** No active code injections, database modifications, or account bypasses were initiated.
* **No Authentication Flooding:** Automated password guessing or application brute-force mechanisms were strictly bypassed to ensure service stability.
* **No Service Disruption (DoS):** High-volume resource validation testing was avoided to maintain 100% platform up-time.

---

## 📂 Passive Evidence Records & Verification Data

The underlying system configurations and structural gaps found can be verified through the static, read-only data assets retained inside the `/evidence` directory:

### 1. Plaintext Data Exposure Files
* **Evidence Asset:** `[evidence/credentials_leak.png]`
* **Context:** Documents the lack of access controls on administrative storage pathways, leaving secret operational variables readable over open HTTP web ports.

### 2. Misconfigured Server Directory Indexing
* **Evidence Asset:** `[evidence/directory_indexing.png]`
* **Context:** Captures the structural layout leak at the `/admin/` and `/CVS/` server folders due to missing configuration restriction commands.

### 3. Cleartext Transmission Channels
* **Evidence Asset:** `[evidence/insecure_http_warning.png]`
* **Context:** Visual reference documenting the lack of standard browser cryptography layers across user communication interfaces.

---

## 🛠️ Security Engineering Audit Framework
The passive mapping of the application's external surface profile was conducted utilizing clean client-side interrogation tools:
* **Web Browser Inspection Suites:** Extracted raw target server header arrays and verified transmission flags.
* **HTTP Parameter Evaluators:** Analyzed directory listing attributes without running aggressive fuzzing commands.
