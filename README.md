# Matin Asadpour (bc1Matin) - Personal Portfolio & Resume

A modern, responsive, and printable single-page resume and portfolio website designed for instant zero-build deployment on **GitHub Pages**.

- **Live URL Target**: `https://bc1Matin.github.io`
- **GitHub Profile**: [github.com/bc1Matin](https://github.com/bc1Matin)

---

## 🚀 Features

- **Architectural Bento Matrix**: Custom layout faithfully mapping your development environment (Arch Linux / Omarchy, Neovim, Tmux/Herdr, Docker, AI tools), JS/TS ecosystem (Node.js, Deno, Bun, NestJS, Hardhat), and Blockchain stacks (Permaweb Arweave/AO, Bitcoin, EVM Solidity).
- **Hardhat ➔ Solidity Visual Bridge**: Dotted connection illustrating full-stack smart contract testing and deployment.
- **Accurate Personal Profile**:
  - **Bio**: Highlighting your M.A. in Philosophy & B.Sc. in Electrical Engineering.
  - **Links**: Proton Mail (`matinasadpour@proton.me`), LinkedIn, X (`@bc1Matin`), Bluesky, Instagram.
  - **Repositories**: HyperBEAM, Alpha Stock Engine, and Discord Radio Bot.
- **Theme Switcher**: Smooth Dark/Light mode toggle with `localStorage` memory and OS system-theme detection.
- **Print / PDF Ready**: Dedicated `@media print` styling connected to the **Resume PDF** button for clean paper or PDF export (`window.print()`).
- **Zero Build Tools Needed**: Pure HTML5 + Tailwind CSS (via CDN) + Lucide Icons.

---

## 📦 How to Deploy to GitHub Pages (`bc1Matin.github.io`)

### 1. Initialize Git in this Directory
```bash
cd /home/matin/Projects/iam
git init
git add .
git commit -m "feat: launch bc1Matin personal resume portfolio"
```

### 2. Create the Special GitHub Repository
1. Go to [GitHub - New Repository](https://github.com/new).
2. Name the repository exactly:
   ```text
   bc1Matin.github.io
   ```
3. Set visibility to **Public**.
4. Leave "Add a README file" unchecked (you already have this project ready).

### 3. Push Your Code
```bash
git branch -M main
git remote add origin https://github.com/bc1Matin/bc1Matin.github.io.git
git push -u origin main
```

### 4. Verify GitHub Pages Settings
1. On your repository page, click **Settings** > **Pages** (on the left menu).
2. Under **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main` and folder `/(root)`
3. Save. Within 1–2 minutes, your website will be live at:
   ```text
   https://bc1Matin.github.io
   ```

---

## 🛠️ Local Preview

To preview the website locally in your browser:
```bash
python3 -m http.server 8080
```
Then visit `http://localhost:8080` in your web browser.
