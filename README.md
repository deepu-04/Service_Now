Automated Network Request Management in ServiceNow
📌 Overview

This project provides an automated solution for managing network-related service requests in ServiceNow. It leverages Service Catalog, Flow Designer, and automated workflows to streamline the request lifecycle — from submission and approval to task creation and fulfillment.

The system ensures:

✅ Faster processing with reduced manual effort

✅ Real-time updates & notifications

✅ Automated approvals and task assignments

✅ Improved SLA tracking & transparency

🚀 Features

Service Catalog – Network Request

Custom catalog item for network and connectivity requests

Dynamic variables and UI policies for flexible form handling

Requester information auto-population

Database & Task Tables

Custom Network Database Table with auto-numbering

Network Task Table extending the parent for task-specific fields

Auto-generated unique request and task numbers

Automated Approvals

Related list of approvals linked to each request

Approval workflows for request and task levels

Conditional logic to update status and assignments

Flow Designer Automation

Captures catalog variables and creates database records

Sends email notifications for each stage (request, approval, rejection)

Automatically creates & manages Network Tasks

Tracks work progress with status updates

🛠️ Processes Implemented

Service Catalog Setup

Catalog item: Network Request

Variables, variable sets, and UI policies

Database & Task Table Creation

Custom fields for request tracking

Auto-numbering configuration

Inherited fields for tasks

Approvals & Relationships

Linked approval records to Network Database Table

Scripted filtering for relevant approvals

Flow Designer Automation

Record creation & updates

Email notifications

Multi-level approvals

Conditional branching for approved/rejected requests

📊 Benefits

Reduced manual workload

Faster resolution times

Accurate request capture

Better visibility for users and technicians

SLA tracking and compliance

👩‍💻 Author

Prathipati Deepthisri
