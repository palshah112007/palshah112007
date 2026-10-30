<!-- Profile README for @palshah112007 | Midnight Aurora design system -->

<div align="center">
  <img src="./assets/readme/pal-midnight-aurora-hero.svg" width="100%" alt="Pal Shah — Full-Stack Development, AWS Cloud Engineering and Applied AI" />

  <a href="https://github.com/palshah112007"><img src="https://img.shields.io/badge/GitHub-Profile-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub profile" /></a>
  <a href="https://www.linkedin.com/in/pal-shah-69b75138a"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:palshah112007@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</div>

<p align="center">
  <strong>Full-Stack Development</strong> · <strong>AWS Cloud Engineering</strong> · Applied AI
  <br />
  <sub>B.Tech Information Technology · Acropolis Institute of Technology & Research · Indore, India</sub>
</p>

<p align="center">
  <a href="#profile">Profile</a> ·
  <a href="#featured-engineering-work">Projects</a> ·
  <a href="#cloud--engineering-toolkit">Toolkit</a> ·
  <a href="#engineering-foundations">CS Foundations</a> ·
  <a href="#education--recognition">Education</a> ·
  <a href="#contact">Contact</a>
</p>

---

## Profile

I am an Information Technology undergraduate at **Acropolis Institute of Technology & Research, Indore (2024–2028)**, with a current CGPA of **8.48/10** as listed in my resume. I am working toward a career in **full-stack software development and cloud engineering**, with a particular interest in building AI-integrated applications.

I enjoy connecting product interfaces with practical engineering: shaping user flows, building web and mobile experiences, integrating APIs and authentication, handling data, and learning how to deploy and operate applications on cloud infrastructure.

**Career direction:** Full-Stack Developer · Cloud Engineer · Software Engineering internships.

**Technical interests:** React and Next.js applications · Mobile development with Expo · API design · AWS cloud services · Identity and access management · AI/LLM API integration · Data visualisation.

**Location:** Indore, Madhya Pradesh, India  
**Education:** B.Tech, Information Technology · 2024–2028  
**Languages:** Hindi and English

## Engineering approach

- **Build useful workflows:** focus on the user journey and the job the software should complete.
- **Connect the layers:** understand how the UI, API, authentication, data store, and deployment environment work together.
- **Make limitations visible:** distinguish sample data, local persistence, demo authentication, and planned architecture from fully deployed services.
- **Secure the boundary:** validate inputs, keep server credentials out of the browser, and enforce access rules in the backend.
- **Keep learning measurable:** use code, tests, CI runs, and reproducible setup instructions as evidence.

## Featured engineering work

The projects below are selected from public repositories and the supplied resume. Project summaries describe the implementation visible in the repositories; where a project is still an MVP or demo, that scope is stated directly.

### 01 · StudySprint — AI-assisted study platform

