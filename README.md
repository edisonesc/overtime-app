#Overtime App

## Key requirement: company needs documentation that salaried employees did or did not get overtime each work

## Models
- Post => date: rationale:text
- User => devise
- AdminUser => STI (Single Table Inheritance)

## Features:
- Approval Workflow
- SMS Sending => Link to approval or overtime input
- Administrate admin dashboard
- Email summary to managers for approval
- Needs to be documented if employee did not log overtime

## UI:
Bootstrap => formatting