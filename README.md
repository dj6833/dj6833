# Hi there! Thanks for checking my profile. 👋

## 🚀 Featured Project: University Management System

During a structured career break, I used the time to upskill in modern open-source web technologies and cloud-native architectures. I implemented and built upon a decoupled, full-stack University Management system to serve as an ongoing testing ground for modern coding languages, infrastructure toolsets, and deployment processes.

### 🛠️ Architecture & Tech Stack

* **Front-End:** React, Vite, Refine (Enterprise CRUD framework), TanStack (State & Data Management), Tailwind CSS, Zod schema validation
* **Back-End:** Node.js (Express) & Python (FastAPI) microservices
* **Database & ORM:** PostgreSQL (Neon Serverless), Drizzle-ORM, normalised relational schemas with custom variable-driven data seeding scripts
* **Cloud, DevOps & Security:** Vercel, Railway & Render cloud hosting, GitHub Actions CI/CD pipelines orchestrating a multi-stage Git-flow lifecycle (Local -> Staging automation with Playwright regression testing -> Production promotion), Docker containerisation, Site24x7 monitoring, Better-auth secure session handling, Arcjet protection, Cloudinary asset management

### 🔐 Site Access
**If you are a hiring manager or recruiter looking to view the system** please follow the dedicated **project link** available in the header of my CV. This link will open the site and pre-populate the login screen, enabling access as a student-profile user.

To protect database limits and system states, **new user registration has been disabled on the public landing page**. 

The majority of create, update, and delete actions are restricted to system administrators. Under the student profile, you can freely browse records, view dynamically recommended classes, and test interactive class enrolment workflows. 

*(Note: The underlying site data is reset regularly, rolling any changes back to a clean testing baseline).*

### ⚙️ Current System Features

#### Application Interface & Workflows

* **Role-Based Provisioning:** Supporting distinct views and permissions for [Admin], [Lecturer] and [Student] profiles
* **Operational Dashboard:** Main landing interface tracking system metrics and recent activity  
* **Department Management:** Ability to provision and maintain University Departments, and view associated data
* **Subject Management:** Maintain academic modules assigned directly to parent Departments
* **Staff Listing:** View a list of university lecturers and associated data
* **Class Details:** Classes teach a **Subject**; Manage Class instances, including lecturer assignments and enforcing max-capacity validation rules
* **Student Enrolment:** *My Classes* allows students to manage their academic schedules by joining or leaving Classes
* **Algorithmic Class Recommendations:** Dynamic *Recommended Classes* discovery panel driven by a Python data script that identifies and suggests popular classes based on peer enrolment trends
* **Automated System Health Checks:** To optimise cloud resources, backend services automatically scale down during periods of inactivity. A custom health dashboard monitors endpoint availability, handling server cold starts and alerting users to initialisation states

#### Architecture & Pipeline Operations

* **Lightweight Backlog Management:** Project tickets managed with a structured agile-aligned backlog spreadsheet tracking issue types, priority tags, deployment categories, and execution status
* **Multi-Stage CI/CD Git-Flow Workflow:** Automated delivery pipelines where merging feature branches into the Staging branch triggers immediate, isolated environment builds for pre-production quality checks
* **Automated Regression Frameworks:** Playwright scripts triggered directly by staging branch updates, executed via GitHub Actions runner containers to validate system stability before production promotion
* **Configurable Data Seeding:** A custom data seeding engine driven by isolated control variables to programmatically populate target database environments with realistic, relational sample sets for load-testing scenarios
* **Database-as-Code:** Automated schema tracking and structural database migrations executed natively via Drizzle-ORM in parallel with backend application updates

### 📋 Project Backlog & Future Roadmap
To simulate an active, iterative product lifecycle, I maintain a development backlog targeting bug fixes, enhancements, and longer-term architectural planning. I've shared some backlog items below to provide an outline of the potential project roadmap.

| Category | Task | Candidate Stack & Tools |
| :--- | :--- | :--- |
| **UX & Frontend** | **Mobile-View Optimisation:** Resolve out-of-place UI elements in mobile viewports | Tailwind CSS, shadcn/ui |
| **UX & Frontend** | **Onboarding:** Add a first-visit welcome process to introduce new site users following login | React, Refine |
| **UX & Frontend** | **Reactive UI Mutations:** Implement real-time state synchronisation to allow active pages to respond instantly to data layer modifications | TanStack, WebSockets |
| **Core Feature** | **User Login & Profile Management:** Build Forgot Password workflow; enable SSO login providers; allow authenticated users to maintain their personal profile & logon details | React, Zod, Better-auth |
| **Core Feature** | **Timetable Scheduling:** Build an admin service that auto-generates a conflict-free weekly class schedule matching lecturer availability | Serverless Functions / Python |
| **Core Feature** | **Display Schedules:** Present personalised student and teacher views displaying their weekly class timetables; introduce notification system to alert students to any class timetable clashes | React, Refine |
| **Automation & Background Tasks** | **Asynchronous Document Engine:** Implement background processing to generate automated student welcome packs and PDFs containing personalised timetables | Serverless Functions / Celery / Redis |
| **Reporting** | **Reporting & Metrics Layer:** Integrate a reporting panel to aggregate system data and provide data-driven insights | Reporting stack TBC |
| **Testing** | **Test Coverage Expansion:** Extend frontend and introduce backend automated test coverage | Playwright, Vitest, PyTest |
| **Infrastructure** | **Distributed Caching Infrastructure:** Implement a caching tier ahead of the database to optimize read-heavy routes | Redis, Neon PostgreSQL |
| **Architecture** | **Next-Gen Frontend Migration:** Evaluate the trade-offs of migrating the as-is client-rendered application into a server-rendered model | Next.js (App Router), React Server Components (RSCs) |

### 📂 Explore the Source Code
The complete implementation comprises the following three repositories:
*   **[Frontend Application](https://github.com/dj6833/university-frontend)** - React
*   **[Backend Services - Primary](https://github.com/dj6833/university-backend)** - Node.js, Database Migrations
*   **[Backend Services - Analysis](https://github.com/dj6833/university-backend-analysis-services)** - Python

---

### 📬 How to reach me
For a detailed technical walkthrough of the site, or if you are sourcing for a hands-on technical or analytical role, please contact me directly using the details available on my CV.
