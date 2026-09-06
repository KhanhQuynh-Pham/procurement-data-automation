# Procurement Data Automation

Two lightweight Power Platform tools (Power Automate, Power Query) built to remove manual, repetitive work from the PR to PO procurement process for buyers.

## Problem
Buyers manually collected Purchase Requisition (PR) details from incoming emails, then cross checked them against Purchase Orders (PO) across two disconnected systems, SAP and an internal request platform. Both steps were repetitive, time consuming, and error prone as volume grew.

## Solution
- **PR data collection (Power Automate):** Automatically extracts PR information from incoming Outlook emails and logs it into Excel, removing manual copy paste from email notifications.
- **PR to PO reconciliation (Power Query):** Joins PR and PO data from both systems into one view, then surfaces only new records at each refresh, while preserving buyers' manually added tracking notes.

## Tools
Power Automate, Power Query (M language), Excel, Outlook

## Note
Company specific details (system names, file paths, data) have been redacted or anonymized. This repository reflects the author's own independently built solution.
