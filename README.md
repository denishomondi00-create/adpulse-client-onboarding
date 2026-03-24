# Adpulse Client Onboarding System

Enterprise-grade client onboarding, qualification, project intake, milestone payment, and project transparency platform for **Adpulse Industries**.

---

## Overview

The Adpulse Client Onboarding System is a premium digital intake and project management experience built to help Adpulse Industries collect high-quality client requirements, qualify serious leads, reduce back-and-forth communication, and create a structured path from inquiry to launch and post-launch support.

This system is not just a quote form.

It is a full onboarding operating system designed to:

- capture complete client requirements
- qualify leads by service type, budget, urgency, and clarity
- educate clients on process, delivery expectations, and payment milestones
- provide a transparent client portal for progress tracking and approvals
- support internal lead review, project conversion, and delivery management
- reinforce Adpulse’s positioning as a premium, organized, and trustworthy technology partner

---

## Product Objective

Build a world-class onboarding platform that helps Adpulse Industries:

1. Understand each client’s business, goals, and challenges clearly
2. Gather all necessary files, assets, branding, and content early
3. Qualify serious projects using service selection, budget, urgency, and intent
4. Structure delivery through milestone-based payments and approval flow
5. Give clients visibility into project progress, feedback, revisions, and payments
6. Standardize internal operations from lead intake to support handoff

---

## Core Philosophy

This platform must feel like a **guided consultation**, not a generic form.

The onboarding flow should:

- feel premium and structured
- reduce client confusion
- minimize unnecessary calls and repeated questions
- filter unserious or underqualified leads gracefully
- improve project kickoff speed
- create operational clarity for both Adpulse and the client

---

## Key Business Outcomes

When implemented well, this system should:

- improve lead quality
- reduce negotiation friction
- reduce project delays caused by missing content and assets
- improve payment clarity and milestone compliance
- increase trust through visibility and process transparency
- speed up onboarding-to-delivery transition
- position Adpulse as an enterprise-capable digital delivery partner

---

## Primary Use Cases

The system should support onboarding for:

- Landing Pages
- Business Websites
- Custom CRM Systems
- Business Automation Systems
- Custom Web Apps
- Mobile Apps
- Email / SMS / WhatsApp Automation
- IT Support / ICT Services
- Digital Marketing Management
- Not Sure / Guided Recommendation path

---

## Main User Journeys

### 1. New Prospect Journey
Website CTA → `/start-project` → multi-step onboarding → submission → internal review → discovery call → proposal → milestone payment → project activation

### 2. Qualified Client Journey
Lead approved → project created → milestone plan generated → client portal invite → deposit paid → project phases begin

### 3. Active Client Journey
Portal login → track progress → upload files → review prototype → approve milestones → pay next phase → launch → support window

### 4. Internal Team Journey
Admin dashboard → review submission → assign status → qualify lead → create project → generate milestones → send portal invite → manage delivery

---

## Public Website Integration

All key CTAs across the Adpulse website should direct users into the onboarding system.

Recommended CTA destinations:

- `Start a Project`
- `Get a Quote`
- `Get My Custom Plan`
- `Request a Strategy Quote`
- `Build My System`

Recommended route:

- `/start-project`

---

## Onboarding Experience

## Structure

The onboarding flow is designed as a multi-step guided experience.

### Step 0 — Welcome / Positioning
Purpose:
- introduce the process
- set expectations
- reinforce trust and quality

Content:
- onboarding takes 5 to 8 minutes
- structured intake for better delivery
- 30-day free post-launch support
- trust metrics such as projects delivered and response time

Primary actions:
- Start My Project
- Book Discovery Call

---

### Step 1 — Service Type Selection
Purpose:
- classify the project early
- drive conditional logic for later questions

Options:
- Landing Page
- Business Website
- Custom CRM System
- Business Automation
- Custom Web App
- Mobile App
- Email / SMS / WhatsApp Automation
- IT Support & ICT Services
- Digital Marketing
- Not Sure — Help Me Decide

Each service option should communicate:
- what it is
- what business outcome it delivers
- whether it is a popular path

---

### Step 2 — Business Profile
Purpose:
- understand the client and business context

