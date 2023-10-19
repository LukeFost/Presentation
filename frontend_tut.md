---
marp: true
theme: default
backgroundColor: '#f0f0f0'
---

### Workshop: Quick Start to Frontend for Smart Contracts

---

#### Welcome

- Introduction to frontend development for smart contracts
- Targeting EVM-based blockchains, DAGs, etc.
- Focusing on WalletConnect integration

---

#### Essential Tools

- Visual Studio Code (VSCode)
- Special development directory
- GitHub Desktop
- Node.js with npm
- **Note**: If you're comfortable with Git CLI, you may skip GitHub Desktop.

---

#### Initial Setup

1. Open a command prompt.
2. Navigate (`cd ..`) to the development directory.
3. Initialize your project:
   ```bash
   npm init wagmi --template next-web3modal
   ```

---

#### Update wagmi (Precaution)

- Run the following command to update wagmi to its latest version:
  ```bash
  npm i -g wagmi
  ```
- Recommended as a precautionary measure.

---

#### Project Configuration

1. Follow on-screen instructions.
2. Choose Next.js when prompted.
3. Sign in to WalletConnect and create a new project.
4. Copy the Project-ID into the command line.

---

#### GitHub and VSCode Setup

1. Create or add an existing GitHub repo.
2. Clone the repo in VSCode.
3. Run `npm install` to install dependencies.

---

#### Local Development

1. Run the dev server:
   ```bash
   npm run dev
   ```
2. Open your web browser to view your site.

---

#### Disable Linting (Optional)

- To speed up development, you may choose to disable linting.
- Add to `next.config.js`:
  ```js
  module.exports = { eslint: { ignoreDuringBuilds: true } }
  ```

---

#### Styling with TailwindCSS

1. Create `globals.css` in `/src/app`.
2. Add import in `layout.tsx`.
3. Install TailwindCSS:
   ```bash
   npm install -D tailwindcss postcss autoprefixer
   ```

---

#### TailwindCSS Configuration

- Edit `tailwind.config.js` to specify the content folders.
- Run `npx tailwindcss init -p`.

---

#### Verify TailwindCSS Installation

- Add the following to `page.tsx`:
  ```jsx
  <h1 className="text-3xl font-bold underline">Hello world!</h1>
  ```

---

#### Style Packs with DaisyUI

1. Install DaisyUI:
   ```bash
   npm i -D daisyui@latest
   ```
2. Update `tailwind.config.js` to include DaisyUI in plugins.

---

#### Verify DaisyUI Installation

- Add to `page.tsx`:
  ```jsx
  <button className="btn btn-primary">Primary</button>
  ```

---

#### Deployment with Vercel

1. Visit vercel.com and log in.
2. Link your GitHub account.
3. Import your repo and follow the build steps.

---

#### Thank You!

- Feel free to ask questions for further clarification.

Now your presentation is structured to deliver your informative goal in a clear and organized manner.