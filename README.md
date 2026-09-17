# Comprehensive Guide: Creating and Deploying an HTML Site on GitHub

This markdown document provides a streamlined, step-by-step roadmap from creating an HTML folder locally on your machine to hosting it live globally using GitHub Desktop and GitHub Pages.

---

## 📁 Phase 1: Create the Project Locally

1. **Create your folder:** Create a brand new folder on your computer desktop named `my-first-html-project`.
2. **Open in code editor:** Open your code editor (like VS Code) and load this folder.
3. **Create the file:** Create a new file inside this folder named **exactly** `index.html` *(all lowercase, no spaces)*.
4. **Add code and save:** Paste this basic HTML code inside your file and save it (**Ctrl + S** or **Cmd + S**):
   ```html
   <!DOCTYPE html>
   <html>
     <head>
       <title>My First Project</title>
     </head>
     <body>
       <h1>Hello World from GitHub!</h1>
     </body>
   </html>
   ```

---

## 🛠️ Phase 2: Track and Commit in GitHub Desktop

5. **Open the app:** Open the **GitHub Desktop** app on your computer.
6. **Add the folder:** Go to the top menu and select **File** > **Add Local Repository...**
7. **Select path:** Click **Choose...**, click on your `my-first-html-project` folder, and click **Open**.
8. **Initialize Git:** Click the blue link that says **create a repository** to let the app initialize your Git tracking. Leave the default settings alone and click **Create Repository**.
   * *Note: GitHub Desktop automatically takes a snapshot of your new file right here and labels it an "Initial commit". This is why your commit button may appear grayed out initially—your file is already safely recorded!*

---

## ☁️ Phase 3: Publish Publicly to GitHub.com

9. **Publish:** Click the **Publish repository** button at the top of the window.
10. **Make it public:** In the popup window that appears, **uncheck** the box that says **"Keep this code private"**. 
11. **Upload:** Click the blue **Publish Repository** button. Your code is now safely uploaded to the GitHub cloud.

---

## 🚀 Phase 4: Deploy Your Live Website Link

12. **Open GitHub:** Open your web browser, navigate to **GitHub.com**, and open your **`my-first-html-project`** repository.
13. **Go to Settings:** Click on the **Settings ⚙️** tab in the top horizontal menu bar of your repository page.
14. **Select Pages:** In the menu column on the left side of the screen, scroll down to the "Code and automation" section and click on **Pages**.
15. **Set the Branch:** Under the *Build and deployment* section, locate the **Branch** dropdown menu.
    * Click the dropdown that says **None** and change it to **`main`** (or `master`).
    * Keep the secondary folder dropdown set to **`/ (root)`**.
16. **Save:** Click the **Save** button.

---

## 🎯 The Result

Wait about **1 minute** for GitHub's servers to process your files, then **refresh the page**. At the top of that same **Pages** screen, a success box will appear showing your live URL (e.g., `https://yourusername.github.io/my-first-html-project/`). 

You can now click that link to see your website live, or share it with anyone in the world!
