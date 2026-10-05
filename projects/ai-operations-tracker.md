# AI-Assisted Operations Tracker

## Problem

Operational teams often receive requests through channels such as email where information is unstructured.

As volume grows, several problems emerge:

- Requests can be missed.
- Ownership is unclear.
- Threads become fragmented.
- Information must be manually extracted.
- Status tracking becomes difficult.
- Follow-up depends on individual memory.
- Management lacks reliable operational visibility.

## Design Question

How might we transform unstructured incoming requests into structured operational cases without adding administrative work for the team?

## Initial Solution

The first version of the system converts incoming requests into traceable cases.

Each case can contain:

- Unique case ID
- Source
- Request type
- Responsible owner
- Creation date
- Current status
- Relevant information
- Conversation thread
- Required actions
- Follow-up state

## Workflow

```text
Incoming request
       |
       v
Thread detection
       |
       v
Information extraction
       |
       v
Case creation
       |
       v
Classification
       |
       v
Owner assignment
       |
       v
Status tracking
       |
       v
Follow-up
       |
       v
Operational reporting
