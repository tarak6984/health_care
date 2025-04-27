# HealthCare Management System

<div align="center"> 
  <br /> 
  <img src="https://github.com/adrianhajdin/healthcare/assets/151519281/a7dd73b6-93de-484d-84e0-e7f4e299167b" alt="Project Banner" />
  <br />  
  <div> 
    <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="nextjs" /> 
    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="typescript" /> 
    <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="tailwindcss" /> 
    <img src="https://img.shields.io/badge/Appwrite-FD366E?style=for-the-badge&logo=appwrite&logoColor=white" alt="appwrite" /> 
    <img src="https://img.shields.io/badge/Open%20Source-✔️-brightgreen?style=for-the-badge" alt="open-source" />
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge" alt="license" />
  </div> 
</div> 

---

## Table of Contents

1. [Introduction](#introduction)  
2. [Tech Stack](#tech-stack)  
3. [Features](#features)  
4. [Quick Start](#quick-start)  
5. [Snippets](#snippets)  
6. [Assets](#assets)  
7. [License](#license)

---

## Introduction

A healthcare patient management application that allows patients to register, book, and manage their appointments with doctors.  
It features administrative tools for scheduling, confirming, and canceling appointments, along with SMS notifications, all built with Next.js.

For community help and discussions, join [our Discord](https://discord.com/invite/n6EdbFJ).

---

## Tech Stack

- **Next.js** — React framework for production
- **TypeScript** — Static type checking
- **TailwindCSS** — Utility-first CSS framework
- **Appwrite** — Backend as a service
- **ShadCN** — UI components
- **Twilio** — SMS notifications
- **Sentry** — Application monitoring

---

## Features

- 🧑‍⚕️ **Patient Registration**  
- 📅 **Book Appointments with Doctors**  
- 🛠️ **Admin Management for Appointments**  
- 📩 **SMS Appointment Confirmations**  
- 📱 **Fully Responsive Design**  
- 📂 **Secure File Uploads with Appwrite Storage**  
- 🛡️ **Performance Monitoring with Sentry**  
- 🔥 **Clean Code Structure & Reusability**  

---

## Quick Start

### Prerequisites

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

### Clone the Repository

```bash
git clone https://github.com/adrianhajdin/healthcare.git
cd healthcare
```

### Install Dependencies

```bash
npm install
```

### Set Environment Variables

Create a `.env.local` file in the root:

```env
# Appwrite Credentials
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=
API_KEY=
DATABASE_ID=
PATIENT_COLLECTION_ID=
APPOINTMENT_COLLECTION_ID=
NEXT_PUBLIC_BUCKET_ID=

NEXT_PUBLIC_ADMIN_PASSKEY=111111
```

Replace the placeholders with your actual Appwrite credentials.

### Run the Development Server

```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## Snippets

Essential configurations and snippets (already included in the repository):

- `tailwind.config.ts` — TailwindCSS custom configuration
- `globals.css` — Global styling
- `utils.ts` — Helper functions
- `validation.ts` — Form validation schemas
- `types/` — TypeScript types
- `constants/` — Application constants

---

## Assets

All public assets used in the project are available [here](https://drive.google.com/file/d/1yGvWFeSaH1-_aiQ1gejT23lqz5979RKB/view?usp=sharing).

---

## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.  
Feel free to use, modify, and distribute for both personal and commercial purposes!

---

# 🚀 Happy Coding!


