# Task 2 – Phishing Email Analysis

## Cyber Security Internship

### Objective

The objective of this task is to analyze a suspicious email sample and identify common phishing characteristics such as sender spoofing, suspicious links, urgent language, threatening messages, and social engineering techniques.

## Task Description

A simulated phishing email was analyzed to identify indicators that can help detect phishing attempts.

The analysis focused on:

* Sender email address
* Email subject
* Suspicious URLs
* Urgent or threatening language
* Generic greetings
* Social engineering techniques
* Email header analysis

## Phishing Indicators Found

### 1. Suspicious Sender Address

The email claims to be from PayPal Security but uses the `example.com` domain instead of an official PayPal domain.

### 2. Urgent Subject

The subject contains the word "URGENT" and claims that the account has been limited.

### 3. Threatening Language

The email threatens permanent account suspension if the recipient does not respond within 24 hours.

### 4. Suspicious URL

The email contains a verification URL using the `example.com` domain. The link should not be clicked.

### 5. Generic Greeting

The message starts with "Dear Customer" instead of using the recipient's name.

### 6. Social Engineering

The email uses fear, urgency, and the threat of account suspension to pressure the recipient into taking immediate action.

## Header Analysis

The sample used for this project is a simulated text email and does not contain original email headers such as `Received`, `Return-Path`, `SPF`, `DKIM`, or `Authentication-Results`.

Therefore, genuine email-header analysis could not be performed on this sample.

In a real investigation, the original email headers should be obtained and analyzed using a trusted email-header analysis tool.

## Recommended Safety Measures

* Do not click suspicious links.
* Do not open unknown attachments.
* Verify the sender independently.
* Access websites by typing the official website address manually.
* Report suspected phishing emails.
* Delete suspicious emails after reporting them when appropriate.

## Files Included

```text
Task-2-Phishing-Email-Analysis/
│
├── README.md
├── phishing_email_sample.txt
├── phishing_analysis_report.md
└── screenshots/
```

## Conclusion

The analysis identified multiple phishing indicators, including a suspicious sender domain, urgent language, account-suspension threats, a suspicious URL, generic personalization, and social engineering.

This task helped develop awareness of common phishing tactics and basic email threat-analysis skills.
