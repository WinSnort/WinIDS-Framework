## **The WinIDS v4.1 Deployment Suite**

WinIDS offers a flexible deployment model tailored to your specific infrastructure. Whether you are securing a single workstation or a multi-site enterprise network, our automated frameworks ensure a consistent, hardened installation.

### **1. Standalone Auto-Installers**
These installers provide a "one-click" experience to stand up a complete, self-contained IDS sensor on Windows 10/11 or Windows Server (2019–2025). 

| Deployment Type | Web Server | Database Engine | Ideal For |
| :--- | :--- | :--- | :--- |
| **Framework A** | Apache2 | MySQL | Open-source standard setups |
| **Framework B** | Apache2 | PostgreSQL | High-concurrency environments |
| **Framework C** | IIS | MySQL | Native Windows Server integration |
| **Framework D** | IIS | PostgreSQL | Enterprise-grade stability & performance |

### **2. Distributed Architecture (Multi-Node)**
For larger environments, WinIDS supports a "Manager-Sensor" relationship to offload packet inspection from the primary host.

* **Remote Node Conversion:** A specialized installer that converts any standalone sensor into a **Dedicated Remote Node**. 
* **Auto-Detection:** The remote installer intelligently detects the Host Database (MySQL or PostgreSQL) across the LAN/WAN for seamless connectivity.
* **Multi-Node Management:** The Server Host includes a management module capable of integrating and monitoring an unlimited number of remote nodes from a single security console.

---

### **Technical Specifications**
* **OS Compatibility:** Windows 10/11 (Workstation) | Windows Server 2019, 2022, 2025.
* **Architecture:** 64-bit Optimized.
* **Core Components:** Snort Engine, Barnyard2 Spooler, PulledPork (Rule Management), and BASE (Security Console).
* **Automation:** Full PowerShell 5.1/7.4 integration with intelligent failure recovery and system restore baseline creation (on Workstation).
