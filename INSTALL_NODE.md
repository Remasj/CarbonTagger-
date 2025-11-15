# 📦 Installing Node.js on macOS

You need Node.js to run this project. Here are the easiest ways to install it:

## Method 1: Direct Download (Easiest) ⭐

1. **Visit the Node.js website:**
   - Go to: https://nodejs.org/
   - Click the big green "LTS" button (recommended version)

2. **Download and Install:**
   - Download the `.pkg` installer for macOS
   - Double-click the downloaded file
   - Follow the installation wizard (just click "Next" through all steps)
   - This will install both Node.js and npm

3. **Verify Installation:**
   - Open a new Terminal window
   - Run: `node --version`
   - Run: `npm --version`
   - You should see version numbers

4. **Then run the project:**
   ```bash
   cd /Users/remasaljifri/demo
   npm install
   npm run dev
   ```

## Method 2: Using Homebrew (For Developers)

If you prefer using Homebrew:

1. **Install Homebrew first:**
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

2. **Install Node.js:**
   ```bash
   brew install node
   ```

3. **Verify:**
   ```bash
   node --version
   npm --version
   ```

## Method 3: Using nvm (Node Version Manager)

If you want to manage multiple Node.js versions:

1. **Install nvm:**
   ```bash
   curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
   ```

2. **Restart Terminal or run:**
   ```bash
   source ~/.zshrc
   ```

3. **Install Node.js:**
   ```bash
   nvm install --lts
   nvm use --lts
   ```

## After Installation

Once Node.js is installed, come back to this directory and run:

```bash
cd /Users/remasaljifri/demo
npm install
npm run dev
```

Then open http://localhost:3000 in your browser!

---

**Recommendation:** Use Method 1 (Direct Download) - it's the simplest and fastest! 🚀

