# Matthew Lazarowitz
**Senior Software Engineer**  
[LinkedIn](https://linkedin.com/in/Matthew-Lazarowitz) | [GitHub](https://github.com/mattlazarowitz)

---

## Work Experience

### NVIDIA — Sr Software Engineer  
*Santa Clara, USA | Jul 2017 – Present*

- **Owned the NvSIPL Core Verification project**, tracking unit and integration test metrics, resolving or coordinating fixes for failures, and supplying verification data to support **ISO 26262** compliance  
- Established a framework for the **physical safety of active sensors** on the DRIVE IX platform, aligning with automotive safety and compliance requirements  
- Formulated C and C++ coding guidelines in alignment with **MISRA** and **AutoSAR** standards, guiding adoption across teams  
- Integrated industry-standard practices into the **formal code inspection process**, including a metrics-driven strategy for planning, execution, and continuous improvement  
- Pioneered use of **AI-assisted development tools (Cursor)** to analyze complex C++ code paths, creating structured context for LLMs that enabled automated test-to-function traceability and improved debugging efficiency  

**Automation and Tooling Contributions**  
- Developed an **automated C++ code analysis pipeline** (Clang Diagnostic Parser) to identify non-C++98 compliant patterns across large codebases, enabling systematic modernization of legacy systems  
- Created a **metrics collection and reporting system** to track code quality and support data-driven development decisions  
- Engineered **Python automation systems** for Perforce integration, reducing manual compliance effort by **90%** by generating and maintaining work product index files for 47+ artifacts  
- Automated **hardware testing workflows** (Drive Farm Colossus helper scripts) through shell scripting, reducing manual setup time and configuration errors  
- Built **Perforce integration tools** to catalog and extract metadata from engineering work products, establishing the foundation for document management automation workflows  
- Developed a **report aggregation system** to automatically download and organize test results, coverage data, and analysis reports from multiple testing platforms into structured P4 workspaces  
- Prototyped a tool to **extract and analyze metrics** from static and dynamic testing reports (SWUTR reports), streamlining software test result reporting  

---

### Cisco Systems — Technical Lead  
*San Jose, USA | Jun 2012 – May 2017*

- **Led the design and implementation** of the Precision Boot Order feature for Cisco blade servers, enabling fine-grained control of boot sequencing across complex environments  
- Authored and submitted **multiple patent applications** related to server firmware innovations  
- Enhanced firmware logging systems, accelerating root cause analysis of unexpected boot behaviors and improving system reliability  
- Developed **UEFI shell utilities** that streamlined BDS issue troubleshooting for engineering teams  
- Prototyped an XML parser to optimize communication between UCSM and server firmware, reducing interface overhead  
- Conducted early research on **unit testing for UEFI firmware**, implementing a hybrid unit testing framework ahead of Microsoft’s official tooling  
- Ensured **on-time hardware launches** by resolving compatibility issues and establishing cross-team firmware standards  

---

### Booz Allen Hamilton — Senior Software Engineer  
*McLean, USA | Oct 2010 – May 2012*

- Engineered and enhanced **mobile data recovery tooling** for a DOJ client, improving forensic analysis capabilities for law enforcement  
- Performed **vulnerability assessments** on feature phones, identifying and mitigating potential security risks  
- Conducted in-depth analysis of **feature phone flash images**, supporting recovery of critical digital evidence  

---

### American Megatrends — Software Engineer  
*Norcross, USA | Sep 2005 – Sep 2010*

- Developed and maintained **firmware for new hardware platforms**, contributing to successful product launches across multiple OEM partners  
- Implemented **custom firmware features** in response to client requests, strengthening AMI’s reputation for customer-focused solutions  
- Migrated features across code bases to ensure backward compatibility and consistent functionality across product lines  
- Performed **root cause analysis** of software failures, reducing defect recurrence and improving firmware stability  

---

## Projects

### ESP8266 IoT Framework  
- Developed a configurable **IoT framework** for ESP8266 microcontrollers (Arduino) featuring runtime configuration through a responsive web interface, eliminating the need for reflashing firmware  
- Implemented **persistent JSON-based configuration storage** with LittleFS and multi-mode Wi-Fi operation (AP/Station) with intelligent reset detection for mode switching  
- Engineered **power-efficient design** with Wi-Fi state management and deep sleep modes, extending device battery life  
- Designed framework for **security and flexibility**, supporting multiple ESP8266 board variants  

---

### ESP8266 Environmental Monitoring System (SHT30)  
- Built a **low-power IoT temperature and humidity monitor** integrating an SHT30 sensor with an ESP8266 microcontroller  
- Implemented **MQTT communication** for real-time reporting to central monitoring systems with secure authentication  
- Engineered **fault-tolerant design** with error checking, timeout handling, and infrastructure issue detection  
- Leveraged custom IoT framework for **runtime configuration and reliable field operation**  

---

### Game Data Analysis Tool (No Man’s Sky Save Parser)  
- Developed a **Python tool** to parse and analyze binary save data from *No Man’s Sky*  
- Implemented **3D coordinate transformation algorithms** converting in-game positions into geographic latitude/longitude  
- Created **CSV export pipeline** for systematic analysis of player bases and discovered systems  
- Built a **CLI tool with argparse**, supporting flexible data output and integration into larger workflows  

---

### IR Protocol Reverse Engineering (Vornado Fan)  
- Reverse engineered a **proprietary IR protocol** for the Vornado Transom fan through signal capture and analysis  
- Implemented an **ESP8266-based IR remote system** using precise PWM modulation and microsecond-level timing control  
- Designed a **robust command encoding/validation system** supporting multiple modes (power, speed, direction)  
- Integrated with **home automation platforms via MQTT**, enabling remote smart control of the fan  

---

### Motion (forked open-source project)  
- **Diagnosed and corrected NVENC hardware-accelerated video encoding issues** in Motion, restoring stable and high-quality video performance  

---

## Education
**Penn State University** — B.S. Electrical Engineering  
*Dec 2004 | USA*  

---

## Publications
- *Edge Anti-Aliasing Utilizing Morphological…*  
  Proc. of the International Conference on Consumer Electronics (2005)  
  — Proposed novel image processing kernels for edge detection and anti-aliasing  

---

## Patents
- **US8869282** — Anti-malware support for firmware  
- **US9401848** — Stateless flexible boot control  

---

## Skills
- **Languages:** C, C++, Python  
- **Domains:** Firmware, Embedded Systems, Automotive Safety, IoT, System Software  
- **Practices:** Code Coverage, FMEA, Code Inspection, Static/Dynamic Analysis, Safety Standards (MISRA, AutoSAR, ISO 26262), AI-Assisted Development  
- **Tools:** Perforce, Git, UEFI, MQTT, LittleFS, Arduino, ESP8266, FFmpeg/NVENC, Cursor (AI code assistant)  
