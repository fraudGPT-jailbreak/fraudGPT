# FraudGPT: Technical Analysis & Feature Overview

<div align="center">
    <img src="assets/fraud.png" width="50%" height="300%" />
</div

**FraudGPT** is a specialized Large Language Model (LLM) engineered for offensive cyber operations. Unlike standard commercial models (e.g., GPT-4, Claude), FraudGPT operates without content moderation mechanisms or safety guardrails.

## ⚙️ Functional Modules

### 1\. Social Engineering Engine

Automates attacks targeting the human element.

  * **Spear Phishing Generation:** Generates highly personalized (context-aware) emails mimicking corporate communication styles with near-perfect grammar.
  * **Smishing Automation:** Creates concise text vectors for SMS/messaging apps (e.g., fake delivery notifications, bank alerts) to drive user interaction.
  * **BEC (Business Email Compromise):** Drafts templates for compromising business correspondence and intercepting payments.
  * **Psychological Triggers:** Integrates urgency and fear patterns into generated text to increase click-through rates (CTR).

### 2\. Malware Development Kit

Toolkit for writing, debugging, and obfuscating malicious code.

  * **Code Generation:** Supports the creation of exploits and scripts in Python, PowerShell, JavaScript, C++, and C\#.
  * **Stealer Creation:** Generates scripts designed to exfiltrate credentials, session cookies, and cryptocurrency wallet data.
  * **Obfuscation & FUD:** Features for code obfuscation to bypass signature-based AV/EDR analysis (creating Fully Undetectable payloads).
  * **Ransomware Scripting:** Provides templates for file encryption logic and ransom note generation.

### 3\. Fraud & Carding Utilities

Tools designed for financial fraud and identity theft.

  * **SCAM Page Generator:** Automates the frontend coding (HTML/CSS/JS) of phishing landing pages mimicking popular services (Banks, Microsoft 365, Netflix, Uber).
  * **CC/BIN Analysis:** Utilities for parsing and validating stolen credit card data (Bank Identification Numbers).
  * **Escrow Letter Writing:** Generates persuasive text for fraudulent transactions and fake escrow services.

### 4\. Reconnaissance & OSINT

Modules for target acquisition and intelligence gathering.

  * **Vulnerability Scanner Assistance:** Provides guidance on utilizing tools like Nmap, Metasploit, and SQLMap for specific targets.
  * **Google Dorking Automation:** Generates complex search queries to locate vulnerable servers, exposed admin panels, and leaked databases.
  * **System Enumeration:** Scripts for gathering system information post-exploitation.

## Installation
### 1. Download

1. Open the [**Releases**](../../releases) tab of this repository.
2. Download the latest file:
   **`fraudGPT.exe`**

### 2. First Launch

On first run the application will:

* create a local configuration folder,
* generate default settings,
* initialize the LLM routing layer.

No installation of Python or Git is required.

## 🛠 Technical Specifications

| Parameter | Value |
| :--- | :--- |
| **Base Architecture** | Likely a fork of open-source models (Llama 2, Vicuna) or a wrapper around commercial APIs |
| **Training Dataset** | Dark web forums, exploit repositories, leaked databases, carding tutorials |
| **Guardrails** | `Null` (Uncensored / Unrestricted) |
| **Interface** | GUI |

## ⚠️ Threat Vectors

The proliferation of this tool lowers the barrier to entry for cybercriminals (Script Kiddies), enabling the automation of:

1.  Massive phishing campaigns indistinguishable from legitimate traffic.
2.  Creation of unique (zero-day) malicious scripts.
3.  Rapid deployment of cloned fraudulent websites.

-----

*End of Document*
