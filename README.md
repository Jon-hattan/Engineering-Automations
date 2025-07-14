## ⚙️ How to Use These Automations

To run the automation workflows provided in this repository, follow the steps below:

### 🖥️ Prerequisites

- Install **UIPath Assistant**  
  This is the desktop application used to run automation packages locally.

### 📦 Step-by-Step Instructions

1. **Download the Automation Package**  
   Download the latest `.nupkg` file from this link:  
   👉 [Jacobs.Engineering.Automations.1.0.6.nupkg](https://github.com/Jon-hattan/Engineering-Automations/releases/downloadPackage in the Correct Folder**  
   Move the downloaded `.nupkg` file to one of the following directories:

   - For system-wide installation:
     ```
     %ProgramData%\UiPath\Packages
     ```
   - For user-specific installation:
     ```
     %UserProfile%\.nuget\packages
     ```

3. **Launch UIPath Assistant and Migrate the Process**  
   - Open **UIPath Assistant**
   - Click on your **profile name** in the top-right corner
   - Go to **Preferences → Tools**
   - Click **Migrate** to import the automation package into your Assistant

4. **Install the Automation**  
   - After migration, locate the automation in the Assistant
   - Click **Install** to add it to your local environment

5. **Configure GenAI Activities (if required)**  
   - Click on your **profile name** → **Preferences**
   - Under **AI Center / GenAI**, enter your **email address** to enable GenAI-powered activities

6. **Run the Automation**  
   - Once installed and configured, click **Run** to execute the automation
   - Ensure any required input files or configurations are in place

---

### 🖼️ Optional: Use Picture-in-Picture (PiP)

**Picture-in-Picture (PiP)** allows the automation to run in a separate Windows session, so you can continue using your computer while the automation executes in the background.

- Learn more about PiP here: 👉 How to Use Picture-in-Picture in UIPath

#### 💡 When to Use PiP:
- ✅ **Recommended** for long-running automations like:
  - `P&ID Marking`
  - `P&ID Tracking`  
  These take more time and can run in the background while you work.

- ❌ **Not necessary** for shorter, interactive automations like:
  - `Electrical Load List Generator`
  - `RFIW Separator`  
  These require more user input and are better run in the foreground.

> You can enable or disable PiP when launching the automation by clicking the dropdown next to the **Run** button in UIPath Assistant.
