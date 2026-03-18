# AI-Powered News Publication Automation

[![Methodology](https://img.shields.io/badge/Methodology-DMAIC-blue)]()
[![Tools](https://img.shields.io/badge/Tools-draw.io%20%7C%20AI%20Integration-orange)]()
[![Course](https://img.shields.io/badge/Course-WSZiB%20Kraków%202026-green)]()

## Overview

This project designs an end-to-end automated news publication system for a 
social media editorial team using AI integration and the DMAIC methodology.

**Business problem:** Manual news monitoring is slow, costly, and error-prone.  
**Solution:** An AI system that monitors competitors, detects viral content,  
auto-generates posts, and publishes after editor approval.

---

## Process Logic (TO-BE Model)
```
Competitor website
       ↓
AI monitors views in real time
       ↓
Views > 1,000 in 5 min?
   NO  → End process
   YES ↓
AI generates: text + title + image
       ↓
Editor review
   ├── Approve → Auto-publish to Facebook & Instagram
   ├── Needs fix → AI corrects → back to review
   └── Off-topic → End process
```

---

## DMAIC Framework

### 1. Define
The current AS-IS process requires a journalist to manually monitor competitor 
sites (Onet.pl, WP.pl, Interia.pl), evaluate article popularity, write content, 
create visuals, and publish — all manually. This causes delays and missed trends.

**Business goal:** Reduce reaction time to trending topics, cut operational costs, 
and scale content production without increasing headcount.

### 2. Measure
Key performance indicators defined for comparison (before vs. after automation):

| KPI | Description |
|-----|-------------|
| Reaction time | Time from competitor publish to own post |
| Daily output | Number of posts published per day |
| Engagement | Likes, comments, shares per post |
| Cost per post | Time and resources per publication |
| Rejection rate | % of topics rejected by editor |

### 3. Analyse — 5 Whys
**Problem:** The publication process is too slow and inefficient.

1. Why is it slow? → Editor manually monitors competitor sites
2. Why is monitoring manual? → No automated data collection system exists
3. Why no filtering system? → Process relied on subjective editorial judgment
4. Why subjective judgment? → No analytical tools or decision algorithms implemented
5. Why no tools? → Process was never analysed for optimisation

**Root cause:** Lack of systematic content selection and over-reliance on manual work.

### 4. Improve — TO-BE Process Roles

**AI System (automation):**
- Monitors competitor websites continuously
- Detects viral content (threshold: >1,000 views / 5 min)
- Generates unique text, title, and image
- Submits to editor for approval
- Auto-publishes after approval

**Editor (quality control):**
- Verifies factual and linguistic accuracy
- Evaluates title and image appeal
- Approves, rejects, or requests corrections

**IT Specialist (implementation phase only):**
- Configures monitoring system and social media integrations
- Periodic technical oversight — not required daily

### 5. Control
Monthly KPI review covering: reaction time, daily post count, engagement rate, 
cost per post, and rejection rate. System parameters updated as market conditions 
evolve.

**Expected benefits after automation:**

| Benefit | Impact |
|---------|--------|
| Faster reaction to trends | Higher reach and competitiveness |
| Reduced manual workload | Editor focuses on quality, not repetition |
| Lower operational cost | Less time per post |
| Scalability | Multiple sources monitored simultaneously |
| Content standardisation | Consistent quality based on defined criteria |

---

## Process Map (TO-BE)

<img width="977" height="937" alt="automatyzacja_newsow_schemat drawio" src="https://github.com/user-attachments/assets/6a75b35d-dc45-4752-86f9-c1f70f1e8a3a" />



---

## Files

| File | Description |
|------|-------------|
| `Projekt_Akkus.docx` | Full academic project report (Polish, WSZiB format) |
| `process_map.drawio` | Editable BPMN-style process diagram |

---

## Context

**Course:** Automatyzacja i Robotyzacja Procesów Biznesowych  
**Institution:** Wyższa Szkoła Zarządzania i Bankowości (WSZiB), Kraków  
**Year:** 2026  
**Author:** Daryna Akkus

---

## Author

**Daryna Akkus** — Data Analyst | Business Analyst  
[GitHub](https://github.com/DarynaAkkus) · 
[LinkedIn](https://linkedin.com/in/daryna-akkus-309289308)
