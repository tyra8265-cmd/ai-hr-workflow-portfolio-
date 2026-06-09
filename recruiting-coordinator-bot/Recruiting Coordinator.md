# Recruiting Coordinator Bot

## Overview

This project outlines a human-reviewed AI workflow that helps recruiting teams organize candidate communication, draft responses, track follow-up, and flag sensitive issues.

The goal is not to replace recruiters or make hiring decisions.

The goal is to reduce missed follow-up, improve response time, and help recruiters stay organized.

## Problem

Recruiters often manage a high volume of candidate replies, scheduling requests, status updates, and follow-up messages.

Important messages can get missed when communication is spread across inboxes, spreadsheets, calendars, and chat tools.

## What the Workflow Can Help With

- Read candidate replies
- Identify candidate intent
- Detect scheduling availability
- Draft recruiter responses
- Flag sensitive topics
- Update candidate tracker
- Create daily recruiter summaries

## Example Candidate Reply Categories

- Interested
- Ready to schedule
- Asked a question
- Resume received
- Declined
- Needs follow-up
- Needs human review
- Unclear

## Human Review Rules

A human should always review before:

- Sending a candidate message
- Rejecting a candidate
- Discussing compensation
- Handling accommodations
- Responding to legal or sensitive issues
- Making any hiring decision

## Sensitive Topics to Flag

- Salary or compensation
- Visa or immigration
- Disability or accommodation
- Medical information
- Legal concerns
- Harassment or discrimination
- Background checks
- Angry or escalated language

## Tools That Could Be Used

- n8n
- Gmail or Outlook
- Google Sheets
- Slack or Teams
- Google Calendar
- OpenAI
- Airtable

## Sample Output

The workflow could produce a recruiter summary like:

```text
Candidate: Jordan Lee
Role: Operations Manager
Status: Ready to schedule
Summary: Candidate replied with availability for Tuesday and Thursday afternoon.
Suggested next step: Draft scheduling reply for recruiter review.
Risk flags: None
Human review required: Yes
