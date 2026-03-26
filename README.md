# Home Lab Virtual Network

## Overview

This repository documents the design of a segmented virtual network home lab built to simulate a small enterprise-style environment. The lab supports practical security learning in network architecture, monitoring awareness, and defensive security thinking aligned with Security Operations Centre (SOC) analyst responsibilities.

The objective of this lab is to demonstrate structured network design principles and how segmentation can improve visibility, containment, and security monitoring within an organisation.

---

## Lab Design Objectives

The virtual environment was structured to simulate how systems are logically separated within a business network to reduce attack surface exposure and support incident detection and response workflows.

Key objectives included:

- Creating logical separation between internal systems
- Demonstrating secure network boundary thinking
- Supporting monitoring-focused security learning
- Simulating realistic enterprise-style infrastructure design
- Reinforcing defensive architecture principles  

---

## Network Structure

The virtual network was designed using multiple logical zones representing common enterprise environments:

**User Network Segment**

Represents employee workstation activity and normal user-generated traffic patterns typically monitored within a corporate environment.

**Server Network Segment**

Represents internal service infrastructure requiring controlled access and monitoring due to its importance to business operations.

**Administrative Segment**

Represents privileged-access systems used for management and maintenance tasks requiring stricter access control and monitoring visibility.

---

## Security Design Considerations

The structure of the environment reflects several defensive architecture principles used within production enterprise environments:

- Network segmentation to reduce lateral movement risk
- Separation of privileged administrative activity
- Logical isolation of server infrastructure
- Monitoring-aware infrastructure placement
- Reduced attack surface exposure through structured layout  

These design choices support detection-focused security workflows used within SOC environments.

---

## SOC Analyst Relevance

Understanding how enterprise networks are structured helps analysts interpret alerts more effectively and recognise suspicious activity patterns within segmented environments.

This lab supports development of practical awareness in:

- Interpreting activity across network zones
- Recognising unusual communication paths
- Understanding privilege boundaries
- Supporting investigation workflows
- Improving detection reasoning during alert triage

---

## Skills Demonstrated

This project demonstrates foundational security capabilities relevant to entry-level SOC analyst roles:

- Network segmentation awareness
- Defensive infrastructure thinking
- Enterprise-style architecture familiarity
- Monitoring-oriented environment design
- Structured security documentation practice

---

## Future Enhancements

Future development of this environment may include:

- Simulated monitoring scenarios
- Alert investigation walkthrough examples
- Authentication event analysis scenarios
- Network traffic pattern interpretation exercises

---

## Purpose of Repository

This repository forms part of a structured cyber security learning portfolio focused on developing practical SOC analyst skills through documentation-led technical simulations aligned with enterprise security environments.
