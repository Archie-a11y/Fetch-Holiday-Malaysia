# Malaysia Holiday Calendar

A lightweight, single-page web application designed to fetch, filter, and visualize Malaysian public holidays in real-time. Built as a self-contained client-side application, it leverages dynamic APIs to deliver localized holiday schedules with support for state-specific filters and multiple languages.

---

## ✨ Features

- 🌐 **Multi-language Support**: Toggle interfaces seamlessly between English, Chinese (中文), and Malay (Bahasa Melayu).
- 🗺️ **State-level Filtering**: Filter holidays dynamically by individual Malaysian states (e.g., Selangor, Johor, Penang) or view national-level public holidays.
- 📅 **Dual Visual Layouts**:
  - **Calendar Grid View**: An interactive, classical 12-month grid displaying holidays highlighted in gold.
  - **Table List View**: A detailed chronological table showing statuses, badges, and the scope of each holiday.
- ⏳ **Chronological Status Indicators**: Holidays automatically display status tags based on the current date, categorizing events into *Passed*, *Upcoming*, or *Today*.
- 📱 **Fully Responsive Layout**: Designed using CSS Grid, Flexbox, and media queries to adapt from desktop screens to mobile card structures.
- 💡 **Interactive Tooltips**: Hovering over calendar dates displays custom tooltips with holiday names and their applicable states.

---

## 🏗️ Tech Stack

- **Markup & Structure**: HTML5 (Semantic elements)
- **Styling & Theme**: CSS3 (Custom properties/variables, Flexbox, CSS Grid, Responsive breakpoints)
- **Client-Side Logic**: Vanilla JavaScript (ES6+, Fetch API, Dynamic DOM rendering, Event delegation)
- **Data Source**: Microservice Holiday API (Hosted on Cloudflare Workers)

---

## 🖼️ Project Screenshots & User Guide

### 📍 Step 1: Default Dashboard (Calendar Grid View)
The application initializes in the English calendar layout, highlighting current-year public holidays in gold and the current day in blue.
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/cc1a51ca-08a1-498f-b558-2666040cd3b9" />


### 📍 Step 2: Tabular Holiday List & Status Badges
Switching to the Table View presents holidays in a clean, chronological list accompanied by visual badges indicating their status relative to today's date.
<img width="1366" height="604" alt="image" src="https://github.com/user-attachments/assets/9961f706-d80e-4d30-b65d-be0ff189fb52" />


### 📍 Step 3: Interactive Multi-language & State Filters
Users can filter holidays by choosing a specific state and change the application language to localize holiday names instantly.
<img width="1366" height="605" alt="image" src="https://github.com/user-attachments/assets/d5a46a73-5373-4f5f-b354-fdb3051fb24a" />


### 📍 Step 4: Desktop Hover Details (Custom Tooltips)
Placing the mouse pointer over a highlighted holiday date triggers a dynamic, custom-styled tooltip containing metadata about the holiday.
<img width="1366" height="606" alt="image" src="https://github.com/user-attachments/assets/7338add2-5072-4941-9795-2517076c5117" />


---

## 🛠️ Project Setup

### Prerequisites
Since this is a client-side static application, you do not need to install databases, runtimes, or package managers. 
- A modern web browser (e.g., Google Chrome, Mozilla Firefox, Apple Safari, Microsoft Edge).
- Active internet connection (required to fetch holiday data from the remote API).

### Installation Steps

1. **Clone or Download the Project**:
   Download the HTML file directly or clone the repository to your local computer.
   ```bash
   git clone https://github.com/Archie-a11y/AI-Background-Remover.git
   ```

2. **Open the Application**:
   Navigate to the directory containing the file and open it with your browser:
   * Double-click `index.html`.
   * Alternatively, use an editor extension like "Live Server" in VS Code to host it locally.
