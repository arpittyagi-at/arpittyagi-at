<p align="center">
  <img src="./assets/banner.svg" alt="TaskManager ArpitTyagi" width="100%" />
</p>

# TaskManager ArpitTyagi

<p>
  <img src="https://img.shields.io/badge/Web%20App-0D1117?style=flat-square&logo=javascript&logoColor=FF9900" alt="Web App" />
  <img src="https://img.shields.io/badge/CRUD-0D1117?style=flat-square&logo=sqlite&logoColor=58A6FF" alt="CRUD" />
  <img src="https://img.shields.io/badge/GitHub-0D1117?style=flat-square&logo=github&logoColor=F0F6FC" alt="GitHub" />
  <img src="https://img.shields.io/badge/Responsive%20UI-0D1117?style=flat-square&logo=vercel&logoColor=F0F6FC" alt="Responsive UI" />
</p>

## Overview

TaskManager ArpitTyagi is a productivity application for creating, organizing, updating, and completing tasks through a clear user interface. The project demonstrates practical application structure, CRUD behavior, and interface thinking.

## Business Problem

Users often need a lightweight system to capture tasks, maintain priorities, and track progress without unnecessary complexity. The product value comes from making common workflows fast: add, edit, complete, filter, and review work.

## Objectives

| Objective | Outcome |
| --- | --- |
| Implement task CRUD | Support creating, reading, updating, and deleting tasks. |
| Improve task visibility | Use status, priority, and clean layout to make work scannable. |
| Build responsive flows | Keep the interface usable across desktop and mobile. |
| Practice maintainable UI | Separate structure, styling, and behavior clearly. |

## Dataset

The application uses task records as its primary data model. A task can include id, title, description, status, priority, due date, created date, and updated date.

## Architecture

```text
User Actions
  -> UI Components
  -> Task State
  -> CRUD Operations
  -> Local or Persistent Storage
  -> Updated Task Views
```

## Folder Structure

```text
.
|-- src/
|   |-- components/
|   |-- data/
|   |-- styles/
|   `-- utils/
|-- public/
|   `-- screenshots/
|-- assets/
|   `-- banner.svg
|-- README.md
`-- package.json
```

## Tech Stack

| Layer | Tools |
| --- | --- |
| Interface | HTML, CSS, JavaScript or React |
| State | Browser state, local storage, or backend API |
| Workflow | Git, GitHub |
| Quality | Responsive design, form validation, empty states |

## Installation

```bash
git clone https://github.com/arpittyagi-at/TaskManager-ArpitTyagi.git
cd TaskManager-ArpitTyagi
npm install
npm run dev
```

## Results

The finished application supports task creation, editing, completion, deletion, filtering, responsive interaction, and clear visual feedback for empty, active, and completed states.

## Screenshots

| View | File |
| --- | --- |
| Dashboard | `public/screenshots/dashboard.png` |
| Add task flow | `public/screenshots/add-task.png` |
| Mobile task list | `public/screenshots/mobile.png` |

## Next Improvements

| Improvement | Value |
| --- | --- |
| Add authentication | Support user-specific task lists. |
| Add backend persistence | Keep tasks synced across sessions and devices. |
| Add analytics summary | Show completion rate and productivity trends. |
| Add keyboard shortcuts | Improve speed for frequent users. |

## License

This project is released under the MIT License.
