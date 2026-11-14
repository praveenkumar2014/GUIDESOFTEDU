# Data Model Baseline

Core entities: User, Role, Organization, Membership, LearnerProfile, InstructorProfile, EmployerProfile, Program, ProgramVersion, Module, Lesson, Cohort, CohortMembership, Application, Enrolment, LessonProgress, Assignment, Submission, Assessment, AssessmentAttempt, Certificate, Opportunity, JobApplication, Lead, Payment, PaymentEvent, SupportTicket, Notification, FileAsset and AuditEvent.

Use stable IDs, timestamps, explicit statuses, constraints and foreign keys. Model org/tenant ownership explicitly. Payment events/webhooks need idempotency keys. Certificate verification IDs must be unguessable and expose only approved public data.