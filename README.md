# AWS Data Center Operations (DCO) — Complete Interview Study Guide

![Focus: AWS DCO L3](https://img.shields.io/badge/Focus-AWS%20DCO%20L3-orange.svg)
![Type: Public Study Guide](https://img.shields.io/badge/Type-Community%20Prep-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

Welcome to the **AWS Data Center Operations (DCO) Interview Preparation Guide**. This repository is a structured, community-focused study hub designed for candidates preparing for the AWS Data Center Technician interview loop.

> **⚠️ Legal Disclaimer & Compliance:** > This repository contains **strictly publicly available knowledge**, community prep experiences, and general data center engineering concepts. It does **NOT** contain any proprietary Amazon/AWS information, internal system details, confidential runbooks, or actual NDA-protected interview questions. Use this repository strictly as an educational study aid.

---

## 📌 Guide Overview

The AWS DCO interview evaluation is typically divided into two core areas: 
* **Behavioral & Leadership Principles (~70–80%):** Evaluates culture fit, safety prioritization, customer focus, operational maturity, and STAR storytelling.
* **Technical Concepts & Logical Troubleshooting (~20–30%):** Evaluates server architecture, hardware isolation, fiber optics, networking layers (L1–L3), and structured problem-solving under pressure.

---

## 🗂️ Documentation Index

Click any module below to dive deep into specific study materials:

### 🧠 1. [Leadership Principles & STAR Story Framework](leadership-principles.md)
* Breakdown of core Leadership Principles prioritized for AWS DCO roles.
* Strategic STAR method timing guidelines (Situation, Task, Action, Result).
* Printable STAR story drafting template and follow-up question prep.

### 🎯 2. [LP & STAR Story Master Matrix](lp-star-bank.md)
* Real-world DCO behavioral story blueprints for core AWS Leadership Principles.
* Two-Way Door vs. One-Way Door decision-making framework.
* Quick-reference matrix mapping past experience to LPs and technical metrics.

### 🛠️ 3. [Technical Deep-Dive & Hardware Cheat Sheet](technical-cheatsheet.md)
* **Networking & Hardware:** OSI Model (L1–L3), POST boot sequence, and ECC RAM slot-vs-stick isolation.
* **Storage & Fiber:** RAID configurations, NVMe SSDs, and Single-Mode vs. Multi-Mode fiber optics.
* **Linux CLI:** Key network (`ip`, `ping`, `ethtool`) and system diagnostic commands (`dmesg`, `lsblk`, `lspci`).

### 🔀 4. [Troubleshooting Methodology & Flowcharts](troubleshooting-flowcharts.md)
* Visual Mermaid flowcharts for *No POST / Power Failures* and *Network Link Drops*.
* Step-by-step physical isolation techniques and fiber ferrule cleaning routines.
* The 90-second response standard for verbal technical interview questions.

### 📖 5. [Data Center Hardware & Networking Glossary](hardware-and-networking-glossary.md)
* Essential definitions for server components (BMC, IPMI, ECC, POST).
* Fast-recall reference for fiber connectors, transceiver types (SFP, QSFP), and VFL testing.

### 📋 6. [Interview Day Execution Checklist](interview-day-checklist.md)
* Day-before prep checklist covering STAR story metrics and technical frameworks.
* Morning-of environment, audio, and mindset checks before your loop.
* Key rules for live interview execution (ESD first, single-variable testing).

---

## ⚡ The 6-Step Technical Response Formula

When asked to troubleshoot any technical scenario during the interview, structure your verbal response using this sequence:

1. **Clarify Scope:** Confirm ticket symptoms, affected host(s), and service impact.
2. **Safety First:** Explicitly state ESD strap compliance and physical safety procedures.
3. **Physical Layer Checks (L1):** Inspect PDU power feeds, seating, latching, and physical link lights.
4. **Logical Diagnostics:** Log into out-of-band management (BMC) or review OS system/kernel logs.
5. **Isolate One Variable:** Test or swap **one component at a time** (cables, optics, DIMM slot-vs-stick).
6. **Verify & Document:** Confirm resolution through diagnostic testing, update ticket logs cleanly, and escalate with evidence if out of scope.

---

## 🤝 Contributing & Usage

Feel free to fork this repository, star it if it helps your preparation, or submit a Pull Request if you would like to contribute non-proprietary diagnostic tips or general industry prep resources!

---

## 📄 License

This repository is available under the [MIT License](LICENSE).