Fields:
- Full name
- Company / organization
- Business email
- Primary phone
- WhatsApp
- Industry
- Country
- City
- Current website
- Business stage

Business stage options:
- Existing business
- New business
- Internal team project
- Personal brand

---

### Step 3 — Goals and Business Problem
Purpose:
- identify the real business need behind the request

Fields:
- What challenge are you trying to solve?
- Desired outcomes
- What happens if this is not solved in the next 3–6 months?

Outcome options:
- More leads
- More sales
- Better branding
- Better client experience
- Internal efficiency
- Team productivity
- Less manual work
- Centralized data
- Better communication
- Better reporting

---

### Step 4 — Feature Scope
Purpose:
- gather client expectations without requiring technical documentation

Dynamic feature options should change based on selected service type.

Examples:
- booking systems
- M-Pesa integration
- dashboards
- reports
- admin panel
- notifications
- user accounts
- role permissions
- automation flows
- content management
- analytics

Also include:
- custom feature free text field

---

### Step 5 — Design Direction and Brand Assets
Purpose:
- collect creative input early
- reduce design revisions later

Inputs:
- logo upload
- images upload
- videos upload
- inspiration uploads
- reference websites
- visual direction

Design preference options:
- client provides brand colors
- Adpulse can be creative
- client provides typography
- Adpulse can be creative

Visual style options:
- Corporate & Professional
- Premium & Luxury
- Clean & Minimal
- Bold & Modern
- Tech-Forward
- Friendly & Warm
- Creative & Artistic

---

### Step 6 — Content Submission
Purpose:
- reduce delays caused by missing text and materials

Content inputs:
- company description
- services text
- about us text
- document uploads
- brochure uploads
- company profile uploads
- SEO or content support request

Checkboxes:
- We need help writing professional content
- We want SEO-optimized website copy

---

### Step 7 — Budget Qualification
Purpose:
- qualify seriousness
- align scope and pricing early
- reduce low-budget mismatch

Budget range options:
- KES 10K – 30K
- KES 30K – 70K
- KES 70K – 150K
- KES 150K – 300K
- KES 300K+
- Not sure yet

Optional field:
- estimated budget

#### Minimum budget rules

| Service Type | Minimum Budget |
|---|---:|
| Landing Page | KES 10,000 |
| Business Website | KES 20,000 |
| Custom CRM System | KES 70,000 |
| Business Automation | KES 50,000 |
| Web App | KES 100,000 |
| Mobile App | KES 100,000 |
| Email / SMS / WhatsApp Automation | KES 15,000 |
| IT Support / ICT Services | KES 10,000 |
| Digital Marketing Management | KES 15,000 |

If a selected range is below the required threshold for the chosen service, the system should:
- allow submission
- show a calm pricing note
- suggest reduced scope or phase one
- offer customer care guidance

---

### Step 8 — Timeline and Urgency
Purpose:
- understand deadlines and project urgency

Options:
- ASAP — Urgent
- 2–4 Weeks
- 1–2 Months
- Flexible

Additional fields:
- Event / campaign / launch context
- Preferred go-live date

Urgent projects should show:
- rush fee note depending on scope and team capacity

---

### Step 9 — Contact and Decision Workflow
Purpose:
- make communication smoother
- identify approval bottlenecks early

Fields:
- Primary email
- Secondary email
- Primary phone
- Secondary phone
- WhatsApp
- Preferred contact method
- Decision maker
- Multiple reviewers toggle

Preferred contact options:
- Email
- Phone Call
- WhatsApp
- Zoom / Google Meet

---

### Step 10 — Process and Payment Education
Purpose:
- set expectations before submission
- eliminate surprises

Content shown:
- 40% deposit
- 40% after prototype approval
- 20% on launch
- delivery phases
- free 30-day post-launch support

Required consent checkboxes:
- I understand the payment structure
- I confirm the information is accurate
- I understand timelines depend on timely feedback and approvals

---

### Step 11 — Review and Submit
Purpose:
- give the client a clean summary before final submission

Summary should include:
- service
- client and company details
- industry and location
- budget range
- timeline
- contact details
- features selected
- design preferences

Final CTA:
- Submit Project Details

---

### Step 12 — Success Screen
Purpose:
- confirm receipt
- reduce uncertainty
- guide next actions

