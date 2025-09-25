# 🛠️ Developer Reference – Git Workflow & Project Commands

This section provides a handy list of Git and development commands for managing the project.

---

## 🧹 Clean Up Old Directory (Windows)

```bash
rmdir /s /q "C:\xampp\htdocs\backend_project_2025\LMS-Adaptive-Quizzes-AI-Backend"


## 📦 Clone the Repository
git clone https://github.com/KDA-Creative/Interactive-Campus-Navigation-Kiosk-in-Eastern-Visayas-State-University-Ormoc-Main-Campus.git

## 🌿 Branch Management
### 🔍 View All Branches
git branch -a

###🔀 Switch to an Existing Branch
git switch Test-System
git switch feature/auth
git switch feature/save_building_data

### 🌱 Create and Switch to New Branches
git switch -c feature/logout-redirect
git switch -c feature/auth
git switch -c feature/backend-analytics
git switch -c feature/backend-analytics-latest
git switch -c feature/manage-account-crud
git switch -c feature/save_building_data

## 💾 Staging and Committing Changes
### ✅ Stage Changes
git add .

### 📝 Commit Changes
git commit -m "report_v.1"
git commit -m "backend-analytics-latest"
git commit -m "Manage account - loading - crud"
git commit -m "Save Buildings Data in file"
git commit -m "logout - redirect in web"

## 🚀 Push Changes to Remote
### 🌐 Push to Origin
git push

### 📤 Push Feature Branches
git push -u origin feature/logout-redirect
git push -u origin feature/auth
git push -u origin feature/backend-analytics
git push -u origin feature/backend-analytics-latest
git push -u origin feature/manage-account-crud
git push -u origin feature/save_building_data

## 🧽 Delete Branches
### 🗑️ Delete Local Branches
git branch -d feature/save_building_data
git branch -d feature/logout-redirect
git branch -d logout-redirect
git branch -d feature/auth

### 🔥 Force Delete Local Branch
git branch -D feature/save_building_data

### ❌ Delete Remote Branches
git push origin --delete feature/save_building_data
git push origin --delete feature/auth
git push origin --delete feature/logout-redirect


---

### ✅ You can now copy and paste this directly into your `README.md`.

Would you like to include the `npm` commands section (to run backend/desktop/web) at the bottom too? I can add that in the same style if needed.


