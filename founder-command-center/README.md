# Founder Command Center

## Overview

This project outlines a lightweight AI-supported command center for founders, consultants, operators, and small business owners.

The goal is to help busy leaders understand what changed, what needs attention, and what should happen next across their business.

This is not a fully autonomous business manager.

It is a visibility and decision-support system.

## Problem

Founders and operators often have important business information spread across too many places.

Examples:

* CRM tools
* Calendars
* Email
* Slack or Teams
* Project management tools
* Client notes
* Sales activity
* Delivery updates
* Financial tools
* Spreadsheets

When information is scattered, follow-up gets missed, risks show up late, and leaders spend too much time trying to figure out what needs attention.

## Workflow Goal

Create a simple command center that gives the founder or operator a clear view of:

* What changed
* What is stuck
* What needs follow-up
* What is at risk
* What should be reviewed today

## What the Workflow Can Help With

* Daily business brief
* Sales activity summary
* Client follow-up tracking
* Calendar preparation
* Project blocker summary
* Draft follow-up messages
* Priority flags
* Risk flags
* Voice or chat-based Q&A
* Weekly operating summary

## Example Questions It Could Answer

* What changed in the business yesterday?
* Which clients need follow-up?
* Which deals need attention?
* What meetings do I need to prepare for today?
* What projects are blocked?
* What tasks are overdue?
* What client risks should I review?
* What follow-up messages should I send?
* What changed in the CRM this week?
* What should I focus on today?

## Example Daily Brief

```text
Founder Daily Brief

Date: Monday

Top Priorities:
1. Follow up with 2 client leads from last week.
2. Review one blocked project before the afternoon meeting.
3. Prepare for the 3:00 PM client call.

Sales Signals:
- 3 deals had no activity in the last 7 days.
- 1 lead replied and may need a follow-up.
- 2 contacts were added to the CRM.

Client Delivery:
- 1 client project appears delayed.
- 2 tasks are overdue.
- 1 meeting needs prep notes.

Suggested Follow-Up:
Draft a short check-in message for the warm lead who replied last week.

Risk Flags:
- Delayed client follow-up
- Overdue project task
- CRM activity gap
```

## Possible Data Sources

The command center could connect to tools such as:

* HubSpot
* Google Calendar
* Gmail
* Slack
* Notion
* Airtable
* Google Sheets
* Project management tools
* CRM systems
* Client trackers
* Financial dashboards

## Possible Tools Used

* n8n
* OpenAI
* Airtable
* Google Sheets
* HubSpot
* Slack
* Twilio
* Retell
* Google Calendar
* Gmail
* Dashboard tools

## Example Workflow Stages

1. Collect updates from connected tools
2. Summarize what changed
3. Identify overdue items
4. Flag client or sales risks
5. Prepare a daily brief
6. Draft follow-up messages
7. Send summary to founder
8. Wait for human review before any action

## Human Review Rules

A human should always review before:

* Sending emails
* Sending client messages
* Updating CRM records
* Changing project status
* Making financial decisions
* Responding to sensitive client issues
* Canceling or rescheduling meetings
* Taking action on behalf of the business

## Safety Rules

The command center should be designed with strong guardrails.

Default rules:

* Read-only access when possible
* Draft-only messages
* Human approval before sending
* No financial action
* No automatic CRM changes without confirmation
* No confidential information shared publicly
* Clear audit trail
* Least-access permissions
* Sensitive topics are flagged for review

## What AI Can Do

AI can help:

* Summarize updates
* Find patterns
* Draft first versions
* Flag risks
* Organize priorities
* Prepare meeting notes
* Identify missing follow-up
* Make scattered information easier to understand

## What AI Should Not Do

AI should not independently:

* Send client messages
* Make business decisions
* Change financial records
* Modify CRM data without approval
* Commit the business to terms
* Replace the founder’s judgment
* Handle sensitive situations without review

## Example Dashboard Fields

* Date
* Priority level
* Client or deal name
* Source system
* Update summary
* Risk flag
* Follow-up needed
* Suggested next step
* Owner
* Status
* Last activity date
* Human review required

## Example Use Case

A founder starts the day and asks:

```text
What needs my attention today?
```

The command center reviews connected sources and returns:

```text
Today you should review:

1. Client A has not received follow-up in 6 days.
2. Deal B has no activity since last week.
3. Project C has an overdue task.
4. Your 2:00 PM meeting needs prep notes.
5. One draft follow-up message is ready for review.
```

The founder can then approve, edit, or ignore the recommendations.

## My Point of View

Founders are not usually short on effort.

They are short on visibility.

A good command center should not create more noise.

It should make the important signals easier to see.

The best AI workflows do not take control away from the human.

They give the human a clearer view of what needs attention.