Show:
- response time
- internal review steps
- discovery call prompt
- WhatsApp contact
- email contact
- direct phone number

---

## Smart Conditional Logic

The system should adapt based on what the client selects.

### If the client selects “Not Sure”
Route them through a lighter discovery path:
- what are you trying to achieve?
- do you need visibility, automation, sales, internal efficiency, or branding?
- what is your estimated budget?

Then recommend the most suitable service internally.

### If the client selects Website / Landing Page
Prioritize:
- design inputs
- content needs
- pages
- SEO
- conversion goals
- forms
- booking systems
- branding

### If the client selects CRM / Automation
Prioritize:
- workflow questions
- pain points
- team usage
- reports
- approvals
- integrations
- internal departments
- roles / permissions

### If the client selects IT Support
Ask for:
- number of staff
- onsite or remote support
- devices and systems
- support frequency
- training needs
- network or infrastructure needs

### If the client selects Digital Marketing
Ask for:
- channels
- ad platforms
- current presence
- campaign goals
- reporting expectations
- budget expectations

---

## Client Portal

The client portal is a major differentiator for Adpulse.

It should give each approved client a secure environment to:

- follow project progress
- review milestones
- upload additional files
- leave comments
- approve deliverables
- view payment status
- access support after launch

### Portal Sections

#### 1. Overview
- Project name
- Service type
- Current phase
- Progress bar
- Latest update
- Next milestone
- Account manager

#### 2. Timeline
- Discovery
- Strategy approved
- Wireframes ready
- Prototype review
- Development
- Testing
- Launch
- Support end date

#### 3. Files
- Client uploads
- Adpulse uploads
- Brand assets
- Prototype files
- Final deliverables
- Contracts and invoices

#### 4. Feedback and Comments
- milestone-based comment threads
- approval actions
- revision requests
- version history

#### 5. Payments
- agreed budget
- milestone split
- paid / pending status
- receipts
- Pay Now button via Paystack

#### 6. Meetings and Communication
- discovery call links
- meeting history
- preferred contact method
- support contact buttons

#### 7. Support
- support window countdown
- issue submission
- fix requests
- support status

---

## Admin Dashboard

The admin dashboard powers the internal operating system for lead review, project qualification, and delivery management.

### Admin Features
- view all submissions
- filter by service type
- filter by budget
- filter by urgency
- see missing assets or content
- assign account manager
- add internal notes
- change lead stage
- convert lead to active project
- create milestones
- trigger payment link
- invite client to portal
- monitor project progress

### Recommended Lead Stages
- New Lead
- Needs Review
- Clarification Needed
- Qualified
- Proposal Sent
- Deposit Pending
- Active Project
- On Hold
- Completed
- Support Window
- Closed

### Recommended Admin Views
- lead list
- kanban board by stage
- urgent leads
- budget summary
- service type breakdown
- missing asset alerts
- payment status overview
- client communication log

---

## Payment System

The platform uses milestone-based billing and Paystack integration.

### Standard Payment Structure
- 40% deposit to begin
- 40% after prototype approval
- 20% on final launch

### Payment Flow
1. Lead is reviewed internally
2. Lead is approved and converted to a project
3. Three milestone records are created automatically
4. Client receives portal invite
5. Client pays first milestone through Paystack
6. Secure webhook confirms payment
7. Project moves into active phase
8. Next milestone becomes payable at the correct stage
9. Final milestone is paid before or at launch

### Critical Rule
Never rely on frontend-only payment success.
Use secure server-side webhook verification from Paystack.

### Payment UI Should Show
- milestone title
- amount due
- what the payment unlocks
- receipt or invoice reference
- current payment state

### Payment States
- Unpaid
- Payment Link Sent
- Paid
- Failed
- Overdue

---

## Post-Submission Automation

Immediately after onboarding submission, the system should:

- save lead data in the database
- save uploaded asset references
- notify admin
- send confirmation email to client
- generate internal lead card
- compute lead quality score

### Confirmation Email Should Include
- thank you message
- submission summary
- selected service type
- budget range
- timeline
- next steps
- expected response time
- optional discovery call link

### Internal Notification Should Include
- lead name
- company
- service type
- budget
- urgency
- completion score
- missing items if any

