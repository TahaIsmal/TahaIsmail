# 💫 About Me:
AI Engineer working across Artificial Intelligence, Machine Learning, and AI Automation, building intelligent systems, models, and automated solutions.


## 🌐 Socials:
[![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?logo=Facebook&logoColor=white)](https://facebook.com/https://www.facebook.com/share/1APSeWy8wZ/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/www.linkedin.com/in/taha-esmail-61247229a) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:tahaesamil7@gmail.com) 

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase) ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) ![Firebase](https://img.shields.io/badge/firebase-a08021?style=for-the-badge&logo=firebase&logoColor=ffcd34) ![Adobe Photoshop](https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Scipy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![Adobe Illustrator](https://img.shields.io/badge/adobe%20illustrator-%23FF9A00.svg?style=for-the-badge&logo=adobe%20illustrator&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=TahaIsmail&theme=shadow_green&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=TahaIsmail&theme=shadow_green&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=TahaIsmail&theme=shadow_green&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=TahaIsmail&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->



# 🎓 University App - UI Development Phase

A robust, scalable mobile application built with **Flutter** following the **Clean Architecture** principles. This project serves as a comprehensive digital portal for university students, enabling them to explore academic programs, engage with the community, and manage their profiles efficiently.

---

## 🏗 Project Structure
The project is organized into modular layers to ensure separation of concerns and ease of collaboration:
```text
lib/
├── main.dart                 # Application entry point
├── bootstrap.dart            # Initialization logic
├── app/                      # Global App Configuration
│   ├── routes/               # Navigation & Routing system
│   ├── di/                   # Dependency Injection (Get_it)
│   ├── theme/                # Design System (Colors, Typography, Spacing)
│   └── config/               # API & Environment configurations
├── core/                     # Core Shared Logic
│   ├── error/                # Exception & Failure handling
│   ├── network/              # Dio Client & API wrappers
│   ├── utils/                # Helper functions & Validators
│   ├── services/             # Local & External services (Storage, Analytics)
│   └── widgets/              # Global reusable UI components
├── features/                 # Modular Business Features
│   ├── auth/                 # Authentication & User Identity
│   ├── university/           # University Search & Discovery
│   ├── community/            # Social Feed & Engagement
│   ├── news/                 # Academic Updates
│   ├── programs/             # Educational Tracks
│   ├── profile/              # User Management
│   ├── chatbot/              # AI Assistant
│   └── comparison/           # University Comparison tools
├── shared/                   # Cross-feature shared models & widgets
└── assets/                   # Images, Icons, Fonts, and Animations

---

## 👥 Development Teams & Task Distribution

To ensure smooth collaboration and avoid merge conflicts, the UI work is divided into two main tracks:

### 🚀 Developer A: Authentication & Profile Journey
**Focus:** User onboarding, security UI, and global design system.
- **Auth Module:** Welcome, Login, Signup, OTP Verification, and Reset Password screens.
- **Profile Module:** Student profile dashboard, settings, and edit profile UI.
- **Global Widgets:** Implementation of `CustomButton`, `CustomTextField`, and `AppBars` in `core/widgets/`.
- **Navigation:** Setting up the `BottomNavigationBar` and Route transitions.

### 🎨 Developer B: Content, Community & Utilities
**Focus:** Discovery, social interaction, and specialized features.
- **University & Programs:** Discovery feed, advanced filters, and detailed University/Program info pages.
- **Community Module:** News feed, post cards, comments section, and "Create Post" interface.
- **News Module:** University news listing and article view.
- **Special Features:** Chatbot interface and University comparison tables.

---

## 🛠 UI Coding Standards
To maintain a consistent Look & Feel, please follow these rules:
1. **Theme First:** Never hardcode colors or font sizes. Always use:
   - Colors: `AppColors.primary`, etc., from `app/theme/colors.dart`.
   - Typography: Use defined styles from `app/theme/typography.dart`.
2. **Reusability:** If a widget (like a card or a header) is used in more than one feature, move it to `shared/widgets/`.
3. **Responsiveness:** Use the spacing constants from `app/theme/spacing.dart` to ensure consistency across different screen sizes.
4. **Assets:** Place all images in `assets/images/` and icons in `assets/icons/`. Ensure they are declared in `pubspec.yaml`.

---

## 🚦 Git Workflow & Collaboration
- **Branching:** Create a branch for each task: `ui/auth-screens` or `ui/community-feed`.
- **Pull Requests:** Before merging to `main`, a PR must be opened and reviewed by the team lead.
- **Sync:** Run `flutter pub get` frequently to stay updated with any new packages added by your teammate.

---
