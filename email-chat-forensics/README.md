# Case Study: Email and Chat Communication Forensic Analysis

## Dataset Notice

All artifacts examined in this investigation originate from a controlled forensic dataset designed to simulate real digital communication environments.  
No private or personal user data is included in this case study.

The purpose of this investigation is to demonstrate digital forensic analysis techniques and investigative methodology.

---

## Overview

This case study documents a forensic investigation into communication artifacts extracted from multiple messaging and email platforms.  
The objective was to reconstruct user communication patterns and identify potential coordination between individuals across several digital communication channels.

The investigation was conducted using the Paraben E3 forensic platform to analyze email databases, messaging artifacts, and communication metadata.

---

## Tools

Paraben E3 Forensic Platform

---

## Evidence Sources

The investigation included analysis of communication artifacts extracted from several platforms:

- Email header metadata
- Outlook email database
- Thunderbird email archive
- Slack workspace database
- Discord chat database

These sources provided multiple layers of communication evidence used to reconstruct interaction timelines between users.

---

## Investigation

### Email Header Analysis

Email metadata was examined to determine message routing, sender infrastructure, and communication timestamps.

Header analysis revealed that the message originated from ProtonMail infrastructure.  
Sender domain and mail routing servers were identified through examination of header fields.

Key artifact identified:

Sender email: a.harknes.2021@protonmail.com  
Mail server: mail-40132.protonmail.ch  
Mail server IP: 185.70.xxx.xxx

---

### Outlook Email Database Examination

The Outlook email database was analyzed to identify messages relevant to the investigation.

Artifacts examined included:

- message threads referencing internal coordination
- attachments stored within the database
- timestamps associated with user communications

These artifacts helped establish the sequence of communication events.

---

### Slack Workspace Analysis

Slack workspace artifacts were examined to identify users participating in internal communication channels.

The investigation included analysis of:

- workspace member lists
- channel structures
- conversation histories

Chat records revealed collaboration between several users across multiple channels.

---

### Thunderbird Email Archive Analysis

A Thunderbird email archive was imported into the forensic platform and searched for additional communication artifacts.

Header analysis and message content examination helped identify sender infrastructure and communication timestamps associated with the investigation.

---

### Discord Communication Analysis

Discord database artifacts were analyzed to reconstruct user conversations.

Artifacts examined included:

- user friend lists
- private message conversations
- message timestamps

These records revealed communication between Beverly Gates and Lena Goodwin and contributed to reconstructing the communication timeline.

---

## Findings

Analysis of communication artifacts across multiple platforms revealed coordinated discussions between several individuals.

Correlation of email metadata and messaging artifacts enabled reconstruction of cross-platform communication timelines and identification of key participants involved in the communication exchanges.

---

## Skills Demonstrated

Digital forensic investigation  
Email header analysis  
Messaging artifact analysis  
Database artifact extraction  
Cross-platform evidence correlation  
Communication timeline reconstruction

---

## Investigation Workflow

Evidence Acquisition → Artifact Extraction → Communication Analysis → Timeline Reconstruction → Findings Documentation