---

## Lead Qualification Logic

Each lead should receive an internal lead score based on:

- budget fit
- urgency
- clarity of goals
- completeness of assets
- completeness of content
- seriousness signals
- alignment with minimum service thresholds

This helps prioritize faster follow-up for the strongest opportunities.

---

## Missing Content and Scope Controls

This platform should also solve operational issues that most agencies ignore.

### Missing Content Flagging
If a website lead provides no copy, no images, and no company information:
- mark as content-blocked internally

### Approval Bottleneck Handling
Ask early:
- who is the final decision-maker?
- will multiple reviewers be involved?

### Revision Governance
Support milestone-based reviews rather than endless global changes.

### Scope Change Handling
Include a project portal action such as:
- Request Scope Change

This should notify the team and potentially trigger a requote.

### Support Countdown
After launch, show support time remaining:
- support days left
- support expiry date

---

## Recommended Tech Stack

## Frontend
- Next.js (App Router)
- TypeScript
- Tailwind CSS
- shadcn/ui
- Framer Motion

## Forms and Validation
- React Hook Form
- Zod
- Zustand for draft state or local multi-step state

## Backend
- Next.js server actions / route handlers for MVP
- optional migration to NestJS for larger internal ops scale

## Database
- PostgreSQL
- Prisma ORM

## Authentication
- NextAuth or Clerk

## File Storage
- Cloudinary for media
- S3-compatible storage for documents and large files
- direct-to-cloud uploads via signed URLs

## Payments
- Paystack
- secure webhook processing

## Notifications
- Resend or SendGrid for email
- optional WhatsApp API later
- optional SMS integration later

## Monitoring and Analytics
- Sentry
- PostHog or Plausible

---

## Recommended Data Model

Below is a practical relational structure for the onboarding system, admin dashboard, and client portal.

### Client
- id
- fullName
- companyName
- emailPrimary
- emailSecondary
- phonePrimary
- phoneSecondary
- whatsapp
- preferredContactMethod
- country
- city
- createdAt

### Lead
- id
- clientId
- serviceType
- leadScore
- budgetRange
- estimatedBudget
- urgency
- source
- status
- submissionJson
- createdAt

### Project
- id
- clientId
- leadId
- projectName
- serviceType
- agreedBudget
- currentPhase
- progressPercent
- scopeJson
- designPrefsJson
- contentStatus
- supportEndsAt
- createdAt

### Milestone
- id
- projectId
- title
- description
- amount
- dueDate
- status
- isApproved
- isPaid
- paymentProviderRef

### FileAsset
- id
- projectId
- uploadedBy
- type
- label
- url
- mimeType
- createdAt

### CommentThread
- id
- projectId
- milestoneId
- authorRole
- message
- attachmentUrl
- createdAt

### Proposal
- id
- leadId
- projectId
- version
- scopeSummary
- timelineEstimate
- priceSummary
- status

### ActivityLog
- id
- projectId
- actor
- eventType
- metadataJson
- createdAt

---

## Suggested Folder Structure

