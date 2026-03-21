# Privacy Policy — MVP Builder

**Version:** 1.1
**Last updated:** March 2026

---

## 1. Who We Are

MVP Builder is operated by:

Dejan Potocnik
Alpsteinstrasse 3
8570 Weinfelden
Schweiz

Email: energetekk@proton.me
Website: https://mvpbuilder.io

Dejan Potocnik is the data controller within the meaning of the EU General Data Protection Regulation (GDPR) and the Swiss Federal Act on Data Protection (FADP / DSG).

Switzerland is recognized by the European Commission as providing an adequate level of data protection. GDPR applies additionally for users residing in the EU.

---

## 2. What Data We Collect and Why

### 2.1 Application Form (mvpbuilder.io/pipeline)

**Data collected:**
- First name or nickname
- Email address
- Self-reported skill level (beginner / intermediate / professional)
- Self-reported project phase
- Project description and sprint goal (free text)
- Time zone (auto-detected from browser settings — no location tracking)
- Timestamp of submission

**Purpose:** Reviewing your application, assigning you to the right tier (Bronze/Silver/Gold), communicating our decision.

**Legal basis:** Art. 6(1)(b) GDPR (steps prior to entering a contract) and Art. 6(1)(a) GDPR (consent through voluntary application).

**Retention:** Rejected applications: 6 months. Accepted applications: duration of sprint plus 2 years (for quality and feedback purposes).

---

### 2.2 Dashboard Use During the Sprint

**Data collected:**
- Login timestamps (`last_login_at`)
- Check-in entries (date, status)
- Submitted proof-of-work evidence (links, screenshots, or videos)
- Progress data (current sprint day, tier assignment)

**Purpose:** Running the sprint, detecting inactivity (to notify you of missed milestones), confirming sprint completion.

**Legal basis:** Art. 6(1)(b) GDPR (performance of a contract).

**Retention:** 2 years after sprint end, then deleted or anonymized.

---

### 2.3 Email Communication

**Data collected:**
- Email address
- Open and click tracking (if tracked by our email provider — see Section 3.2)
- Content of incoming messages (when you reply directly to us)

**Purpose:** Sending daily prompts, milestone reminders, inactivity alerts, sprint completion notifications, and responding to inquiries.

**Legal basis:** Art. 6(1)(b) GDPR (performance of a contract) for transactional emails. Art. 6(1)(a) GDPR (consent) for optional non-transactional communications.

**Retention:** As described in 2.1 and 2.2 above. Direct email correspondence: 2 years.

---

### 2.4 Technical Access Data (Server Logs)

When you visit our website, the following data is automatically collected by our hosting provider:

**Data collected:**
- IP address (anonymized within 24 hours)
- Browser type and operating system
- Requested URL
- Date and time of access
- Referrer URL (where you came from)

**Purpose:** Technical operation, error resolution, security.

**Legal basis:** Art. 6(1)(f) GDPR (legitimate interest in secure website operation).

**Retention:** 7 days, then automatic deletion.

---

### 2.5 Analytics (Vercel Analytics)

We use Vercel Web Analytics for anonymized usage statistics.

**What Vercel Analytics does not do:**
- No cookie tracking
- No browser fingerprinting
- No personally identifiable data

**What is collected:**
- Anonymized page views
- Device type (desktop/mobile), country-level location (not precise)
- Referrer source

**Legal basis:** Art. 6(1)(f) GDPR (legitimate interest in anonymized usage analysis). Because no personal data is processed, no cookie consent is required.

---

## 3. Third-Party Providers and Data Transfers to the USA

We use the following external service providers to operate MVP Builder. These providers process data on our behalf as data processors under Art. 28 GDPR. We have entered into a Data Processing Agreement (DPA) with each of them.

---

### 3.1 Supabase (Database Hosting)

**Provider:** Supabase Inc., 970 Toa Payoh North #07-04, Singapore 318992
**Server location:** Primarily USA (AWS us-east-1)
**Data processed:** All data described in Sections 2.1 and 2.2 (user profile, application data, check-ins, progress data, timestamps)
**Purpose:** Database operation, authentication, dashboard backend
**Legal basis for transfer to third country:** EU Standard Contractual Clauses (SCCs) per Commission Implementing Decision (EU) 2021/914
**Privacy information:** https://supabase.com/privacy
**DPA:** https://supabase.com/legal/dpa

---

