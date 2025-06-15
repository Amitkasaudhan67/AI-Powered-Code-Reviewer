## ✅ How to Run AI-Powered Code Reviewer in VS Code (Windows)

### 🔧 Prerequisites:

* Node.js installed
* VS Code installed
* Internet connection
* Google Gemini API key

---

### 🔹 Step-by-Step Instructions:

### **1. Open the Project in VS Code**

* Open **VS Code**.
* Click on **File > Open Folder** and select the root folder of your project (`ai-code-reviewer`).

---

### **2. Run the Backend Server**

* Go to the `server` folder in VS Code.
* Open a new terminal (`Ctrl + ~`).
* Run the following command to allow script execution:

  ```powershell
  Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
  ```
* Then, start the backend server using:

  ```bash
  npx nodemon
  ```
* This will start the Node.js server and listen on port `5000`.

---

### **3. Run the Frontend React App**

* Now go to the `client` folder in VS Code.
* Open a new terminal.
* Again, run this command to bypass script execution policy:

  ```powershell
  Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
  ```
* Start the frontend with:

  ```bash
  npm run dev
  ```

---

### **4. Open in Browser**

* Once both servers are running, open your browser and go to:

  ```
  http://localhost:3000
  ```

You’ll see the code editor where you can paste code and click **Review** to get AI-generated feedback.
