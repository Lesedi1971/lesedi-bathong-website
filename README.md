# Lesedi Bathong Website — Deployment Guide
## How to get your website live on Netlify (free)

---

### WHAT YOU NEED BEFORE YOU START
- A GitHub account (free) — sign up at https://github.com
- A Netlify account (free) — sign up at https://netlify.com using your Gmail: lesedibathong@gmail.com

---

### STEP 1 — Upload your website files to GitHub

1. Go to https://github.com and log in
2. Click the **+** button (top right) → **New repository**
3. Name it: `lesedi-bathong-website`
4. Set it to **Public**
5. Click **Create repository**
6. On the next screen, click **uploading an existing file**
7. Drag ALL the files and folders from the zip you downloaded into the upload area:
   - `index.html`
   - `netlify.toml`
   - `admin/` (the whole folder)
   - `_data/` (the whole folder)
   - `images/` (the whole folder)
8. Click **Commit changes**

---

### STEP 2 — Connect to Netlify

1. Go to https://netlify.com and log in
2. Click **Add new site** → **Import an existing project**
3. Choose **GitHub**
4. Authorise Netlify to access your GitHub account
5. Select your `lesedi-bathong-website` repository
6. Leave all settings as they are
7. Click **Deploy site**
8. Wait about 1 minute — your site will be live!
9. Netlify gives you a random address like `happy-sun-abc123.netlify.app`
   — you can rename this under **Site settings → Domain management → Options → Edit site name**
   — change it to `lesedibathong` so your address becomes `lesedibathong.netlify.app`

---

### STEP 3 — Enable the Admin Panel (Netlify Identity + Git Gateway)

This lets you log in to add projects, friends, and photos without touching any code.

1. In your Netlify dashboard, go to **Site settings → Identity**
2. Click **Enable Identity**
3. Under **Registration**, choose **Invite only** (so only you can log in)
4. Scroll down to **Services → Git Gateway** → click **Enable Git Gateway**
5. Go to **Identity → Invite users**
6. Enter your email: `lesedibathong@gmail.com`
7. Check your email and accept the invitation — set a password

---

### STEP 4 — Log in to your Admin Panel

1. Go to: `https://lesedibathong.netlify.app/admin`
2. Log in with `lesedibathong@gmail.com` and the password you set
3. You will see three sections:
   - **Projects** — add, edit, or remove projects
   - **Friends of Lesedi Bathong** — add supporters and partners
   - **Photo Gallery** — upload photos with captions

---

### HOW TO ADD A PHOTO

1. Log in to `/admin`
2. Click **Photo Gallery** → **New Photo**
3. Click the image upload button — choose a photo from your computer or phone
4. Add a caption (e.g. "Food parcel drive, June 2025")
5. Choose a section (Home, Projects, Friends, General)
6. Click **Publish**
7. Wait 1–2 minutes — the photo appears on your website automatically

---

### HOW TO ADD A PROJECT

1. Log in to `/admin`
2. Click **Projects** → **New Project**
3. Fill in the title, category tag, and description
4. Make sure **Active** is turned on
5. Click **Publish**

---

### HOW TO ADD A FRIEND / SUPPORTER

1. Log in to `/admin`
2. Click **Friends of Lesedi Bathong** → **New Friend**
3. Enter their name, type (Individual / Church / Business / Organisation), and an optional note
4. Click **Publish**

---

### CONTACT & SUPPORT

If you get stuck at any step, bring this guide and your question back to Claude at claude.ai — we can walk through it together.

Website: lesedibathong.netlify.app (once deployed)
Email: lesedibathong@gmail.com
WhatsApp: +27 84 441 5119
NPO Registration: 2025/490145/08
