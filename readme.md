# GovAssist

A modern **Government Assistance and Document Management System** built for municipalities, barangays, and local government units. GovAssist streamlines citizen assistance applications, document submissions, staff review workflows, claim scheduling, and administrative reporting.

---

# Overview

GovAssist digitizes public service processes by allowing citizens to apply online for government assistance programs, upload required documents, and track application progress. Staff can review requests, verify files, approve or reject submissions, and schedule claims. Administrators gain dashboards, analytics, and full system control.

---

# Tech Stack

### Frontend

* Next.js (App Router)
* TypeScript
* Tailwind CSS
* shadcn/ui

### Backend

* Next.js API Routes / Server Actions
* Prisma ORM

### Database

* PostgreSQL

### Authentication

* Auth.js / NextAuth

### File Uploads

* UploadThing

### Deployment

* Vercel

---

#Features

# Citizen Portal

* Register / Login
* Edit profile
* Browse assistance programs
* Submit applications
* Upload required documents
* Track status in real-time
* Receive notifications
* Download approval or claim files
* View schedules

# Staff Portal

* Review incoming applications
* Verify uploaded documents
* Approve / reject requests
* Add remarks
* Schedule claims
* Notify applicants
* Search and filter records

# Admin Portal

* Dashboard analytics
* Manage users
* Manage assistance programs
* Manage requirements
* Export reports
* Audit logs
* System settings

---

# Application Status Flow

```text id="0u3g2x"
Pending → Reviewing → Approved / Rejected → Claimed
```

---

# Database Tables

* users
* assistance_programs
* applications
* documents
* notifications
* schedules
* audit_logs

---

#Security Features

* Role-based access control
* Password hashing
* Input validation
* Protected routes
* File upload restrictions
* Audit trails
* Secure environment variables

---

# Project Structure

```text id="o5n1dk"
app/
  (public)/
  citizen/
  staff/
  admin/
  api/

components/
lib/
prisma/
hooks/
types/
public/
```

---

# Installation

## 1. Clone Repository

```bash id="l4l19y"
git clone https://github.com/yourusername/govassist.git
cd govassist
```

## 2. Install Dependencies

```bash id="7p4ccp"
npm install
```

## 3. Setup Environment Variables

Create a `.env` file:

```env id="9q9j5i"
DATABASE_URL=
NEXTAUTH_SECRET=
NEXTAUTH_URL=
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=
```

## 4. Run Prisma Migration

```bash id="0k6mrf"
npx prisma migrate dev
```

## 5. Seed Database (Optional)

```bash id="08e4hu"
npx prisma db seed
```

## 6. Run Development Server

```bash id="0ub6i9"
npm run dev
```

Visit:

```text id="qkwx9t"
http://localhost:3000
```

---

# Deployment

Recommended platform: **Vercel**

### Steps:

1. Push project to GitHub
2. Import repository into Vercel
3. Add environment variables
4. Deploy

---

# Future Enhancements

* QR Code Claim Verification
* SMS Notifications
* Email Notifications
* OCR Document Scanning
* AI Assistant Chatbot
* Multi-language Support
* Digital Signatures

---

# Demo Accounts

```text id="it7w4f"
Admin:
admin@govassist.local

Staff:
staff@govassist.local

Citizen:
citizen@govassist.local
```

---

# Contributors

* Your Name
* Team Members

---

# License

This project is for educational, thesis, and government digitization purposes.

---

# Thesis Title Example

**GovAssist: A Web-Based Government Assistance and Document Management System**

---
