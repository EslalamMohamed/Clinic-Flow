# ClinicFlow Premium | React Front-End Demo

واجهة عربية RTL متجاوبة لإدارة العيادات والحجز الطبي، مبنية باستخدام React وVite وCSS وLucide Icons.

> **تنبيه:** هذا مشروع عرض Front-End ببيانات تجريبية، وليس نظامًا طبيًا جاهزًا للاستخدام الفعلي. لا تدخل بيانات مرضى حقيقية.

## Features
- Clinic dashboard with overview and demo statistics
- Appointment management, search, filtering, status changes and CSV export
- Patient, doctor, service and report views
- Marketing landing page and pricing plans
- Demo login screen with clinic/patient views
- Public appointment booking flow
- Patient portal for locally stored demo bookings
- Arabic RTL layout and responsive styling

## Tech Stack
- React
- Vite
- CSS
- Lucide React icons
- Browser `localStorage` for demo booking data

## Run locally
Requirements: Node.js (LTS recommended).

```bash
npm install
npm run dev
```

Open the local URL printed by Vite in your terminal.

To create a production build:

```bash
npm run build
npm run preview
```

The production files are generated in `dist/`.

## Deploy
This project can be deployed on Vercel or Netlify by importing the GitHub repository. For a Vite app, the usual build command is `npm run build` and the output directory is `dist`.

## Demo limitations
- Login is a UI demo, not secure authentication.
- Public booking data is stored in the same browser's `localStorage`; it is not sent to a clinic or shared across devices.
- Dashboard metrics and some records are sample data.
- Pricing cards are illustrative; no subscription or payment is active.
- No backend, database, email/SMS/WhatsApp notifications, or payment integration is included.

Before real-world deployment, implement a backend API, database, secure authentication and role-based authorization, server-side validation, backups, privacy/security controls, and appropriate legal/privacy review for medical data.

## Suggested repository description
Arabic RTL clinic management and appointment booking dashboard built with React, Vite and CSS. Front-end demo with public booking, patient portal, pricing page and responsive UI.

## Suggested topics
`react` `vite` `frontend` `dashboard` `clinic-management` `appointment-booking` `rtl` `arabic` `css`
