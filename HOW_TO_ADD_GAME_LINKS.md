# 🎮 How to Add Your GitHub Game Links

## Step-by-Step Guide

### **Step 1: Find Your GitHub Username**

- Go to https://github.com/yourusername
- Replace `yourusername` with your actual GitHub username

---

### **Step 2: Open `index.html` in an Editor**

- Use Notepad, VS Code, or any text editor
- Find the **"GAMES & PROJECTS SECTION"** (around line 668)

---

### **Step 3: Update Each Game Card**

Each game card has two links to update:

#### **Link 1: GitHub Repository (View Code button)**

```html
<a href="https://github.com/yourusername/snake-game" target="_blank"></a>
```

**Change to:**

```html
<a href="https://github.com/YOUR-USERNAME/YOUR-REPO-NAME" target="_blank"></a>
```

**Example:**

```html
<a href="https://github.com/john-developer/snake-game" target="_blank"></a>
```

---

#### **Link 2: Deployed Game (Play button)**

```html
<a
  href="#"
  onclick="alert('Enter your deployed game URL here'); return false;"
></a>
```

**Change to:**

```html
<a href="https://your-deployed-game-url.com" target="_blank"></a>
```

**Examples:**

- `https://snake-game.netlify.app`
- `https://yourname.github.io/snake-game`
- `https://snake-game-demo.vercel.app`

---

## 🎯 Complete Example

### **Original Code:**

```html
<!-- Game 1 -->
<div class="service-card bg-white rounded-xl...">
  <div class="h-48 bg-gradient-to-br from-purple-500...">
    <i class="fas fa-snake text-white text-6xl"></i>
  </div>
  <div class="p-6">
    <h4 class="text-2xl font-bold text-gray-800 mb-2">Snake Game</h4>
    <p class="text-gray-600 mb-4">Classic snake game with smooth controls...</p>
    <div class="flex gap-3">
      <!-- View Code Button -->
      <a href="https://github.com/yourusername/snake-game" target="_blank">
        <i class="fab fa-github"></i>
        <span>View Code</span>
      </a>

      <!-- Play Button -->
      <a href="#" onclick="alert('Enter your deployed game URL here')">
        <i class="fas fa-play"></i>
        <span>Play</span>
      </a>
    </div>
  </div>
</div>
```

### **Updated Code (Your Details):**

```html
<!-- Game 1 -->
<div class="service-card bg-white rounded-xl...">
  <div class="h-48 bg-gradient-to-br from-purple-500...">
    <i class="fas fa-snake text-white text-6xl"></i>
  </div>
  <div class="p-6">
    <h4 class="text-2xl font-bold text-gray-800 mb-2">Snake Game</h4>
    <p class="text-gray-600 mb-4">Classic snake game with smooth controls...</p>
    <div class="flex gap-3">
      <!-- View Code Button -->
      <a href="https://github.com/john-developer/snake-game" target="_blank">
        <i class="fab fa-github"></i>
        <span>View Code</span>
      </a>

      <!-- Play Button -->
      <a href="https://snake-game.netlify.app" target="_blank">
        <i class="fas fa-play"></i>
        <span>Play</span>
      </a>
    </div>
  </div>
</div>
```

---

## 📝 List of Game Cards to Update

| Game             | Location  | GitHub Link | Play Link    |
| ---------------- | --------- | ----------- | ------------ |
| 1️⃣ Snake Game    | Line ~700 | `your-repo` | Deployed URL |
| 2️⃣ Tic Tac Toe   | Line ~750 | `your-repo` | Deployed URL |
| 3️⃣ Flappy Bird   | Line ~800 | `your-repo` | Deployed URL |
| 4️⃣ 2048 Game     | Line ~850 | `your-repo` | Deployed URL |
| 5️⃣ Space Shooter | Line ~900 | `your-repo` | Deployed URL |
| 6️⃣ Dice Roller   | Line ~950 | `your-repo` | Deployed URL |

---

## 🚀 How to Deploy Your Games for Free

### **Option 1: GitHub Pages (Easiest)**

1. Push your game to GitHub
2. Go to repository Settings
3. Find "Pages" section
4. Select `main` branch as source
5. Your game lives at: `https://yourusername.github.io/repo-name`

### **Option 2: Netlify (Recommended)**

1. Go to https://netlify.com
2. Connect your GitHub account
3. Select the game repository
4. Deploy automatically
5. Get a URL like: `https://your-game.netlify.app`

### **Option 3: Vercel**

1. Go to https://vercel.com
2. Import your GitHub repo
3. Deploy with one click
4. Get a URL like: `https://your-game.vercel.app`

---

## 🔗 Update Main GitHub Link

Also update this line (around line 1000):

```html
<a href="https://github.com/yourusername" target="_blank">
  View All Projects on GitHub
</a>
```

Change to:

```html
<a href="https://github.com/YOUR-ACTUAL-USERNAME" target="_blank">
  View All Projects on GitHub
</a>
```

---

## ✅ Quick Checklist

- [ ] Updated all 6 game GitHub links
- [ ] Added deployed URLs for games
- [ ] Updated the "View All Projects" link at bottom
- [ ] Tested all links by clicking them
- [ ] Saved the file

---

## 📞 Need Help?

If you have questions about:

- **GitHub:** google "how to push code to github"
- **Deploying:** Use Netlify or GitHub Pages (simplest options)
- **Website:** Contact your developer

---

**Happy Coding! 🎮**
