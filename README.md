# PedroT-SIEM-Deployment

# Sprint 11 Project Plan Proposal
# Building a SIEM Lab: From Deployment to Detection
## My Journey Into SIEM

When I first started learning cybersecurity, I quickly realized that understanding security concepts was only part of the process.

I wanted to see what actually happens when a system is attacked.

What does an attack look like in the logs?

How does a security analyst recognize suspicious activity?

And more importantly, how do you connect multiple events together to understand what actually happened?

That led me to build my own Security Information and Event Management (SIEM) lab using **Wazuh, Sysmon, and Windows**.

This project became more than just deploying a SIEM. It became an investigation into how endpoint telemetry can be collected, analyzed, and turned into a story.

---

## The Goal

The goal of this project was to build a working SIEM environment and use it to investigate simulated security activity.

I wanted to go beyond simply installing the tools.

I wanted to understand the complete process:

**Generate activity → Collect telemetry → Analyze events → Identify suspicious behavior → Build the timeline**

This project gave me an opportunity to practice the same type of thinking used by security analysts when investigating events inside a SIEM.

---

## The Environment

For this lab, I built an environment consisting of:

- **Wazuh** – SIEM and security monitoring platform
- **Windows** – Endpoint generating security telemetry
- **Sysmon** – Detailed Windows system and process monitoring
- **Command-line activity** – Used to generate observable events
- **GitHub** – Documentation and project portfolio

The purpose was to create a controlled environment where I could generate activity and then investigate what appeared in the SIEM.

---

## Starting the Investigation

Once the environment was running, the next question was simple:

> **Would I actually be able to see the activity I generated?**

That became the focus of the investigation.

I generated activity on the Windows endpoint and then moved into Wazuh to examine the telemetry.

At first, the individual events didn't necessarily tell the entire story.

The real value came from connecting the events together.

That is where the investigation became interesting.