### 3.2 Resend (Email Delivery)

**Provider:** Resend, Inc., USA
**Server location:** USA
**Data processed:** Email address, first name, tier assignment, daily prompt content, notification messages
**Purpose:** Sending all transactional emails (acceptance, rejection, daily prompts, milestone reminders, sprint completion)
**Legal basis for transfer to third country:** EU Standard Contractual Clauses (SCCs)
**Privacy information:** https://resend.com/privacy
**DPA:** https://resend.com/legal/dpa

---

### 3.3 Vercel (Hosting and Deployment)

**Provider:** Vercel Inc., 440 N Barranca Ave #4133, Covina, CA 91723, USA
**Server location:** USA (primary), with global CDN
**Data processed:** IP addresses on page visits, request logs, deployment logs
**Purpose:** Hosting the website and API endpoints
**Legal basis for transfer to third country:** EU Standard Contractual Clauses (SCCs); Vercel is also certified under the EU-US Data Privacy Framework
**Privacy information:** https://vercel.com/legal/privacy-policy
**DPA:** https://vercel.com/legal/dpa

---

### 3.4 Stripe (Payment Processing — from Cohort #2 onward)

This section applies once paid cohorts are available.

**Provider:** Stripe, Inc., 510 Townsend Street, San Francisco, CA 94103, USA
**Data processed:** Payment information (credit card / bank account), billing address, email
**Purpose:** Payment processing for paid cohorts
**Note:** Stripe acts as an independent controller for payment data. We do not store or have access to full payment instrument details.
**Privacy information:** https://stripe.com/privacy
**DPA:** https://stripe.com/legal/dpa

---

## 4. Your Rights

### 4.1 Rights Under GDPR (EU Residents) and FADP (Swiss Residents)

**Right of access:** You can request a copy of the personal data we hold about you.

**Right to rectification:** You can request correction of inaccurate or incomplete data.

**Right to erasure:** You can request deletion of your data, unless legal retention obligations apply. Just email us at energetekk@proton.me — we will delete your account and all associated data within 30 days.

**Right to restriction of processing:** You can request that we limit processing to storage only.

**Right to data portability:** You can request your data in a machine-readable format.

**Right to object:** You can object to processing based on our legitimate interests.

**Right to withdraw consent:** Where processing is based on your consent, you can withdraw it at any time with effect for the future.

### 4.2 How to Exercise Your Rights
Send an email to: energetekk@proton.me

**Response time:** Within 30 days (GDPR deadline). Usually sooner.

### 4.3 Right to Lodge a Complaint
You have the right to lodge a complaint with a data protection supervisory authority:

**Switzerland:**
Federal Data Protection and Information Commissioner (FDPIC / EDÖB)
https://www.edoeb.admin.ch
Feldeggweg 1, CH-3003 Bern

**European Union:** The supervisory authority in your country of residence.

---

## 5. Data Security

- All connections to mvpbuilder.io are encrypted with TLS/SSL.
- We do not store passwords — authentication uses Magic Links (time-limited, single-use login links).
- Database access is secured through Row-Level Security (RLS) in Supabase — each user can only access their own data.
- We do not store payment instrument data ourselves — this is handled directly by Stripe.

No system is 100% secure. In the event of a data breach, we will notify affected users as quickly as possible and, where legally required, report to the relevant supervisory authority within 72 hours.

---

## 6. Cookies and Tracking

**Cookies:** We use only technically necessary cookies for session management (login state). No third-party tracking cookies are used.

**Analytics:** We use Vercel Analytics — a cookieless analytics solution with no personal identification (see Section 2.5).

**UTM parameters:** When you arrive via a link containing UTM parameters (e.g., ?utm_source=reddit), we store these anonymously to understand which channels bring visitors. No linking to individual identities.

---

## 7. Minors

MVP Builder is intended exclusively for persons aged 18 and older. We do not knowingly collect data from individuals under 18. If you become aware that a minor has submitted data to us, please contact us.

---

## 8. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. The current version is always available at mvpbuilder.io/privacy. Active users will be notified by email of material changes. The date of last update is shown at the top of this document.

---

## 9. Contact for Privacy Questions

**Email:** energetekk@proton.me
**Subject line:** "Privacy request — [your inquiry]"
**Response time:** Typically within 48 hours

---

*MVP Builder — mvpbuilder.io*
*Data controller: Dejan, Switzerland*
