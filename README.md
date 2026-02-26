# Process, Data & Perspective — Personal Blog

A minimal, dark-themed personal blog by Aishwarya Baluri.  
Built with React (CDN) — no build step, no dependencies, just one HTML file.

## 🚀 Deploy to GitHub Pages — Step by Step

### Step 1: Create a GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Repository name: `blog` (or whatever you prefer)
3. Set it to **Public**
4. Check **"Add a README file"**
5. Click **Create repository**

### Step 2: Upload the File

1. In your new repo, click **"Add file"** → **"Upload files"**
2. Drag and drop the `index.html` file
3. Scroll down, click **"Commit changes"**

### Step 3: Enable GitHub Pages

1. Go to your repo → **Settings** tab
2. In the left sidebar, click **Pages**
3. Under **"Source"**, select **"Deploy from a branch"**
4. Under **"Branch"**, select **main** and folder **/ (root)**
5. Click **Save**

### Step 4: Access Your Site

- Wait 1-2 minutes for deployment
- Your blog will be live at: `https://YOUR-USERNAME.github.io/blog/`
- Example: `https://aishwaryabaluri.github.io/blog/`

## ✏️ How to Use

- **Add posts**: Click "+ New Post", fill in details, hit Publish
- **Edit posts**: Click "Edit" on any post
- **Delete posts**: Click "Delete" on any post
- **Filter by category**: Use the category buttons
- **Read full post**: Click the title or "Read" button

Posts are saved in your browser's localStorage — they persist across sessions on the same browser/device.

## 🎨 Customization

Everything is in one file (`index.html`). To customize:

- **Colors**: Search for `#d4af37` (gold accent) and `#0e0e0e` (background)
- **Categories**: Edit the `CATEGORIES` array
- **Your info**: Update name, email, and LinkedIn URL in the hero and footer sections
- **Sample posts**: Edit or remove the `SAMPLE_POSTS` array

## 📝 Important Note

Since this uses `localStorage`, posts are stored **per browser/per device**. If you want posts to persist across all devices, you'd need to upgrade to a backend (like Firebase, Supabase, or a headless CMS).
