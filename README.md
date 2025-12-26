# 🚀 Node.js CI/CD Pipeline Demo

![CI Status](https://github.com/Karma-tic/my-cicd-project/actions/workflows/main.yml/badge.svg)
![Deployment](https://img.shields.io/badge/Vercel-Deployed-black?logo=vercel)
![Node Version](https://img.shields.io/badge/node-20.x-green)

A demonstration project showcasing a complete **DevOps lifecycle** using Node.js, GitHub Actions, and Vercel. This project implements a fully automated pipeline where code is tested, integrated, and deployed to production automatically upon every push.

## 🛠 Tech Stack

- **Runtime:** Node.js (Express)
- **Testing:** Jest
- **CI (Continuous Integration):** GitHub Actions
- **CD (Continuous Deployment):** Vercel
- **API Testing:** Postman

---

## ⚙️ How It Works

1.  **Develop:** Code changes are made locally on the `main` branch.
2.  **Push:** Changes are pushed to GitHub.
3.  **Test (CI):** GitHub Actions triggers a workflow (`.github/workflows/main.yml`) to install dependencies and run unit tests (`npm test`).
4.  **Deploy (CD):** If tests pass, Vercel automatically pulls the new code, builds it, and updates the live URL.

---

## 📦 Getting Started Locally

Follow these steps to run the project on your machine.

### Prerequisites
- Node.js (v18 or higher)
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone [https://github.com/Karma-tic/my-cicd-project.git](https://github.com/Karma-tic/my-cicd-project.git)
   cd my-cicd-project
   Install dependenciesBashnpm install
Start the serverBashnpm start
The app will run at http://localhost:3001.🧪 Running TestsThis project uses Jest for unit testing. The tests verify basic logic (e.g., math operations) to ensure the build is stable before deployment.To run tests manually:Bashnpm test
📂 Project Structuremy-cicd-project/
├── .github/workflows/   # CI Configuration (GitHub Actions)
├── node_modules/        # Dependencies
├── index.js             # Main application entry point (Express Server)
├── math.js              # Sample logic module for testing
├── math.test.js         # Unit tests for math.js
├── package.json         # Project metadata and scripts
└── README.md            # Project documentation
🌐 API EndpointsMethodEndpointDescriptionGET/Returns the Hello World welcome message.📝 LicenseThis project is open source and available under the MIT License.
### **Step 3: Commit and Push**

Now, let's send this documentation to GitHub so it appears on your repository's front page.

```bash
git add README.md
git commit -m "docs: Add project documentation and CI badges"
git push