```bash
app/
  (marketing)/
    page.tsx
    services/
    pricing/
    work/
    about/
    blog/
  start-project/
    page.tsx
    success/
      page.tsx
  portal/
    login/
      page.tsx
    [projectId]/
      page.tsx
      files/
        page.tsx
      payments/
        page.tsx
      feedback/
        page.tsx
  admin/
    page.tsx
    leads/
      page.tsx
      [leadId]/
        page.tsx
    projects/
      page.tsx
      [projectId]/
        page.tsx
    payments/
      page.tsx
    clients/
      page.tsx
    settings/
      page.tsx

components/
  onboarding/
  portal/
  admin/
  ui/

lib/
  validations/
  services/
  paystack/
  storage/
  email/
  auth/

prisma/
  schema.prisma
Design System

The onboarding example you provided uses a premium dark interface with gold accents, muted neutrals, and a supporting blue accent. The color palette strongly supports an enterprise feel.

Extracted Design Colors
Core Background and Surfaces
#0A0A0F — primary background
#111118 — surface
#18181F — elevated surface
Borders
#2A2A35 — standard border
#3A3A48 — high-contrast border
Gold Brand Accent
#C9A84C — primary gold
#E8C97A — light gold
#8A6E30 — dim gold
Blue Accent
#4F8EF7 — primary accent blue
#2A5AB0 — dim accent blue
Typography Neutrals
#F0EDE8 — primary text
#A8A49E — mid text
#6B6760 — dim text
Status Colors
#2ECC71 — success
#F39C12 — warning
#E74C3C — error
Recommended Design Tokens
export const COLORS = {
  bg: "#0A0A0F",
  surface: "#111118",
  surfaceHigh: "#18181F",
  border: "#2A2A35",
  borderHigh: "#3A3A48",
  gold: "#C9A84C",
  goldLight: "#E8C97A",
  goldDim: "#8A6E30",
  accent: "#4F8EF7",
  accentDim: "#2A5AB0",
  text: "#F0EDE8",
  textMid: "#A8A49E",
  textDim: "#6B6760",
  success: "#2ECC71",
  warning: "#F39C12",
  error: "#E74C3C",
};
Typography Direction

The example uses a premium editorial-meets-product interface approach.

Recommended Fonts
Playfair Display for serif headlines
DM Sans for UI and body text
DM Mono for step indicators, system labels, and metadata
Design Character
premium
sharp
technical
elegant
enterprise-friendly
Kenya-rooted with global polish
UX Principles

This product should follow these design and experience rules:

1. One decision per screen

Avoid clutter and reduce fatigue.

2. Visual selectors over generic dropdowns

Use service cards, chips, toggles, and budget selectors.

3. Save and continue later

Persist progress in local storage and optionally via secure resume link.

4. Progressive disclosure

Only show the right questions at the right time.

5. Make “Be Creative” feel premium

It should not feel like the client is skipping work. It should feel like they are trusting Adpulse’s design leadership.

6. Keep the client oriented

Always show:

current step
total steps
progress
what comes next
Recommended MVP Scope
Phase 1 — High-Value MVP

Build first:

multi-step onboarding form
service-based conditional logic
validation rules
file uploads
submission storage
confirmation email
admin dashboard for lead review
lead-to-project conversion
basic client portal overview
milestone creation
first Paystack deposit flow
Phase 2 — Strong Upgrade

Add:

proposal builder
save and resume by magic link
comment threads
milestone approvals
automated status emails
payment reminders
receipts
internal assignment and notes
Phase 3 — Enterprise Expansion

Add:

role-based admin permissions
real-time portal comments
support ticketing
advanced lead scoring
WhatsApp updates
analytics dashboards
satisfaction and support surveys
Development Priorities
Sprint 1
design system
onboarding shell
progress system
basic step flow
validation schemas
Sprint 2
service logic
file upload architecture
database schema
submission API
Sprint 3
admin dashboard
lead detail pages
project conversion
milestone generation
Sprint 4
client portal overview
files and timeline
payment page
Paystack integration
confirmation emails
Sprint 5
comments and approvals
support module
QA
analytics
launch polish
Security and Reliability Notes
use signed upload URLs for file uploads
never store raw payment trust on the frontend
use Paystack webhooks for payment confirmation
enforce auth for admin and client portals
separate admin and client roles clearly
log major lifecycle actions in activity logs
validate all onboarding inputs server-side as well
Product Standard

When this system is complete, a client should feel:

I am being guided professionally
this team understands my business
the process is structured and transparent
the pricing is serious and clear
I know what happens next
I can follow progress without chasing anyone
Adpulse is organized, modern, and trustworthy

That is the benchmark.

Final Recommendation

Build this as a serious internal operating system, not just a prettier quote form.

The full value comes from the complete chain:

Website CTA → Guided onboarding → Internal qualification → Proposal → Milestone payment → Client portal → Delivery supervision → Launch → Support

That is how Adpulse stops looking like a standard agency and starts operating like a premium digital transformation partner.

Suggested Project Name

Adpulse Client Onboarding System
Alternative internal names:

Adpulse Start Project Platform
Adpulse Project Intake OS
Adpulse Client Portal & Onboarding Suite
Maintained By

Adpulse Industries
Nairobi, Kenya
Email: adpulseindustries@gmail.com
Phone: +254 769 968 696
