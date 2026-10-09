# Assignment 1: Student Project Approval and Allocation

## Overview
This BPMN diagram represents the process of submitting, reviewing, and approving student project proposals, followed by faculty guide allocation.

## Process Flow

1. **Submit Proposal:** The student team submits a project proposal.
2. **Validate Proposal:** The system checks whether the proposal form and team details follow the required rules.
3. **Screen Proposal:** The project coordinator screens the submitted proposal.
4. **Evaluate Proposal:** The review committee evaluates the proposal and makes a decision.
5. **Review Decision:**
   - **Approved:** The process continues to faculty guide allocation.
   - **Revise:** The student team is asked to revise and resubmit the proposal.
   - **Rejected:** The student is notified, and the process ends.
6. **Check Guide Availability:** The system checks the faculty guide's availability and workload.
7. **Send Allocation Request:** An allocation request is sent to the selected faculty guide.
8. **Faculty Response:** The guide accepts or declines the request. If declined, another guide can be considered.
9. **Complete Allocation:** The system notifies the student and records the allocation.

## BPMN Elements Used
- Start and End Events
- User Tasks
- Service Tasks
- Exclusive Gateways for decisions
- Sequence Flows
- Swimlanes to represent responsibilities

## Outcome
The process ends when the proposal is rejected or when a faculty guide is successfully allocated to the student project.
