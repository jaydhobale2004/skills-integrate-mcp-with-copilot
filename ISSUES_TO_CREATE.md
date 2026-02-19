# Proposed Issues to Create

This file contains proposed GitHub issues to implement features inspired by `bq-educacion/academy-manager`.

---

## 1) Migrate to GraphQL + Apollo
**Description:** Replace current REST endpoints with a GraphQL API (or add GraphQL alongside REST) and generate TypeScript types for clients using Apollo.
**Acceptance Criteria:** GraphQL server exposing activities, students, groups; generated types; basic query/mutation examples.
**Labels:** enhancement, backend
**Estimate:** medium

---

## 2) Add Next.js + TypeScript frontends
**Description:** Replace static frontend with Next.js + TypeScript apps for mobile (`front_m`) and back-office (`front_bo`) views, integrating with Apollo client.
**Acceptance Criteria:** Two Next.js apps scaffolded; development and build scripts; example page fetching activities.
**Labels:** frontend, enhancement
**Estimate:** large

---

## 3) Back-office CRUD (students/groups/instructors/centers)
**Description:** Implement admin UI and corresponding API endpoints for create/read/update/delete of core entities (students, groups, instructors, centers).
**Acceptance Criteria:** CRUD pages and API operations; forms and validation; role-restricted access.
**Labels:** feature, backend, frontend
**Estimate:** large

---

## 4) Tables with sorting, pagination and advanced search
**Description:** Add table components supporting column sorting, server-side pagination, and an advanced search UI.
**Acceptance Criteria:** Table component; API supports pagination and ordering; search filters working.
**Labels:** frontend, enhancement
**Estimate:** medium

---

## 5) Create/Edit modals and detailed entity pages
**Description:** Provide modal dialogs for quick create/edit actions and dedicated detail pages for each entity.
**Acceptance Criteria:** Modals for create/edit; detail pages for students/groups showing related data.
**Labels:** frontend
**Estimate:** medium

---

## 6) Authentication & authorization (JWT + Google OAuth)
**Description:** Add authentication using JWT tokens, support Google OAuth sign-in, and protect admin routes.
**Acceptance Criteria:** Login flow, JWT issuance and verification, protected admin pages.
**Labels:** security, backend, frontend
**Estimate:** medium

---

## 7) Real-time updates / subscriptions (WebSockets)
**Description:** Implement real-time updates for participant lists and dashboards using GraphQL subscriptions or WebSocket messages.
**Acceptance Criteria:** Clients receive updates when participants sign up/unregister without manual refresh.
**Labels:** feature, realtime
**Estimate:** medium

---

## 8) Dockerize project (Dockerfile, docker-compose)
**Description:** Add Dockerfiles and a `docker-compose.yml` to run the API and frontend services for local development and testing.
**Acceptance Criteria:** `docker-compose up` brings services up; docs updated.
**Labels:** devops
**Estimate:** small

---

## 9) i18n / translations
**Description:** Add internationalization support (messages JSON), and locale switching for the frontend.
**Acceptance Criteria:** UI supports at least English and one other language via messages files.
**Labels:** enhancement, frontend
**Estimate:** small

---

## 10) UI component library and theming
**Description:** Extract common UI components and theme tokens into a shared package (e.g., `ui`) for reuse between frontends.
**Acceptance Criteria:** Shared component package with basic components and theme, used by frontends.
**Labels:** frontend, refactor
**Estimate:** medium

---

## 11) Monorepo structure and build tooling
**Description:** Organize code into a monorepo (packages) with `yarn` scripts, linting, and type generation workflows.
**Acceptance Criteria:** Monorepo layout, working build/lint scripts, CI-friendly configuration.
**Labels:** tooling, devops
**Estimate:** medium

---

*If you want me to also open these as GitHub Issues automatically, confirm and I will create them directly in the repository.*