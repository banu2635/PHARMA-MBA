# PHARMA-MBA
# Pharma MBA Compass – GitHub Ready Full-Stack Project

## Objective

Build a complete GitHub-ready web application called **Pharma MBA Compass**.

The project should be production-ready, responsive, and deployable directly to GitHub and Vercel.

The goal is to create a centralized platform where Pharma MBA students can manage learning, case studies, competitions, internships, productivity, and career growth.

The application should answer:

"What should I do today to become a successful Pharma MBA professional?"

---

## Technology Stack

Use:

* Next.js 15 (App Router)
* React
* TypeScript
* Tailwind CSS
* shadcn/ui
* Recharts
* Supabase Authentication
* Supabase Database
* React Hook Form
* Zod Validation

Project must be deployable directly on GitHub and Vercel.

---

## Core Pages

### Dashboard

Display:

* Welcome card
* Pending tasks
* Completed tasks
* Internship applications
* Case studies completed
* Learning streak
* Overall progress percentage

Charts:

* Radial progress gauge
* Weekly activity chart
* Monthly completion chart

Today's Focus:

* Study syllabus
* Solve case study
* Read pharma news
* Apply internship
* Revise notes
* Practice Excel

Tasks should be toggleable.

---

### Case Studies

Create searchable database.

Each case contains:

* Title
* Company
* Industry
* Difficulty
* Problem Statement
* Background
* Framework
* Analysis
* Solution
* Key Learnings

Filters:

* Pharma
* Marketing
* Sales
* Product
* Supply Chain
* Healthcare

Bookmark functionality.

---

### Case Competitions

Display:

* Competition name
* Organizer
* Registration deadline
* Prize
* Team size
* Eligibility
* Registration URL

Status:

* Open
* Closing Soon
* Closed

Save competition feature.

---

### Syllabus Manager

Semester wise structure.

Semester 1

* Pharmaceutical Management
* Marketing Management
* HR Management
* Statistics
* Economics
* Accounting

Each subject contains:

* Important Topics
* Notes
* Recommended Books
* Previous Papers
* Learning Resources

Progress tracking:

* Not Started
* In Progress
* Completed

---

### Roadmap

Generate structured plans:

30-Day Roadmap

60-Day Roadmap

90-Day Roadmap

Include:

* Weekly Goals
* Learning Objectives
* Excel Learning
* Resume Building
* Case Practice
* Internship Preparation

---

### Internship Tracker

Display:

* Company
* Role
* Location
* Work Mode
* Duration
* Stipend
* Deadline
* Apply Link

Application status:

* Not Applied
* Applied
* Interview
* Selected
* Rejected

Search and filter support.

---

### Daily Task Tracker

Allow:

Create Task

Fields:

* Title
* Priority
* Deadline
* Category
* Status

Operations:

* Add
* Edit
* Delete
* Complete

Show completion percentage.

---

### Weekly Habit Tracker

Track:

* Study
* Revision
* Case Study
* Internship Search
* Networking

Display weekly statistics.

---

### Monthly Progress

Display:

* Study Hours
* Tasks Completed
* Case Studies Solved
* Internship Applications

Charts:

* Pie Chart
* Line Chart
* Progress Chart

---

### Resources Library

Categories:

* Books
* Notes
* Resume Templates
* Excel Resources
* Power BI Resources
* Marketing Resources
* Industry Reports

Search functionality required.

---

### Profile Page

Display:

* Name
* College
* Semester
* Target Role
* Skills
* Certifications
* Progress Summary

---

## Global Search

Search across:

* Case Studies
* Competitions
* Syllabus
* Internships
* Resources

---

## Authentication

Implement Supabase Authentication.

Support:

* Email Login
* Email Signup
* Google Login

Protected Routes:

* Dashboard
* Tracker
* Profile

---

## Database Schema

Users

Tasks

CaseStudies

Competitions

Internships

Syllabus

Resources

Bookmarks

Progress

Habits

Applications

Use simple relational schema.

---

## Admin Panel

Admin can:

* Add Case Studies
* Add Competitions
* Add Internships
* Add Resources
* Update Syllabus

Simple CRUD only.

---

## AI Assistant

Add chatbot UI component.

Capabilities:

* Explain Pharma MBA concepts
* Generate study plans
* Explain case studies
* Suggest internships
* Resume tips

Create API-ready architecture.

Do not connect any paid AI API.

Use mock responses.

---

## UI Requirements

* Mobile Responsive
* Dashboard First Design
* Dark Mode
* Clean Cards
* Modern Layout
* Fast Loading
* Minimal Animations

---

## Deployment

Generate:

* README.md
* Installation Guide
* Environment Variables Template
* Supabase Setup Instructions
* Vercel Deployment Instructions

Project should run using:

npm install
npm run dev

and be deployable directly from GitHub to Vercel without modification.

---

## Seed Data

Populate:

* 20 Pharma MBA Case Studies
* 10 Internship Opportunities
* Semester 1 Sample Syllabus
* Sample Tasks
* Sample Progress Data

so the dashboard looks complete immediately after deployment.
