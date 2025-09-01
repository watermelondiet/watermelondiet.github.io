---
layout: post
title: "Building StormCloud Arsenal: A Military Cyber Professional's Journey into Cloud Security"
date: 2025-01-15
category: "Cloud Security"
tech_stack: ["AWS", "Terraform", "Python", "MITRE ATT&CK", "IaC"]
read_time: 10
excerpt: "As an Army Cyber Operations Specialist transitioning into civilian cybersecurity, I'm building a comprehensive cloud security testing platform that demonstrates both offensive and defensive capabilities at enterprise scale."
---

As an Army Cyber Operations Specialist (17C) transitioning into the civilian cybersecurity market, I aim to build a portfolio project that will stand out and stretch my skills: a comprehensive cloud security testing platform that demonstrates both offensive and defensive capabilities at enterprise scale.

## Introducing StormCloud Arsenal

StormCloud Arsenal is an automated AWS red team framework that simulates coordinated attack campaigns while simultaneously testing enterprise defensive capabilities. Think of it as having a persistent threat actor on-demand, combined with the detection engineering infrastructure to measure and improve security posture.

The project consists of four integrated components:

### Multi-Account Attack Infrastructure
Separate AWS accounts for attacker resources, target environments, and security monitoring. This mirrors real enterprise architectures where threats move between network segments and cloud accounts.

### Automated Attack Chains
Python-based automation that executes full attack sequences—from initial reconnaissance through privilege escalation, persistence, and data exfiltration. Each technique maps to the MITRE ATT&CK framework for cloud environments.

### Real-Time Detection Engine
AWS-native monitoring using CloudTrail, GuardDuty, and Security Hub, enhanced with custom detection rules and automated response capabilities via Lambda functions.

### Compliance Integration
Security controls are mapped to frameworks like NIST and FedRAMP, generating evidence for government contractor requirements.

## Technical Architecture

The platform leverages Infrastructure-as-Code principles using Terraform to provision reproducible environments. The target environment includes intentionally vulnerable configurations: 

- EC2 instances with overly permissive security groups
- S3 buckets with public access  
- IAM roles with excessive privileges

Attack automation uses Python with the Boto3 AWS SDK to orchestrate sophisticated campaigns. Rather than simple vulnerability scanning, the system executes complex multi-stage attacks that demonstrate understanding of cloud-specific attack vectors:

- IAM privilege escalation
- Lambda persistence techniques  
- Cross-account resource abuse

Detection capabilities integrate multiple AWS services into a unified monitoring platform. Custom CloudWatch queries identify anomalous API patterns, while Security Hub aggregates findings from multiple sources. Lambda functions provide automated incident response, isolating compromised resources and rolling back malicious configuration changes.

## Learning Through Building

This project aims to understand cybersecurity from both the attacker and defender perspectives simultaneously, and expand my skill repertoire to include cloud infrastructure. By building the infrastructure that gets attacked and the systems that defend it, I'm developing holistic security thinking.

Despite nine months of some of the most intellectually demanding training that DoD has to offer, I have never worked with cloud tools. Therefore, the learning is in the doing. At the outset of this project, I knew nothing about AWS, but I had an inkling of an understanding that it could be used to build and deploy an extensive home lab in which I could replicate and build upon the kinds of ranges I saw in training. 

Over the next several weeks, I intend to stretch my skills far beyond what was required in training and to gain a deep understanding of the security challenges that are unique to enterprise clouds. **I'll be taking you with me through a series of blogs if you'd like to join.**

## Measuring Success

Much of the success of this undertaking will be measured in how much I have learned and grown. Some will be in how much attention it garners from recruiters and hiring managers. But - if we're beginning with the end in mind ("backward planning" in Army speak) we should focus on a few technical and business metrics:

### Technical Metrics
- Detection coverage across MITRE ATT&CK techniques
- Mean time to detection and response
- Automation effectiveness

### Business Metrics  
- Risk reduction quantification
- Cost optimization through automation
- Compliance coverage

## Timeline and Next Steps

The project follows an 8-week development timeline. Current progress includes foundational AWS infrastructure deployment and initial Terraform automation, which I'll cover in an upcoming post. 

Upcoming phases focus on:
- Attack chain development
- Detection rule engineering  
- Comprehensive documentation

Throughout the process, I'm documenting lessons learned, architectural decisions, and debugging challenges.

---

*Michael Cooke is a U.S. Army Cyber Operations Specialist (17C) transitioning to civilian cybersecurity, focusing on government contractor cloud security roles in the Seattle market. Follow his progress on [LinkedIn](https://linkedin.com/in/micooke) and [GitHub](https://github.com/watermelondiet) as he builds.*
