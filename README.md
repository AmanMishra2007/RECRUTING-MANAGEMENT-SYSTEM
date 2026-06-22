# RECRUTING-MANAGEMENT-SYSTEM
End-to-end Salesforce Recruitment Management System for managing jobs, candidates, interviews, recruiters, and offers with automated workflows, validation rules, Apex triggers, and real-time dashboards.
The Recruiting Management System is a Salesforce-based recruitment automation platform designed to streamline the entire hiring lifecycle, from job creation to candidate onboarding. The system enables HR managers and recruiters to efficiently manage job openings, applications, interviews, and offer letters while automating repetitive recruitment processes.

Business Problem

Traditional recruitment processes involve manual tracking of candidates, interview scheduling, offer management, and vacancy monitoring. This often leads to delays, data inconsistency, and poor communication between recruiters and hiring teams.

The Recruiting Management System addresses these challenges by:

Centralizing recruitment data.
Automating candidate workflows.
Tracking hiring progress in real time.
Providing recruitment analytics through reports and dashboards.
Data Model
Objects
Company (Account)
Candidate (Contact)
Job Position
Application
Interview
Recruiter
Job Recruiter
Offer
Recruitment Workflow
Step 1: Create Job Position

HR Manager creates a new job position specifying:

Job title
Required openings
Salary range
Job category (IT / Non-IT)

Validation rules ensure valid openings and salary ranges.

Step 2: Candidate Application

Candidates apply through the Application Form Screen Flow.

The flow:

Collects candidate details.
Associates the candidate with a job position.
Creates an Application record.
Automatically sets application status using a Record Triggered Flow.
Step 3: Recruiter Assignment

Recruiters are mapped to jobs through the Job Recruiter object.

This enables:

Multiple recruiters per position.
Workload distribution.
Recruitment ownership tracking.
Step 4: Interview Management

Once shortlisted:

Interview records are created.
Interview dates are validated.
Scheduled reminders are automatically sent before interviews.
Interview results are evaluated using automated flows.
Step 5: Offer Management

Selected candidates receive offers.

The system:

Validates offer salary.
Tracks offer acceptance.
Automatically updates job status when an offer is accepted.
Step 6: Job Closure

A Scheduled Triggered Flow continuously monitors open positions.

If:

Required openings are filled, or
Offer acceptance reaches vacancy count,

the job position is automatically closed.

Salesforce Automation
Screen Flows
Application Form Screen Flow
Create Job Position Flow

These flows provide a guided UI for HR teams and candidates.

Record Triggered Flows
Set Application Status on Create
Check Interview Result
Close Job Position after Offer Acceptance

These automate recruitment decision-making processes.

Scheduled Flows
Interview Reminder Automation
Vacancy Monitoring and Job Closure

These run automatically without user intervention.

Validation Logic

The system includes validations for:

Number of openings
Salary ranges
Application dates
Interview dates
Offer salary amounts

This ensures recruitment data integrity and prevents invalid records.

Security Model
Roles
Admin
HR Manager
Recruiter
Profiles
System Administrator
HR User
Recruiter User

This role hierarchy ensures secure access to recruitment information.

Apex Development
Apex Classes
RecruitmentReportBatch
InterviewReminderScheduler
JobDashboardController
ApplicationController
InterviewController
Trigger
ApplicationTrigger

Used to implement advanced business logic and automation beyond declarative Salesforce tools.

Lightning Web Components (LWC)

Custom Lightning Web Components:

interviewManagement
applicationComponent
jobDashboard

These provide interactive recruiter dashboards and candidate management interfaces.

Reporting & Analytics

Reports:

Jobs by Status
Applications per Job
Interview Results
Offer Acceptance

Dashboard:

Recruitment Dashboard

The dashboard provides real-time recruitment KPIs such as:

Open positions
Candidate pipeline
Interview success rates
Offer acceptance trends
Key Achievements
Automated end-to-end recruitment lifecycle.
Reduced manual recruiter workload.
Improved hiring process visibility.
Enabled real-time recruitment analytics.
Implemented Salesforce Flow, Apex, LWC, Reports, and Dashboard integrations.
Technologies Used
Salesforce CRM
Apex
SOQL
Lightning Web Components (LWC)
Salesforce Flow Builder
Validation Rules
Triggers
Reports & Dashboards


Skill Upgradation for Rural youth Empowerment Trust
Student Details
Name: Aman Kumar Mishra

Email ID: amanmishrag1salesforce@gmail.com

College Name: Dr. B. C. Roy Engineering College, Durgapur

Branch/Specialization : Masters in Computer Applications

Course Details
Course Opted: Salesforce

Instructor Name: Sriram Yarrabothula

Duration: 6 Months

Trainer Details
Trainer Name: Sriram Yarrabothula

Trainer Email ID: yarrabothulasriram@gmail.com

Trainer Designation: Salesforce developer