**Repository:** [palshah112007/StudySprint](https://github.com/palshah112007/StudySprint)

A gamified study-workspace MVP that brings study sessions, quizzes, flashcards, notes, tasks, progress views, and AI-assisted study workflows into one Next.js application.

- **Stack:** Next.js App Router, TypeScript, React, Tailwind CSS, Framer Motion, Recharts, OpenAI-compatible provider integration, and API routes.
- **Implemented areas documented in the repository:** AI chat and quiz-generation routes, quiz/flashcard workflows, Pomodoro focus room, notes and task modules, gamification UI, and analytics views.
- **Engineering focus:** multi-provider AI integration, streaming responses, request limits, client persistence, and modular feature routes.
- **Status and boundary:** the product requirements and technical requirements documents describe an MVP / active-development state. Local storage remains an important persistence path; full cross-device database persistence and real-time collaboration are target-state capabilities, not claims made by this profile.
- **Inspect:** [source repository](https://github.com/palshah112007/StudySprint) · [product requirements](https://github.com/palshah112007/StudySprint/blob/main/PRD.md) · [technical requirements](https://github.com/palshah112007/StudySprint/blob/main/TRD.md) · [case study](docs/case-studies/studysprint.md).

### 02 · YouTube Transcript Generator — authenticated transcript workflow

**Repository:** [palshah112007/YT-Transcript-Generator](https://github.com/palshah112007/YT-Transcript-Generator)

A React and Vite application for generating transcripts from YouTube videos, with timestamps, text export, optional user accounts, transcript history, and a server-side transcript proxy.

- **Stack:** React, Vite, JavaScript, `youtube-transcript`, optional Apify integration, Supabase Auth/PostgreSQL, and Vercel serverless support.
- **Backend evidence:** the proxy verifies Supabase bearer tokens, validates supported YouTube URL/video-ID formats, applies request-size and timeout limits, and keeps the Apify token on the server.
- **Data and access:** the supplied Supabase SQL enables row-level security for transcript history and an atomic server-side credit-spending function.
- **Quality evidence:** the repository includes Vitest tests and a GitHub Actions build/test workflow. A successful workflow run is recorded on **September 30, 2026**; see the [run](https://github.com/palshah112007/YT-Transcript-Generator/actions/runs/36679967610).
- **Status and boundary:** Supabase features are optional; the app can run in guest mode. Apify is an optional fallback, not a requirement for the free captions path.
- **Inspect:** [source repository](https://github.com/palshah112007/YT-Transcript-Generator) · [server proxy](https://github.com/palshah112007/YT-Transcript-Generator/blob/main/lib/proxy-handler.js) · [database/RLS setup](https://github.com/palshah112007/YT-Transcript-Generator/blob/main/supabase/init.sql) · [case study](docs/case-studies/youtube-transcript-generator.md).

### 03 · NexaPulse — mobile analytics interface

**Repository:** [palshah112007/nexapulse](https://github.com/palshah112007/nexapulse)

A cross-platform mobile analytics application built with React Native and Expo, with a dashboard experience, interactive visualisations, authentication flows, and theme support.

- **Resume role:** Full-Stack Developer · **Feb 2026 – Apr 2026**.
- **Stack:** React Native, Expo SDK 54, TypeScript, Expo Router, NativeWind, Firebase Authentication, AsyncStorage, and Expo Secure Store.
- **Implemented areas documented in the repository:** authentication screens, guarded navigation, dashboard and profile/settings screens, reusable UI components, chart components, and theme switching.
- **Status and boundary:** the repository includes a demo-authentication fallback when Firebase is not configured. Dashboard figures and charts are seed/mock data in the checked-in data module; they should not be read as live business analytics or measured user metrics.
- **Inspect:** [source repository](https://github.com/palshah112007/nexapulse) · [case study](docs/case-studies/nexapulse.md).

### 04 · Novamart — e-commerce storefront and Node API

**Repository:** [palshah112007/E-commerce-website](https://github.com/palshah112007/E-commerce-website) · [GitHub Pages demo](https://palshah112007.github.io/E-commerce-website/)

A React storefront with catalog browsing, product search and category filters, product detail pages, a cart, checkout flow, and an accompanying lightweight Node.js API.

- **Stack:** React, React Router, Vite, Node.js native HTTP server, and a file-backed JSON data store.
- **API evidence:** product listing, cart retrieval and mutation, and order creation endpoints; the repository workflow builds the frontend and smoke-tests the API product endpoint.
- **Important deployment distinction:** the GitHub Pages demo is static/demo mode with bundled data and browser-local cart state. The Node API and JSON data store are for local execution; the public static demo is not a hosted production backend.
- **Production boundary:** the checked-in API uses a single JSON file and does not implement multi-user authentication or a payment gateway. This is an educational full-stack project, not a production commerce platform.
- **Inspect:** [source repository](https://github.com/palshah112007/E-commerce-website) · [build/deploy workflow](https://github.com/palshah112007/E-commerce-website/blob/main/.github/workflows/build.yml) · [case study](docs/case-studies/novamart.md).

### 05 · CSV Insight Dashboard — browser-side data exploration

**Repository:** [palshah112007/CSV-Dashboard](https://github.com/palshah112007/CSV-Dashboard)

A browser-based dashboard that accepts a CSV file, parses rows, infers likely column types, calculates descriptive statistics, and creates a gallery of charts.

- **Stack:** HTML, CSS, JavaScript, and Chart.js.
- **Implemented areas visible in the source:** quoted-field CSV parsing, numeric/date/category inference, missing-value counts, descriptive statistics, data preview, formula explanations, and generated chart specifications.
- **Status and boundary:** client-side learning/project implementation with a built-in sample dataset; no backend or server-side persistence is part of the repository.
- **Resume role:** Frontend Developer · **Jan 2026**.
- **Inspect:** [source repository](https://github.com/palshah112007/CSV-Dashboard) · [case study](docs/case-studies/csv-insight-dashboard.md).

<p align="center">
  <img src="./assets/readme/pal-engineering-evidence-map.svg" width="100%" alt="Engineering evidence map linking web and mobile projects to frontend, APIs, cloud, AI integration, authentication, data and verification." />
</p>

## Cloud & engineering toolkit

The following technologies are drawn from the supplied resume and public project repositories. This is a skills inventory, not a claim that every listed service has been used in a production environment.

| Area | Selected technologies |
|---|---|
| Languages | C, C++, Java, Python, JavaScript, TypeScript |
| Frontend & mobile | HTML, CSS, React, Next.js, React Native, Expo, Vite, Tailwind CSS / NativeWind |
| Backend & APIs | Node.js, REST API routes, native Node HTTP server, serverless functions |
| AWS compute | EC2, Lambda, ECS Fargate, EKS |
| AWS storage, network & edge | S3, CloudFront, API Gateway, VPC |
| AWS identity & security | IAM, Cognito, KMS, Secrets Manager, GuardDuty |
| AWS delivery & operations | CloudFormation, SAM, CodePipeline, CodeBuild, CodeDeploy, CodeArtifact, CloudWatch, X-Ray |
| AWS AI & analytics | SageMaker, QuickSight |
| AI / LLM & voice | OpenAI API, Claude API, Gemini API, Llama, Amazon Lex, OpenRouter-compatible APIs |
| Authentication & data | Firebase Authentication, Supabase Auth, PostgreSQL, Row Level Security, localStorage |
| Tools | GitHub, VS Code, Figma |

For a deeper breakdown of AWS service responsibilities and the evidence to build for each area, see the [AWS Cloud Engineering service map](docs/engineering/aws-cloud-map.md).

## Engineering foundations

Core subjects and concepts I study and apply while building projects:

- **Programming and OOP:** C/C++/Java/Python fundamentals, object-oriented design, abstraction, encapsulation, and reusable components.
- **Data structures and algorithms:** arrays, strings, hashing, linked lists, stacks, queues, trees, graphs, searching, sorting, and problem-solving patterns.
- **DBMS:** relational data modelling, SQL, indexes, constraints, transactions, and row-level access control.
- **Computer organisation:** processor, memory, and computer architecture fundamentals.
- **Cloud fundamentals:** compute, storage, network isolation, identity, secrets, deployment pipelines, monitoring, and event-based services.
- **Application engineering:** API contracts, input validation, authentication, client/server boundaries, and testing.

## Education & recognition

### Education

**B.Tech — Information Technology**  
Acropolis Institute of Technology & Research, Indore · 2024–2028  
**CGPA:** 8.48/10 (as listed in the supplied resume)

**Class XII (CBSE):** 82% · 2024  
**Class X (CBSE):** 93.4% · 2022  
Shri Gujarati Samaj English Medium School

### Highlights

- **Winner — Yantrika 2026 RPA Pre-Hackathon**.
- **Content Lead & Anchor — App Builder Club**.
- Participant — Tech-o-Utsav Quizzards, Poster Making Competition, and Vibe Coding Competition.

### Certifications

The supplied resume lists the following credentials:

- AWS Certified AI Practitioner — Amazon Web Services (2026)
- AWS Certified Cloud Practitioner — Amazon Web Services (2026)
- Red Hat Application Development I: Programming in Java EE (AD183) — Red Hat (2025)
- Artificial Intelligence: Concepts and Techniques — NPTEL / IISc Bangalore (2025)
- Java Course — Mastering the Fundamentals — Scaler (2025)
- Additional learning: MATLAB Programming for Numerical Computation (NPTEL / IIT Madras); C, C++ & Computer Fundamentals (Spoken Tutorial / IIT Bombay); AWS Scholars Program project badges (Udacity)

<sub>Public credential IDs or issuer verification URLs were not included in the supplied resume. Add the official badge/verification links before presenting these entries as independently verified. See the <a href="docs/credentials/verification-policy.md">credential publication policy</a>.</sub>

## Current engineering focus

- Building stronger full-stack applications with reliable API and authentication boundaries.
- Deepening AWS architecture and deployment skills across compute, networking, identity, security, and observability.
- Improving AI integration with provider abstraction, input validation, latency/cost awareness, and secure server-side key handling.
- Strengthening DSA, OOP, DBMS, and core Computer Science fundamentals for SDE interviews.

## Contact

Open to relevant software engineering, full-stack, cloud, and AI-integrated application opportunities.

- **Email:** [palshah112007@gmail.com](mailto:palshah112007@gmail.com)
- **LinkedIn:** [linkedin.com/in/pal-shah-69b75138a](https://www.linkedin.com/in/pal-shah-69b75138a)
- **GitHub:** [github.com/palshah112007](https://github.com/palshah112007)

---

<p align="center">
  <sub>Build thoughtfully. Deploy responsibly. Keep learning.</sub>
</p>
