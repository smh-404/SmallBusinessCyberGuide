# SmallBusinessCyberGuide
This repository consists of a straight forward guide to enhance the cyber security of small to medium sized companies, highlighting the essentials for an organization in terms of what needs to be done to protect themselves from the majority of cyber attacks.

## Introduction
Areas that will be covered:

1. What companies need to worry about their cyber posture?
2. What controls need to be in place?
3. What are the minimum cyber tasks/actions that need to be performed?
4. What response and recovery plans need to be incorporated in business continuity planning?

Reach out to me if you have any suggestions or feedback!

## Guide

### What companies need to worry about their cyber posture?
I have classified company exposure levels to cyber attacks in the following three categories:
  1. Companies with public-facing digital assets (e.g. a websites, portals, social media, etc.)
  2. Companies with internal digital assets (e.g. servers, desktops, etc.)
  3. Companies with no digital assets

If a company has public-facing and/or internal digital assets, then they should have some understanding and coverage of basic cyber security controls. The reason why they are split into two categories is that there are different types of attacks and security controls for each.

### What controls need to be in place?
For public-facing digital assets, the following security checklist needs to be covered:
- Email security controls to prevent impersonation. This includes the incorporation of SPF, DKIM, and DMARC records.
- Ensuring that websites do not exposure internal information unintentionally. This includes admin user lists, internal documents, server configuration information, etc.
- Limited open ports that are required to be open and publicly accessible. All ports that are unused should be closed, and any port that is not intended for public use should be IP restricted.
- Modern and up-to-date encryption protocols in use on website certificates. This includes SSL/TLS protocols and the configured ciphers that encrypt all website-based traffic.
- Website security header configurations. This inludes Content Security Policy (CSP), HTTP Strict Transport Security (STS), etc.
- Password policies need be incorporated and enforced. All accounts should have strengthened passwords that are over 12 characters long, and consist of a combination of uppercase and lowercase letters, numbers, and symbols.
- Multi-Factor Authentication (MFA) should be configured wherever possible. If a public-facing digital asset does not support MFA, then this should be raised to the vendor and the risk should be noted.
- Social media accounts should be created and managed by a company owned email, and not for a specific employee that might leave the company. Password policies and MFA should be implemented across all accounts.
 
For internal digital assets, the following security checklist needs to be covered:
- USB access to all devices must be blocked.
- Devices should be updated to the latest operating systems.
- All software that is used on company devices should be authorized and approved.
- All internal servers should be IP restricted and access should only be granted to approved users.
- Zero-Trust policies and Need-To-Know protocols should be implemented wherever possible.

### What are the minimum cyber tasks/actions that need to be performed?
- Periodic assessments need to be done to ensure that the controls listed above are in place, which may change due to updates to existing digital assets or new additions of digital assets.
- Free website security scans should be utilized at least once a year or after any major change.
- Operating sytem and software updates and patches need to be completely periodically. This can't be ignored because threat actors view outdated servers and assets as low-hanging fruits, as a lot of the time updates or patches are released to fix bugs that can be exploited.
- Cyber security training sessions should be mandatory for all employees at least once a year. This should cover phishing emails, malicious websites, dangerous downloads, social engineering, etc.


### What response and recovery plans need to be incorporated in business continuity planning?
- Is there a load balancer configured on the website?
- Is Denial-of-Service (DoS) protection (e.g. cloudflare) enabled?
- Backups:
  - Are backups being taken of all data?
  - How often are they being taken?
  - Where are they stored?
  - Is the backup process defined?
 
