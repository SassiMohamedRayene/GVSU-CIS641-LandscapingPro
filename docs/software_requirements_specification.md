# Overview

This Software Requirements Specification describes the initial functional
and non-functional requirements for LandscapingPro, a Landscaping Service
Management System. The application will help customers explore services
and request quotes, while helping the administrator prepare quotes and
schedule appointments. This prototype SRS was prepared by Mohamed Rayene
Sassi as an individual project approved by the professor.

# Functional Requirements

1. Service Browsing
   1. **FR1:** The system shall display the name, description, and pricing
      information of each active landscaping service to website visitors.

2. Quote Requests
   1. **FR2:** The system shall allow an authenticated customer to submit
      a quote request containing a selected service, property address,
      project description, and preferred service date and time.

3. Quote Management
   1. **FR3:** The system shall allow an administrator to create a quote
      for a submitted request by entering an estimated price and service
      description.

4. Appointment Scheduling
   1. **FR4:** The system shall allow an administrator to schedule an
      appointment for an accepted quote by entering a service date,
      start time, and estimated duration.

# Non-Functional Requirements

1. Password Security
   1. **NFR1:** The system shall store user passwords only as salted
      password hashes.

2. Performance
   1. **NFR2:** The system shall display the services page within three
      seconds in at least 95% of test requests when 20 users access the
      application concurrently in the agreed test environment.

3. Responsive Layout
   1. **NFR3:** The system shall display the home page, services page,
      and quote request form without horizontal scrolling at viewport
      widths of 375, 768, and 1440 pixels.

4. Form Usability
   1. **NFR4:** The system shall preserve previously entered quote request
      values when a submission is rejected because of a validation error.
