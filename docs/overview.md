# Overview

## Goal

Show how a business can automate lead intake and routing using n8n plus AI.

## Problem

Many businesses receive leads through forms or email, but handling is often manual:

- reading each submission
- deciding whether it is a good lead
- extracting details
- forwarding to the right person
- logging it in a sheet or CRM
- responding quickly

This creates delays and inconsistency.

## Proposed solution

This workflow automates the first layer of lead operations.

It can:

- capture new leads
- classify intent
- score relevance
- extract structured information
- route the lead
- trigger follow-up actions

## Example input

Name: Sarah Johnson  
Business: BrightTax Solutions  
Email: sarah@brighttax.example  
Message: We need help automating lead handling, client onboarding, and internal admin tasks. Looking for an implementation partner this month.

## Example output

Category: Qualified lead  
Priority: High  
Summary: Accounting business seeking automation support this month  
Key details:
- Industry: Accounting
- Need: Lead handling, onboarding, admin automation
- Intent: Services enquiry
- Timing: Near-term
- Quality score: High

Next action:
- Notify sales inbox
- Add to CRM or sheet
- Draft reply
