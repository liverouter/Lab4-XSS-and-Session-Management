# Web Application Security Assessment - Activity Log

## Overview
This activity log documents the testing timeline, evidence capture, target applications, and vulnerability categories analyzed during the security assessment.

---

## Log Entries

| Timestamp | Evidence File | Target | Vulnerability / Category | File Size |
| :--- | :--- | :--- | :--- | :--- |
| **2026-09-03 17:24** | `E-19-DVWA-Cookie-Security.png` | DVWA | Cookie Security | 321 KB |
| **2026-09-03 17:23** | `E-20-Multillidae-Cookie-Security.png` | Mutillidae | Cookie Security | 86 KB |
| **2026-09-03 14:52** | `E-18-Mutillidae-WebStorage-DOM-XSS-Proof.png` | Mutillidae | DOM XSS (Proof of Concept) | 450 KB |
| **2026-09-03 14:50** | `E-17-Mutillidae-DOM-WebStorage-baseline.png` | Mutillidae | DOM XSS (Baseline Analysis) | 416 KB |
| **2026-09-03 12:40** | `E-16-Mutillidae-Stored-XSS-Second-Session.png` | Mutillidae | Stored XSS (Multi-Session Persistence) | 420 KB |
| **2026-09-03 12:29** | `E-15-Mutillidae-Stored-XSS-Proof.png` | Mutillidae | Stored XSS (Proof of Concept) | 365 KB |
| **2026-09-02 19:12** | `E-14-Mutillidae-Stored-XSS-Baseline.png` | Mutillidae | Stored XSS (Baseline Analysis) | 302 KB |
| **2026-09-02 18:46** | `E-13-Mutillidae-Reflected-XSS-Proof.png` | Mutillidae | Reflected XSS (Proof of Concept) | 369 KB |
| **2026-09-02 18:46** | `E-12-Mutillidae-Reflected-XSS-Baseline.png` | Mutillidae | Reflected XSS (Baseline Analysis) | 359 KB |
| **2026-09-02 18:36** | `E-09-DVWA-Reflected-XSS-Impossible.png` | DVWA | Reflected XSS (Impossible Level Mitigation) | 394 KB |
| **2026-09-02 18:35** | `E-10-DVWA-Stored-XSS-Impossible.png` | DVWA | Stored XSS (Impossible Level Mitigation) | 406 KB |
| **2026-09-02 18:35** | `E-11-DVWA-DOM-XSS-Impossible.png` | DVWA | DOM XSS (Impossible Level Mitigation) | 363 KB |
| **2026-09-02 18:18** | `E-08-DVWA-DOM-XSS-Proof.png` | DVWA | DOM XSS (Proof of Concept) | 175 KB |
| **2026-09-02 18:14** | `E-07-DVWA-DOM-XSS-Baseline.png` | DVWA | DOM XSS (Baseline Analysis) | 368 KB |
| **2026-09-02 18:10** | `E-06-DVWA-DOM-XSS-Source-Sink.png` | DVWA | DOM XSS (Source & Sink Identification) | 231 KB |
| **2026-09-02 15:11** | `E-05-DVWA-Stored-XSS-Persistence-Proof.png` | DVWA | Stored XSS (Persistence Verification) | 170 KB |
| **2026-09-02 14:50** | `E-04-DVWA-Stored-XSS-Proof.png` | DVWA | Stored XSS (Proof of Concept) | 446 KB |
| **2026-09-02 14:48** | `E-03-DVWA-Stored-XSS-baseline.png` | DVWA | Stored XSS (Baseline Analysis) | 400 KB |
| **2026-09-02 13:44** | `E-01-DVWA-Reflected-XSS-Proof.png` | DVWA | Reflected XSS (Proof of Concept) | 190 KB |
| **2026-09-02 12:40** | `E-01-DVWA-Reflected-XSS-baselline.png` | DVWA | Reflected XSS (Baseline Analysis) | 370 KB |

---

## Target Breakdown

### DVWA (Damn Vulnerable Web Application)
* **Reflected XSS:** Baseline, PoC, Impossible Level Assessment
* **Stored XSS:** Baseline, PoC, Persistence Testing, Impossible Level Assessment
* **DOM XSS:** Source & Sink Identification, Baseline, PoC, Impossible Level Assessment
* **Session & Cookie Security:** Cookie Configuration Verification

### OWASP Mutillidae II
* **Reflected XSS:** Baseline, PoC
* **Stored XSS:** Baseline, PoC, Multi-Session Verification
* **DOM XSS / Web Storage:** Baseline, PoC
* **Session & Cookie Security:** Cookie Configuration Verification
