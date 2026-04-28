# 📖 Spell Compendium — Owlbear Rodeo Extension

A D&D 5e spell reference panel embedded directly inside Owlbear Rodeo.  
Powered by the free [Open5e API](https://open5e.com). No login required.

---

## ✨ Features

- Full SRD spell list — **2024 edition** and **2014 edition**
- Search by name in real time
- Filter by spell level, school of magic
- Full spell details: casting time, range, components, duration, classes, description, upcast rules
- Concentration indicators
- Dark grimoire aesthetic that fits right into a VTT session

---

## 🚀 How to Host on GitHub Pages (Free — No Coding Needed)

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up for a free account if you don't have one.

### Step 2 — Create a new repository
1. Click the **+** icon (top right) → **New repository**
2. Name it: `obr-spell-compendium`
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload the files
1. On your new repo page, click **Add file → Upload files**
2. Drag and drop ALL three files:
   - `manifest.json`
   - `index.html`
   - `icon.svg`
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repo **Settings** tab
2. In the left sidebar, click **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Choose **main** branch, **/ (root)** folder
5. Click **Save**
6. Wait ~1 minute, then your extension will be live at:
   ```
   https://YOUR_USERNAME.github.io/obr-spell-compendium/manifest.json
   ```
   *(Replace YOUR_USERNAME with your GitHub username)*

---

## 🦉 How to Add to Owlbear Rodeo

### Step 1 — Go to your Profile
1. Open [owlbear.rodeo](https://www.owlbear.rodeo)
2. Click your avatar / profile icon (top right)
3. Select **My Extensions**

### Step 2 — Add the extension
1. Click **Add Extension**
2. Paste your manifest URL:
   ```
   https://YOUR_USERNAME.github.io/obr-spell-compendium/manifest.json
   ```
3. Click **Add**

### Step 3 — Enable in a Room
1. Create a new room (or open an existing one)
2. In the **Create Room** dialog, or from room settings, enable **Spell Compendium**
3. Once inside the room, you'll see the **book icon** in the top-left toolbar
4. Click it to open the spell panel! 📖

---

## 🔮 Using the Extension

| Feature | How |
|---|---|
| Search a spell | Type in the search box |
| Filter by level | Use the Level dropdown |
| Filter by school | Use the School dropdown |
| Switch editions | Click **2024** or **2014** button |
| Read a spell | Click any spell in the list |
| Go back | Click **← Back** |

---

## 📝 Notes

- **Spells available**: All spells from the D&D 5e SRD (Systems Reference Document). This covers the vast majority of core spells. Spells exclusive to non-SRD sourcebooks are not included due to copyright.
- **2024 edition**: Uses the revised 2024 SRD spells where available.
- **Internet required**: Spell data is fetched live from api.open5e.com.

---

## 🛠 Troubleshooting

| Problem | Solution |
|---|---|
| "Could not reach the spell archives" | Check your internet connection |
| Extension not appearing in room | Make sure it's enabled in room settings |
| Manifest URL not working | Wait a couple of minutes after enabling GitHub Pages |
