# Life-Happens
Life Happens

Life Happens is an adaptive academic scheduler that transforms deadlines into a living study plan. Unlike traditional to-do lists or static calendars, it automatically finds study time, optimizes around your priorities, and instantly recalculates when life throws curveballs. With flexible scheduling modes, Canvas & Calendar integration, syllabus confirmation, and optional focus app support, Life Happens helps students get work done without the constant mental juggling.

📝 The Problem

Being a student is a constant juggling act: lectures, assignments, projects, readings, and personal goals. Deadlines alone are not enough — finding the time to complete everything is the real challenge. Existing tools show deadlines but rarely adapt to changes in priorities or unexpected life events.

💡 The Solution

Life Happens is a dynamic, priority-aware study planner. It takes all of your academic tasks and commitments, intelligently schedules them, and adapts in real time. Whether you’re aiming for a balanced week, a high-priority crunch, or an all-nighter, Life Happens flexes to your reality — so you can focus on work instead of planning.

✨ Key Features
1. Assignment Import

Primary: Import assignments directly from Canvas via API.

Secondary: Optional syllabus PDF import with “Confirm or Edit” mode to handle messy PDFs.

Commitments: Import existing events from Google Calendar or iCalendar.

2. Intelligent Scheduling with Modes

Life Happens adapts to both your priorities and reality:

Mode	Description
Balanced Mode	Optimized to respect awake hours, classes, and commitments. Ideal for long-term scheduling.
Priority Override Mode	Temporarily extend awake hours, reschedule low-priority tasks, or skip optional commitments for urgent deadlines.
All-Nighter Mode	Focus purely on the task at hand, ignoring sleep or optional commitments. Brute-force scheduling until completion.

Users can configure custom sliders for flexibility (sleep tolerance, class skipping, free-time sacrifices).

3. Calendar Integration

Sync study blocks to Google Calendar or iCalendar automatically.

Recalculate schedules with a single click when life happens.

4. Dynamic Rescheduling

Handles unexpected events or missed blocks by recalculating only the remaining tasks.

Updates the calendar automatically with new optimized schedule.

5. Optional Focus App Integration

Future support for apps like Opal to block distractions during scheduled sessions.

🛠️ Technology Stack

Backend: Python + FastAPI

Frontend: React.js (create-react-app or Vite)

Database: PostgreSQL (or SQLite for MVP)

Python Libraries:

SQLModel / SQLAlchemy for DB management

pdfplumber + regex for syllabus parsing

google-api-python-client + google-auth-oauthlib for Calendar API

icalendar for .ics file generation (optional)
