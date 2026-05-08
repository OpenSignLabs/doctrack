# DocTrack.ai

Secure document sharing platform with granular analytics, enterprise-grade protection, and team collaboration.

```
Source code coming soon!
```

## Features

### Document Management
- Upload & manage PDFs, DOCX, XLSX, PNG, JPEG, CSV (up to 50MB single / 25MB per-file batch)
- Batch uploads with progress tracking, checksums, and automatic retry
- Document version control with history and rollback
- Hierarchical folder organization with breadcrumb navigation

### Secure Sharing
- Customizable share links with password protection, expiration dates, and view limits
- Reusable link configurations (saved sharing presets)
- Download controls and right-click prevention
- Dynamic watermarking (text, logo, diagonal, corner placement, adjustable opacity)
- Screenshot protection (multi-layer: keyboard blocking, canvas protection, DOM security)
- Email OTP verification for sensitive documents

### Data Rooms
- Virtual rooms with unified access controls for multiple documents
- Nested folder hierarchy within data rooms
- Custom branding and welcome messages per data room
- QR code sharing for mobile access

### Analytics
- Real-time page-by-page engagement tracking (time, scroll depth, completion)
- Geographic visitor distribution
- Device and browser analytics
- Per-document and per-data-room analytics dashboards
- Exportable reports

### Team Collaboration
- Shared team workspaces with role-based permissions (Owner, Admin, Member)
- Team invitations via email with SMTP integration
- Per-team document and data room management


### Additional
- Dark mode with WCAG 2.1 AA accessibility compliance
- Guided onboarding tour with per-section completion persistence
- App switcher for Qik.ai product suite navigation
- Constitutional design system (OKLCH colors, Radix UI components, Inter typography)

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React 19, Vite, TypeScript, Tailwind CSS 4, Radix UI |
| Backend | Node.js, Express, TypeScript (tsx runner) |
| Database | PostgreSQL via Prisma ORM (migration-less `db push`) |
| Auth | Keycloak OIDC with JWT validation |
| Storage | AWS S3 / DigitalOcean Spaces (S3-compatible) |
| Email | Nodemailer (SMTP) |
| Testing | Jest (unit/integration), smoke tests |
| State | @tanstack/react-query |
