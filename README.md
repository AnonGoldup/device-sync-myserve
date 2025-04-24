# device-sync-myserve
PAD flow, PAD logic, JSON
# SharePoint to MyServe Sync Automation

## Overview
Automates the syncing of IT asset records from a SharePoint list to MyServe using Power Automate Desktop and a cloud-triggered flow.

## Tools Used
- Power Automate Desktop
- Power Automate Cloud Flows
- SharePoint Online
- JSON API Requests

## What It Does
- Retrieves unsynced SharePoint records
- Sends data via HTTP POST to MyServe API
- Updates SharePoint field (MyServeSync) to 'Yes' on success
- Handles empty values and avoids duplicates
- Logs updates & errors to cloud server

## Screenshot
![Flow Overview] Will update

## Outcome
This automation replaced manual sync, reduced errors, and saved significant time for the IT team.
