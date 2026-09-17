## 🟢 Beginner: The "Vanilla" Logic Reset (3 Projects)

**Focus:** Mastering the DOM, Async patterns, and State without frameworks.

1. **The "Virtual Spreadsheet" (Mini-Excel):**
* **The Task:** Create a grid where cells can contain numbers or formulas (e.g., `=SUM(A1, B1)`).
* **The Challenge:** Use a single `index.html` and `script.js` to handle all logic and save data to `localStorage`.


2. **The "Native Dashboard" (API-Driven):**
* **The Task:** Build a dashboard that fetches and displays live data (Weather or Finance) using `fetch()` and `async/await`.
* **The Challenge:** No React or Tailwind; you must create and move elements using only `document.createElement`.


3. **The "State-Sync" Task Manager:**
* **The Task:** A Todo-style app where changing a setting in one sidebar updates a different component on the screen.
* **The Challenge:** Implement your own State Management system to "notify" different parts of the page when data changes without a framework.



---

## 🟡 Intermediate: The "Pattern & System" Layer (3 Projects)

**Focus:** Algorithmic efficiency and connecting University theory to code.

1. **The "Algorithm Visualizer":**
* **The Task:** Build a webpage that animates a sorting algorithm (like Bubble Sort) or a search algorithm.
* **The Challenge:** You must include a sidebar explaining the **Time/Space Complexity** (Big O) of the current animation.


2. **The "Scalable Ordering System" (Backend Focus):**
* **The Task:** Create a basic API for an ordering system and implement **Rate Limiting**.
* **The Challenge:** Prevent a single user from spamming your API 1,000 times a second.


3. **The "Auth & Cache" Gateway:**
* **The Task:** Build a login system that uses your own manually implemented **JWT (JSON Web Token)** flow.
* **The Challenge:** Add a **Redis Cache** layer so that frequent data requests hit memory instead of the main database.



---

## 🔴 Expert: The "Infrastructure & Senior" Hero (3 Projects)

**Focus:** Automation, Observability, and treating Infrastructure as Code.

1. **The "Self-Healing" Pipeline:**
* **The Task:** Containerize an app with **Docker** and write a **Terraform** script to spin up a server.
* **The Challenge:** Set up a **GitHub Action** that builds the Docker image and deploys it automatically upon every push.


2. **The "Monitoring Stack" (Fault-Tolerance):**
* **The Task:** Install **Prometheus and Grafana** to monitor a Node.js server.
* **The Challenge:** Intentionally break your database and see how fast your Grafana dashboard alerts you to the failure.


3. **The "Automated Infrastructure" Provisioner:**
* **The Task:** Use Terraform to provision a Linux VPS (like AWS EC2 or DigitalOcean).
* **The Challenge:** Master **Linux Internals** by configuring the server via script to handle specific process (PID) and file descriptor limits.

