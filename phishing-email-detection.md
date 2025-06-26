# 📧 Phishing Email Detection Use Case

## Goal
Detect and alert on emails with suspicious characteristics like:
- Spoofed sender domain
- Known malicious URLs or attachments
- Brand impersonation

## Data Sources
- Email Gateway (Proofpoint)
- Microsoft Defender for Endpoint
- URL Sandboxing (URLScan, VirusTotal)

## Detection Techniques
- Regex-based rule matching
- User-reported phishing
- Attachment behavior analysis

## Response Steps
- Quarantine email
- Notify user
- Hunt similar emails in environment
