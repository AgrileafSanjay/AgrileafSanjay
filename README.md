<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0d1117&height=200&section=header&text=Sanjay%20%7C%20Agrileaf&fontSize=52&fontColor=00bcd4&animation=fadeIn&fontAlignY=40&desc=Computer%20Vision%20%C2%B7%20AgriTech%20%C2%B7%20Industrial%20Automation&descAlignY=60&descSize=20&descColor=8b949e" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=00BCD4&center=true&vCenter=true&width=540&lines=Building+vision+systems+for+agriculture+%F0%9F%8C%BE;Real-time+defect+detection+%26+quality+grading;YOLO11+%7C+OpenCV+%7C+RPi+%7C+Django+%7C+React" alt="Typing SVG" />
</div>

<br/>

<div align="center">
  <a href="mailto:agrileaf.sanjay@gmail.com">
    <img src="https://img.shields.io/badge/sanjay%40-0d1117?style=flat-square&logo=gmail&logoColor=00bcd4" alt="Email"/>
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/India-0d1117?style=flat-square&logo=googlemaps&logoColor=00bcd4" alt="Location"/>
  &nbsp;
  <img src="https://img.shields.io/badge/AgriTech-0d1117?style=flat-square&logo=leaflet&logoColor=00bcd4" alt="Domain"/>
</div>

<br/>

<div align="center">

