<img width="1563" height="1563" alt="image" src="https://github.com/user-attachments/assets/3563e8d6-f8da-45b1-a749-d66abf1080cf" />
SURE ProEd (formerly SURE Trust)
Skill Upgradation for Rural youth Empowerment Trust
# Student Details
Name: AMAN KUMAR MISHRA

Email ID: amanmishrag1salesforce@gmail.com

College Name: Dr. B. C. Roy Engineering, College

Branch/Specialization : Computer Application (MCA)

College ID: 120710242002
# Course Details
Course Opted: Salesforce

Instructor Name: Sriram yarrabothula

Duration: 6 Months
# Trainer Details
Trainer Name: Sriram Yarrabothula

Trainer Email ID: yarrabothulasriram@gmail.com

Trainer Designation: Salesforce Developer — RAYON TECHNOLOGY SOLUTIONS PRIVATE LIMITED
# Overall Learning
My professional summary based on the extensive Salesforce Administration and Development syllabus you provided, tailored to reflect a strong architectural and developer skill set.

During this course, I developed a comprehensive understanding of the Salesforce ecosystem, spanning both declarative Administration and programmatic Development. I gained hands-on experience in cloud architecture, complex data modeling, organizational security controls, and advanced process automation using Flows and Approval Processes. On the development side, I strengthened my technical capabilities by writing robust Apex code—mastering triggers, asynchronous processes, and comprehensive test classes. Additionally, I built responsive, modern user interfaces utilizing Lightning Web Components (LWC) and deepened my systems architecture expertise by integrating Salesforce with external platforms via REST/SOAP APIs, equipping me to design and deliver highly scalable, real-world CRM solutions.
# Projects Completed
This project involved designing and developing a Recruitment Management System (RMS) using Salesforce. It was built using core platform concepts, including structured data modeling, complex object relationships, and advanced process automation. The project focused on creating custom objects such as Job Positions, Applications, Interviews, and Offers to manage the end-to-end hiring lifecycle. I used Screen Flows to create intuitive candidate application forms and Record-Triggered Flows to automate status updates and job closures once openings were filled. Additionally, I implemented Apex Triggers and Scheduled Apex to prevent duplicate applications and send automated interview reminders. The system was designed with a strict security model, using Private OWD and a Role Hierarchy to ensure sensitive hiring data is accessible only to authorized HR staff and recruiters. This project helped me translate complex recruitment requirements into a scalable Salesforce solution while strengthening my skills in both administrative configuration and custom development.


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


#

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


