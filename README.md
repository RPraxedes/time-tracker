# Time Tracker app

## Key requirement: company needs documentation that salaries employees did or did not get each week

## Models

  x Post -> date:date rationale:text
  x User -> Devise
  x AdminUser -> STI (single table inheritance) [must include "type" string]

## Features:

- Approval Workflow
- SMS Sending -> link to approval or overtime input
- Administrate admin dashboard
- Email summary to managers for approval
- Needs to be documented if employee did not log overtime

## UI:

Bootstrap -> formatting
