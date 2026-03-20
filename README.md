EarnSafe – AI-Powered Parametric Insurance for Gig Workers
Overview

EarnSafe is an insurance solution designed specifically for gig workers such as delivery partners. These workers frequently experience income loss due to external disruptions like heavy rain, extreme heat, pollution, and sudden curfews.

The platform addresses this problem by automatically detecting such events and compensating workers for lost income without requiring manual claims or paperwork.

Target Users

EarnSafe is intended for:

Food delivery partners (Zomato, Swiggy)

E-commerce delivery agents (Amazon, Flipkart)

Grocery delivery workers (Zepto, Blinkit)

In general, it serves individuals whose income depends on daily work and is vulnerable to external conditions.

Use Case Scenarios
Scenario 1: Heavy Rain

A delivery partner starts their shift, but heavy rainfall disrupts operations. The system detects the weather condition, validates the worker’s location, and automatically processes compensation for income loss.

Scenario 2: Curfew or Restricted Zone

A worker is unable to operate due to a local curfew or restricted delivery zone. The system identifies the restriction and triggers a payout without requiring any manual action from the user.

Application Workflow

The user registers and creates a profile

The system generates a risk score

A weekly premium is calculated

Real-time monitoring of environmental and location data begins

A disruption occurs (e.g., weather or zone restriction)

The system detects and validates the event

The claim is triggered automatically

Fraud detection checks are performed

The payout is processed

The entire process is automated and requires no manual intervention.

Weekly Premium Model

EarnSafe follows a weekly pricing model aligned with the earning cycle of gig workers.

Premiums are determined based on:

Location risk

Weather conditions

Historical disruption patterns

Worker activity

This approach ensures that pricing remains flexible, fair, and affordable.

Parametric Triggers

Claims are triggered automatically when predefined conditions are met. These include:

Heavy rainfall exceeding a defined threshold

Extreme temperature conditions

High pollution levels (AQI thresholds)

Curfews or restricted access zones

Since the system is parametric, no manual claim filing is required.

Platform Choice

The system is implemented as a web application.

This choice was made because:

It allows faster development and deployment

It is accessible across multiple devices

It simplifies API integration

It is suitable for rapid prototyping within a hackathon environment

The platform can be extended to mobile applications in future iterations.

AI/ML Integration

EarnSafe incorporates AI and machine learning in multiple components:

Premium Calculation

A dynamic pricing model adjusts premiums based on risk factors such as location, historical disruptions, and environmental conditions.

Fraud Detection

Anomaly detection techniques are used to identify suspicious or duplicate claims and ensure system reliability.

Risk Scoring

Each user is assigned a risk profile to improve the accuracy and fairness of pricing.

Tech Stack

Frontend: React, Vite

Backend: Node.js, Express

Database: MongoDB

AI/ML: Python, Scikit-learn

APIs: Weather API, Maps API

Payments: Razorpay (test environment)

Version Control: Git and GitHub

Development Plan

Phase 1: User interface and authentication
Phase 2: Core functionality and automation
Phase 3: AI integration (risk scoring, pricing, fraud detection)
Phase 4: Testing, optimization, and dashboard development

Key Features

Fully automated claim processing

Real-time disruption detection

AI-based premium calculation

Fraud detection mechanisms

Instant payout simulation

Impact

EarnSafe aims to:

Reduce claim processing time by over 90 percent

Provide financial stability to gig workers

Eliminate manual claim procedures

Improve transparency and trust in insurance systems

Future Work

Mobile application development

Integration with real-time data sources

Expansion to multiple cities

Advanced AI models for prediction and pricing
