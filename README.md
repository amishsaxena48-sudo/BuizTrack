# 🚀 BuizTrack

> A modern, lightweight web application designed to streamline business tracking, operations, and management workflows efficiently.

🔗 **Live Demo:** [http://139.84.175.156](http://139.84.175.156)

---

## 📌 Overview

### The Problem

Small businesses, creators, and teams often struggle with cluttered spreadsheets, fragmented tools, and overly complex software just to track their core metrics, daily tasks, and operational workflows. Existing solutions are either too bloated or lack a clean, lightning-fast interface, creating unnecessary friction in day-to-day management.

### Use Case

BuizTrack solves this by providing a centralized, distraction-free dashboard where users can monitor, organize, and manage their business data seamlessly in real-time. Whether deployed for personal project tracking or small business management, it ensures smooth cross-platform accessibility across both desktop and mobile devices.

### How It Works

* **Responsive Frontend Design:** Built with a lightweight interface that adapts fluidly across all screen sizes (desktop, tablet, and mobile).
* **Asynchronous UX Enhancements:** Features optimized UI interactions (such as dynamic loading states for login, signup, and logout actions) to ensure zero lag and immediate visual feedback.
* **Reliable Cloud Infrastructure:** Containerized using Docker for environment consistency and served via a high-performance Nginx web server deployed on cloud architecture.

---

## ⚙️ Setup & Installation Instructions

To run this project locally or deploy it on your own server, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/amishsaxena48-sudo/BuizTrack.git
cd BuizTrack

```

### 2. Run with Docker (Recommended)

Make sure you have Docker installed on your machine, then run:

```bash
docker build -t buiztrack .
docker run -d -p 80:80 --restart unless-stopped buiztrack

```

### 3. Access the Application

Open your browser and navigate to:

```text
http://localhost

```

