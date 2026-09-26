# AI-Powered Lead Reactivation & Appointment Booking Automation — n8n

## Overview

An AI-powered automation workflow built with n8n for a simulated real estate lead reactivation process.

The system processes inactive leads, generates personalized outreach messages, handles incoming email replies, classifies lead intent using AI, updates opt-out status, and automatically creates appointments in Google Calendar.

## Problem

Real estate businesses may have inactive leads that require follow-up.

Manually reviewing leads, sending personalized messages, handling replies, updating lead status, and scheduling appointments can take significant time.

## Solution

This project automates the lead reactivation and follow-up process using n8n.

## Workflow

### Lead Reactivation

Old Leads Database  
↓  
Filter Inactive Leads  
↓  
Filter Opted-Out Leads  
↓  
AI Lead Classification  
↓  
Hot / Warm / Low Priority  
↓  
AI Personalized Message  
↓  
Gmail  
↓  
Campaign Log  

### Reply Handling

Gmail Trigger  
↓  
Extract Incoming Reply  
↓  
AI Intent Classification  
↓  
Interested / Not Interested / Wants Appointment  

### Interested

AI Follow-Up Reply  
↓  
Gmail Reply  
↓  
Reply Log  

### Not Interested

Update Opted Out = Yes  
↓  
AI Confirmation Reply  
↓  
Gmail Reply  
↓  
Reply Log  

### Wants Appointment

Google Calendar Create Event  
↓  
AI Appointment Confirmation  
↓  
Gmail Reply  
↓  
Reply Log  

## Features

- Automated inactive lead processing
- AI-based lead prioritization
- Personalized email generation
- Gmail reply monitoring
- AI intent classification
- Interested lead follow-up
- Automatic opt-out handling
- Google Calendar appointment creation
- Campaign logging
- Reply logging
- Appointment tracking

## Tools Used

- n8n
- OpenAI
- Gmail
- Google Sheets
- Google Calendar
- Workflow Automation

## My Role

**Automation Developer | Personal Project**

Designed and built the workflow, including lead filtering, AI classification, personalized messaging, reply handling, intent routing, opt-out management, appointment booking, and campaign tracking.

## Test Results

The workflow was tested using fictional lead data and real test email accounts.

Successfully tested:

- Lead reactivation emails
- Interested lead replies
- Not Interested lead replies
- Automatic opt-out updates
- Appointment requests
- Google Calendar event creation
- Email confirmations
- Campaign and reply logging

## Workflow Preview

### Lead Reactivation Workflow

![Lead Reactivation Workflow](workflow1.png)

### Reply Handling & Appointment Booking Workflow

![Reply Handling and Appointment Booking Workflow](workflow-reply-booking.png)

## Project Status

**Completed — Portfolio Demonstration Project**

## Portfolio Note

This project was created as a personal portfolio demonstration.

Sample lead data is fictional. Credentials, private account information, API keys, and sensitive identifiers are not included in this repository.
