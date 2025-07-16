## 📌 Project Summary

**Engineering Automations** is a curated collection of **UIPath automation workflows** tailored for the needs of **engineering and project-based companies**. These automations are designed to streamline repetitive tasks, reduce manual effort, and enhance the accuracy and efficiency of day-to-day operations.

### 🔧 What It Does

This repository includes workflows that automate:

- 📊 **Data Extraction & Transformation**  
  Extract data from PDFs (like technical reports, outlook threads, etc), and convert it into structured formats for analysis or reporting.

- 🗂️ **Project File Management**  
  Automatically create and maintain folder structures, apply naming conventions, and archive files.

- 📑 **Diagram Markups**  
  Markup PDF diagrams using project-specific data.

- 🧾 **Prolog Converge Scraper**  
  Srape information from the Prolog Converge Construction Project Management Software and convert it into structured Excel data.

### 🎯 Who It's For

This project is ideal for:

- Engineering teams looking to adopt RPA without building workflows from scratch
- Project managers aiming to reduce time spent on repetitive documentation
- Companies seeking to improve consistency and reduce human error in engineering processes

The workflows are modular and customizable, making it easy to adapt them to your specific tools, templates, and processes.


> ⚠️ **Disclaimer**: Some workflows in this repository are still a **Work In Progress (WIP)** and may require further development or testing before production use.


---




## ⚙️ How to Use These Automations

To run the automation workflows provided in this repository, follow the steps below:

### 🖥️ Prerequisites

- Install **UIPath Assistant**  
  This is the desktop application used to run automation packages locally.

### 📦 Step-by-Step Instructions

1. **Download the Automation Package**  
   Download the latest `.nupkg` file from this link: [Jacobs.Engineering.Automations.1.0.6.nupkg](https://github.com/Jon-hattan/Engineering-Automations/releases/download/v1.0.6/Jacobs.Engineering.Automations.1.0.6.nupkg)  
   Move the downloaded `.nupkg` file to the following directory:
     ```
     %ProgramData%\UiPath\Packages
     ```


3. **Launch UIPath Assistant and Migrate the Process**  
   - Open **UIPath Assistant**
   - Click on your **profile name** in the top-right corner
   - Go to **Preferences → Tools**
   - Click **Migrate** to import the automation package into your Assistant

4. **Install the Automation**  
   - After migration, locate the automation in the Assistant
   - Click **Install** to add it to your local environment

5. **Configure UIPath Extension on Microsoft Edge**
   - Open Microsoft Edge.
   - In the address bar, type edge://extensions/ and press **Enter**.
   - Find the **UiPath Web Automation** extension, enable it by clicking on the slider, and then click **Details**.
   - Enable "**Allow access to file URLs**"
These settings are essential for Prolog Converge Automations.

5. **Configure GenAI Activities**  
   - Click on your **profile name** → **Preferences**
   - Under **GenAI Activities**, select your **email address** to enable GenAI-powered activities
  
6. **Configure PiP (if required)**  
   - Click Run in PiP if you wish to run it in picture-in-picture (a guide for when to run it in PiP is included below).

7. **Run the Automation**  
   - Once installed and configured, click **Run** to execute the automation
   - Ensure any required input files or configurations are in place



---

### 🖼️ Optional: Use Picture-in-Picture (PiP)

**Picture-in-Picture (PiP)** allows the automation to run in a separate Windows session, so you can continue using your computer while the automation executes in the background.

#### 💡 When to Use PiP:
- ✅ **Recommended** for long-running automations like:
  - `P&ID Marking`
  - `P&ID Tracking`  
  These take more time and can run in the background while you work.

- ❌ **Not necessary** for shorter, interactive automations like:
  - `Electrical Load List Generator`
  - `RFIW Separator`  
  These require more user input and are better run in the foreground.

> You can enable or disable PiP by clicking on the automation and going to "Configure".
