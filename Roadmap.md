# 🗺️ Project Roadmap

### Phase 1: The Core Task Manager (MVP)
*Goal: Establish a solid, functional foundation for managing tasks manually.*
* **Backend:** Implement a full **CRUD API** (Create, Read, Update, Delete) for assignments.
* **Frontend:** Build a **React UI** to interact with the API, allowing users to add, view, and manage their tasks.
* **✅ Milestone:** A standalone, fully functional web-based task manager.

### Phase 2: Assignment & Calendar Integration
*Goal: Automate task and event input by connecting to external data sources.*
* **Task Importing:** Connect to the **Canvas API** to automatically import course assignments.
* **Event Importing:** Sync with **Google Calendar** or an **iCalendar** feed to import fixed commitments (classes, work, etc.).
* **Syllabus Parsing:** Add an optional **PDF syllabus import** feature with a user-facing **Confirm/Edit mode** to ensure accuracy.
* **✅ Milestone:** All academic tasks and personal events are aggregated into one unified system.

### Phase 3: Smart Scheduling & Modes
*Goal: Implement the core "intelligent" engine that generates personalized study plans.*
* **Task Estimation:** Add an **"estimated hours"** field to all assignments.
* **Scheduling Modes:** Implement flexible algorithms for different user needs: **Balanced**, **Priority Override**, and **All-Nighter** modes.
* **User Controls:** Introduce sliders or settings for **sleep, class, and free-time flexibility** to constrain the scheduler.
* **UI:** Create a dedicated scheduler page with a **"Generate My Schedule"** button.
* **✅ Milestone:** The app can generate adaptive schedules that respect user priorities and constraints.

### Phase 4: Dynamic Sync & Rescheduling
*Goal: Make the schedule a "living" entity that syncs with the user's real calendar.*
* **Calendar Sync (Write):** Push the generated schedules and work blocks to the user's **Google Calendar**.
* **Dynamic Rescheduling:** Automatically **recalculate the schedule** when tasks are marked complete, deadlines shift, or new events are added.
* **✅ Milestone:** A fully dynamic schedule that lives and updates within the user's primary calendar.

### Phase 5: Focus App Integration
*Goal: Bridge the gap between planning and execution by integrating with focus tools.*
* **API Integration:** Connect with focus apps like Opal to optionally block distractions during scheduled study blocks.
* **✅ Milestone:** The app actively helps reduce external distractions and increase focus.

### Phase 6: Polish & Quality-of-Life
*Goal: Refine the user experience and add features for advanced task management.*
* **Visualizations:** Implement an in-app **visual calendar view** using a library like FullCalendar.
* **Task Management:** Add support for **subtasks**, **pinning study blocks**, and on-the-fly task editing.
* **UI/UX:** Conduct a full review and implement general user interface improvements.
* **✅ Milestone:** A polished, intuitive, and fully adaptive academic scheduler.

---

## 🚀 Beyond Version 1.0

* **Chrome Extension:** Develop a browser extension for quick-adding tasks, context-aware importing from Canvas, and triggering a reschedule without opening the full web app.
