# MOVE-Rx PHG: e-Delphi Platform

**Research Title:** Development and Validation of a Standardized Transfer Prioritization Scoring Instrument for Pharmacy Personnel in Pahang: A Modified Delphi Study  
**Ethics Approval:** Medical Research and Ethics Committee (MREC) - NMRR ID-26-03968-MPU  
**Principal Investigator:** Muhammad Hafizul Aniq bin Khairul Hafidz, RPh.

## Project Overview
This repository contains the frontend web application for the MOVE-Rx PHG Modified Delphi study. The platform transitions traditional manual Delphi rounds into a secure, mobile-responsive system. It is designed to capture expert consensus from pharmacy administrators (KJF and PFK) across 23 PTj in Pahang, aiming to establish an objective, evidence-based human resource governance framework.

## Key Features
* **Dynamic Delphi Interface:** Mobile-optimized matrix tables for evaluating 9 human resource transfer parameters using a 5-point Likert scale.
* **Conditional Logic:** Automated prompt logic requiring mandatory qualitative justification for any scores ≤ 3.
* **Real-Time Consensus Dashboard:** Secured researcher interface that instantly computes statistical consensus metrics (Median and Interquartile Range) and aggregates qualitative text.
* **Serverless Architecture:** Lightweight HTML/JS/CSS frontend deployed via Cloudflare Pages, integrated with a Google Apps Script (GAS) API for direct data streaming to a private Google Sheet.

## Tech Stack
* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Hosting:** Cloudflare Pages (via GitHub integration)
* **Backend API & Database:** Google Apps Script (`doPost`), Google Sheets
