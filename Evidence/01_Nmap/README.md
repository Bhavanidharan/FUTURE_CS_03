# Nmap API Host Scan

## Overview

This folder contains the Nmap scan performed on the target API host used during the API Security Risk Analysis. The scan was conducted to identify accessible network services and verify the availability of the target before performing API testing.

---

## Objective

The purpose of this scan was to:

- Verify the target host is reachable.
- Identify open network ports.
- Detect running services.
- Collect basic network information.
- Support the overall API security assessment.

---

## Tool Used

- **Nmap 7.98**
- Windows PowerShell

---

## Target

**Host:** `jsonplaceholder.typicode.com`

---

## Scan Performed

```bash
nmap jsonplaceholder.typicode.com
```

---

## Evidence

| File | Description |
|------|-------------|
| **Nmap_API_Host_Scan.png** | Screenshot showing the Nmap scan results, including the discovered open port and detected service. |

---

## Observation

The scan identified:

- Host is reachable.
- Open TCP port:
  - **80/tcp (HTTP)**
- Service detected:
  - HTTP

---

## Security Note

This scan was performed only for information gathering on a publicly accessible test API. No exploitation, vulnerability scanning, or intrusive testing was conducted.

---

## Conclusion

The Nmap scan successfully confirmed that the target API host was online and exposed an HTTP service, providing the necessary network information to proceed with the API Security Risk Analysis.

---

**Task:** Future Interns – Cyber Security Task 03  
**Project:** API Security Risk Analysis  
**Author:** Bhavanidharan Sathiyaseelan