[About](#about-me) · [Projects](#-featured-projects) · [Tech Stack](#-tech-stack) · [Stats](#-github-stats) · [Contact](#-get-in-touch)

</div>

---

## About Me

Software Developer at **Agrileaf** — building real-time computer vision systems that bring intelligent inspection to agriculture and industrial manufacturing. I design end-to-end pipelines from model training to hardware deployment: YOLO models running on Raspberry Pi, talking to actuators and sensors, backed by full-stack Django + React dashboards for operations teams. Recent work includes YOLO11 fungus detection on agri produce, ArUco-calibrated dimension inspection, and a shared SSO identity layer connecting Agrileaf's internal business apps (billing, purchase &amp; payment, HR, inventory, projects).

---

## 🚀 Featured Projects

<table>
  <tr>
    <td valign="top" width="50%">
      <h3>🌾 Arecanut Sorting System</h3>
      <p>Real-time arecanut quality grading using YOLO11 segmentation. Classifies nuts into 4 grades — <code>Good</code>, <code>Koka</code>, <code>Cheppu</code>, <code>Patora</code> — and triggers physical actuators over serial. Flask frame-streaming server handles RPi camera feeds. Custom dark-theme UI with live video + count dashboard.</p>
      <p>
        <img src="https://img.shields.io/badge/YOLO11_Seg-111F68?style=flat-square" alt="YOLO11"/>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
        <img src="https://img.shields.io/badge/RPi-A22846?style=flat-square&logo=raspberry-pi&logoColor=white" alt="RPi"/>
        <img src="https://img.shields.io/badge/Flask-000?style=flat-square&logo=flask&logoColor=white" alt="Flask"/>
        <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"/>
      </p>
    </td>
    <td valign="top" width="50%">
      <h3>⚙️ Plate Sorting System</h3>
      <p>End-to-end automated sorting pipeline — YOLO11 5-class defect detection drives a physical rotary station with laser sensors, stepper motors, and relay-controlled actuators via Arduino. Tracks and routes plates by defect class at production throughput.</p>
      <p>
        <img src="https://img.shields.io/badge/YOLO11-111F68?style=flat-square" alt="YOLO11"/>
        <img src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white" alt="Arduino"/>
        <img src="https://img.shields.io/badge/RPi-A22846?style=flat-square&logo=raspberry-pi&logoColor=white" alt="RPi"/>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      </p>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h3>👁️ Camera OCR System</h3>
      <p>Live camera OCR pipeline: YOLO segmentation isolates text regions, then PaddleOCR / EasyOCR extracts characters. 85% confidence threshold, custom charset validation (A–Z, 0–9, ₹), Levenshtein distance correction. Real-time CustomTkinter UI with GPU acceleration.</p>
      <p>
        <img src="https://img.shields.io/badge/PaddleOCR-0062B3?style=flat-square" alt="PaddleOCR"/>
        <img src="https://img.shields.io/badge/EasyOCR-333?style=flat-square" alt="EasyOCR"/>
        <img src="https://img.shields.io/badge/YOLO-111F68?style=flat-square" alt="YOLO"/>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      </p>
    </td>
    <td valign="top" width="50%">
      <h3>📦 Inventory Management</h3>
      <p>Full-stack inventory platform with RBAC (Admin / Manager / Requester), multi-warehouse tracking, product movement records (stock in / out / transfer), Sort & Pack batch processing, bulk CSV/XLSX import, min/max stock threshold alerts, and Celery background tasks. Dockerized for on-premise LAN or cloud deployment.</p>
      <p>
        <img src="https://img.shields.io/badge/Django%205-092E20?style=flat-square&logo=django&logoColor=white" alt="Django"/>
        <img src="https://img.shields.io/badge/React%2018-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
        <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
        <img src="https://img.shields.io/badge/Ant%20Design-0170FE?style=flat-square&logo=antdesign&logoColor=white" alt="Ant Design"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
      </p>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h3>💳 Purchase &amp; Payment Approval</h3>
      <p>Approval engine for Purchase, Payment and Reimbursement Requests routed through admin-configured <b>N-level approval workflows</b> (one per department per module), replacing the legacy fixed L1 → L2 → L3 chain. Purchase Requests with revision chains, invoice management with GST line items and attachments, PR-vs-invoice comparison with auto-split sub-requests, optional digital invoices on reimbursements, TDS &amp; debit/credit notes, vendor-based scheduling, bulk CSV/XLSX import, PostgreSQL backup &amp; restore, and Agrileaf SSO sign-in. Shipped through 68 versioned releases.</p>
      <p>
        <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django"/>
        <img src="https://img.shields.io/badge/React%2019-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
        <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
        <img src="https://img.shields.io/badge/Ant%20Design%206-0170FE?style=flat-square&logo=antdesign&logoColor=white" alt="Ant Design"/>
        <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" alt="Celery"/>
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis"/>
      </p>
    </td>
    <td valign="top" width="50%">
      <h3>📋 Order Management System</h3>
      <p>Full-stack order lifecycle platform with RBAC (Admin / Manager / Requester). Orders flow through warehouse assignment, packing, dispatch, and delivery confirmation — with per-line-item status driving the overall order state machine. Dockerized for deployment.</p>
      <p>
        <img src="https://img.shields.io/badge/Django%204.2-092E20?style=flat-square&logo=django&logoColor=white" alt="Django"/>
        <img src="https://img.shields.io/badge/React%2019-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
        <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
        <img src="https://img.shields.io/badge/Ant%20Design-0170FE?style=flat-square&logo=antdesign&logoColor=white" alt="Ant Design"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
      </p>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h3>🗂️ ProjectHub</h3>
      <p>Full-stack project & task management platform with department-scoped RBAC (Admin → Dept Head → Team Lead → Member), drag-and-drop Kanban + list views, task dependencies, file attachments, threaded comments with <code>@mentions</code>, and a Knowledge Base. Reporting suite covers burn-down, velocity, resource utilization, and Gantt view with CSV/PDF export, backed by a full audit trail, Ctrl+K global search, recurring tasks with anchored schedules &amp; catch-up, Celery-driven reminders, IST-aware dates, and CI/CD-gated deploys with Trivy vulnerability scanning.</p>
      <p>
        <img src="https://img.shields.io/badge/Django%205-092E20?style=flat-square&logo=django&logoColor=white" alt="Django"/>
        <img src="https://img.shields.io/badge/React%2019-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
        <img src="https://img.shields.io/badge/Ant%20Design-0170FE?style=flat-square&logo=antdesign&logoColor=white" alt="Ant Design"/>
        <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" alt="Celery"/>
        <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
      </p>
    </td>
    <td valign="top" width="50%">
      <h3>🧾 Billing System</h3>
      <p>Full-stack billing & invoicing platform — Django 5 + DRF backend, React 19 + TypeScript + Ant Design frontend. Manages Catalog, Customers, and customer-specific SKU pricing/packaging Mappings; drives Orders through EVD + RFID declaration fields; builds Invoices from Mapping data with per-invoice tariff codes, exported to <code>.xlsx</code> invoice/packing-list templates plus EVD + RFID <code>.docx</code> documents. Agrileaf SSO sign-in, audit log, and GHCR-based CI/CD deploys.</p>
      <p>
        <img src="https://img.shields.io/badge/Django%205-092E20?style=flat-square&logo=django&logoColor=white" alt="Django"/>
        <img src="https://img.shields.io/badge/React%2019-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
        <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
        <img src="https://img.shields.io/badge/Ant%20Design%206-0170FE?style=flat-square&logo=antdesign&logoColor=white" alt="Ant Design"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
      </p>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h3>🔐 Agrileaf SSO &amp; User Console</h3>
      <p>Central identity service for all Agrileaf apps (Billing, Inventory, ProjectHub, Purchase Payment). One sign-in for users; one admin console for users, applications, access grants and audit trail. Opaque bearer session tokens validated by every delegating app, 12-hour absolute session cap, instant sign-out push to every open tab over WebSockets, invitation/activation &amp; self-service reset flows, forced password change, rate-limited lockout-protected sign-in, and a responsive console for phone → desktop.</p>
      <p>
        <img src="https://img.shields.io/badge/Django%20REST-092E20?style=flat-square&logo=django&logoColor=white" alt="Django"/>
        <img src="https://img.shields.io/badge/Channels%20%2F%20WebSocket-333?style=flat-square" alt="Channels"/>
        <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
        <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis"/>
        <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
      </p>
    </td>
    <td valign="top" width="50%">
      <h3>👥 HRM &amp; Leave Management</h3>
      <p>HR platform covering employee onboarding with digital employee files and leave management with manager-approval workflow. Departments, employee types, leave types, policies &amp; balances, holidays, team calendar, announcements, document library, onboarding checklists, reports, RBAC and audit trail. First-login guided tours per role, pytest + Vitest + Playwright regression suite in CI, Caddy auto-HTTPS for production.</p>
      <p>
        <img src="https://img.shields.io/badge/Django%205-092E20?style=flat-square&logo=django&logoColor=white" alt="Django"/>
        <img src="https://img.shields.io/badge/React%2018-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
        <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
        <img src="https://img.shields.io/badge/PostgreSQL%2016-316192?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
        <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright"/>
      </p>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h3>🏭 AGRI-OS</h3>
      <p>Inventory &amp; warehouse ERP for a palm leaf plate, veneer plate, wooden tray and plastic lid manufacturer. Orders, purchase orders, purchase invoices, stock ledger, warehouse issue/return/verification queues, packing and dispatch across 10 roles. Built-in AI assistant <b>AIRA</b> answers natural-language factory queries and prefills purchase invoices from PDFs/images. Excel/PDF document export, Dockerized with GHCR images and DigitalOcean deploy.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
        <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite"/>
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
        <img src="https://img.shields.io/badge/DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white" alt="DigitalOcean"/>
      </p>
    </td>
    <td valign="top" width="50%">
      <h3>📐 Dimension Inspection System</h3>
      <p>Inline go/no-go dimension check for trays and plates on a conveyor. ESP32 tracks position with a rotary encoder and triggers capture and ejection; RPi5 camera frames go to a Flask server that undistorts the fisheye lens, segments the product, and measures it in mm using ArUco-marker scale calibration against the selected size and tolerance. Results are logged to CSV and a relay-driven piston rejects out-of-spec parts.</p>
      <p>
        <img src="https://img.shields.io/badge/OpenCV%20ArUco-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"/>
        <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32"/>
        <img src="https://img.shields.io/badge/RPi%205-A22846?style=flat-square&logo=raspberry-pi&logoColor=white" alt="RPi"/>
        <img src="https://img.shields.io/badge/Flask-000?style=flat-square&logo=flask&logoColor=white" alt="Flask"/>
      </p>
    </td>
  </tr>
</table>

---

## 🛠️ Tech Stack

**ML & Computer Vision**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![YOLO](https://img.shields.io/badge/Ultralytics%20YOLO-111F68?style=for-the-badge&logoColor=white)

**Web Development**

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![Ant Design](https://img.shields.io/badge/Ant%20Design-0170FE?style=for-the-badge&logo=antdesign&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=for-the-badge&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

**Infrastructure & Hardware**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberry-pi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=for-the-badge&logo=caddy&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=for-the-badge&logo=digitalocean&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=AgrileafSanjay&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=00bcd4&icon_color=00bcd4" alt="GitHub Stats"/>
  &nbsp;
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AgrileafSanjay&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00bcd4&count_private=true" alt="Top Languages"/>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=AgrileafSanjay&theme=github-dark-blue&hide_border=true&background=0d1117&ring=00bcd4&fire=00bcd4&currStreakLabel=00bcd4" alt="GitHub Streak"/>
</div>

---

## 📬 Get in Touch

<div align="center">
  <a href="mailto:agrileaf.sanjay@gmail.com">
    <img src="https://img.shields.io/badge/Get%20in%20Touch-sanjay%40agrileaf.in-0d1117?style=for-the-badge&logo=gmail&logoColor=00bcd4" alt="Email"/>
  </a>
</div>

<br/>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0d1117&height=100&section=footer" />
</div>
