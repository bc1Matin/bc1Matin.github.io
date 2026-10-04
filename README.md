# Matin Asadpour (bc1Matin) - Personal Portfolio & Resume

**Decentralized Systems Architect | Blockchain Researcher & Developer**

A modern, responsive, and printable single-page resume and portfolio website designed for instant zero-build deployment on **GitHub Pages**.

- **Live URL Target**: `https://bc1Matin.github.io`
- **GitHub Profile**: [github.com/bc1Matin](https://github.com/bc1Matin)
- **Contact Email**: `bc1Matin@gmail.com`

---

## 🚀 Key Features

- **Architectural Bento Matrix**: Custom layout mapping:
  - **Dev Environment**: Arch Linux (Omarchy), Neovim, Tmux/Herdr, Docker, AI tools (Gemini, Antigravity, Grok).
  - **JS/TS Ecosystem**: Node.js, Deno, Bun, NestJS, and Hardhat.
  - **PermaWeb Matrix**: Explicit separation of **Programming Languages** (`Lua` for AO Smart Contracts, `Erlang` for BEAM concurrency) from **Protocols, Runtimes & Gateways** (`HyperBEAM`, `AR.io`, `WAO`).
  - **Bitcoin & Ethereum**: Bitcoin Core, Lightning Network, Ordinals, and Solidity with an animated bridge to Hardhat.
- **Accurate Personal Profile**:
  - **Location**: Citizen of the World (Universal / Non-geographical).
  - **Education**: M.A. in Philosophy (Decentralization, Ethics & Autonomy) & B.Sc. in Electrical Engineering.
  - **Repositories**: Alpha Stock Engine, HyperBEAM (Research Fork), and Discord Radio Bot.
- **Theme Switcher**: Smooth Dark/Light mode toggle with `localStorage` memory and OS system-theme detection.
- **Print / PDF Ready**: Dedicated `@media print` styling connected to the **Resume PDF** button for clean paper or PDF export (`window.print()`).
- **Clean & Fast**: Zero build dependencies, pure inline SVGs, zero console warnings.

---

## 📦 How to Deploy to GitHub Pages (`bc1Matin.github.io`)

### 1. Stage and Commit in this Directory
```bash
cd /home/matin/Projects/iam
git add .
git commit -m "feat: update title, email, and refined Permaweb architecture"
```

### 2. Push Your Code
```bash
git branch -M main
git remote add origin https://github.com/bc1Matin/bc1Matin.github.io.git
git push -u origin main
```

### 3. Verify GitHub Pages Settings
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
