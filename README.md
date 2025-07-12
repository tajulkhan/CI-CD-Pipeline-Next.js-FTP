# 🚀 Next.js SFTP CI/CD Deployment with GitHub Actions

This project demonstrates a simple and secure CI/CD pipeline that builds a **Next.js app** and deploys it to a remote server via **SFTP**, using **GitHub Actions**.

---

## 📦 Stack

- ⚙️ [Next.js](https://nextjs.org/)
- 💡 GitHub Actions
- 🔐 SFTP Deployment (`wlixcc/SFTP-Deploy-Action`)

---

## 📁 Project Structure

```bash
my-next-app/
├── .github/
│   └── workflows/
│       └── deploy.yml        # CI/CD pipeline config
├── pages/
├── public/
├── styles/
├── out/                      # Static files (after export)
├── package.json
└── README.md
