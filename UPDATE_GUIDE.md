# 🆕 Update Guide - New Features Added!

## ✨ What's New in Version 2

Your Bible verse apps now have **local storage** to save your progress!

### New Features:

#### 1️⃣ **Auto-Resume** 🔄
- App remembers where you left off
- Orange banner at top when you have saved progress
- Click to resume from exact verse
- **Works even after closing app or phone restart!**

#### 2️⃣ **Bookmarks** 🔖
- Star (★) button on each verse card
- Tap to bookmark difficult verses
- New "My Bookmarks" mode to practice only starred verses
- Bookmark count shown in header

#### 3️⃣ **Statistics** 📊
- Total verses practiced counter
- Last practice date
- Bookmark count
- All displayed in header bar

#### 4️⃣ **Data Management** ⚙️
- Reset all progress button
- Export your data as JSON file
- View detailed statistics

---

## 📥 How to Update Your Apps

### Step 1: Download New Files

I've created:
- `14basic_pwa_v2.html` - Enhanced 14 Basic with storage
- (TMS60 v2 coming if you want it)

### Step 2: Upload to GitHub

1. **Go to your GitHub repository:**
   ```
   https://github.com/YOUR-USERNAME/bible-verses
   ```

2. **Option A: Replace the old file**
   - Click on `14basic_pwa.html`
   - Click the trash icon (🗑️) to delete it
   - Click "Commit changes"
   - Click "Add file" → "Upload files"
   - Upload `14basic_pwa_v2.html`
   - **IMPORTANT:** Rename it to `14basic_pwa.html` (remove the `_v2`)
   - Click "Commit changes"

3. **Option B: Keep both versions**
   - Just upload `14basic_pwa_v2.html` alongside the old one
   - Access via: `https://YOUR-USERNAME.github.io/bible-verses/14basic_pwa_v2.html`

### Step 3: Clear iPhone Cache

1. Open **Settings** on iPhone
2. Scroll to **Safari**
3. Scroll down → **"Clear History and Website Data"**
4. Tap "Clear"

### Step 4: Reload the App

1. Delete old app icon from home screen (long press → Remove)
2. Open Safari and go to your app URL
3. Add to Home Screen again
4. Done! New version is installed

---

## 🎯 How to Use New Features

### Auto-Resume:
1. Start practicing (any mode)
2. Close the app (swipe up or go home)
3. Open app again
4. See orange banner: "🔄 繼續上次練習 | Resume from last session"
5. Click banner → continues from exact verse!

### Bookmarks:
1. While practicing, tap the ★ button (top right of verse card)
2. Star turns gold (★) when bookmarked
3. Go back to menu
4. Choose "🔖 模式四：我的書籤" (Mode 4: My Bookmarks)
5. Practice only your bookmarked verses!

### View Statistics:
1. On main menu, scroll down to Settings panel
2. Click "📊 View Statistics"
3. See your progress summary

### Export Data:
1. Click "📤 Export Data" in settings
2. Downloads a JSON file with all your progress
3. Backup for safekeeping or transfer to another device

### Reset Progress:
1. Click "🔄 Reset All Progress"
2. Confirms before deleting
3. Clears all saved data and bookmarks

---

## 📱 Testing Your Update

### Test Auto-Resume:
1. Open app
2. Choose Sequential mode
3. Reveal a few verses
4. Go to verse 5 or so
5. Close app completely
6. Open app again
7. ✅ Should see orange "Resume" banner
8. Click it
9. ✅ Should continue from verse 5

### Test Bookmarks:
1. Start any mode
2. Tap the ☆ on a few verses
3. ☆ should turn to ★
4. Go back to menu
5. Choose "My Bookmarks" mode
6. ✅ Should see only your starred verses

### Test Offline:
1. Use app once (loads data)
2. Turn on Airplane Mode ✈️
3. Close and reopen app
4. ✅ Resume banner still works
5. ✅ Bookmarks still there
6. ✅ Everything works offline!

---

## 🔧 Troubleshooting

### "Resume banner not appearing"
- ✅ Practice at least 1 verse first
- ✅ Make sure you uploaded the v2 file
- ✅ Clear Safari cache and reload

### "Bookmarks not saving"
- ✅ Make sure you're using v2 file
- ✅ Check if iPhone has enough storage
- ✅ Try Safari Settings → Advanced → Website Data → Remove all

### "Statistics showing 0"
- ✅ Normal for first time - practice some verses first
- ✅ Counter increases when you click "Reveal"

### "Old app still showing"
- ✅ Delete app icon from home screen
- ✅ Clear Safari cache in Settings
- ✅ Re-add to home screen

---

## 💾 Where is Data Stored?

### Storage Location:
- **localStorage** in your iPhone Safari browser
- Stored locally on your device only
- NOT uploaded to internet
- Private and secure

### Storage Size:
- Very small (few KB)
- Plenty of space for progress
- Won't use noticeable storage

### Data Persistence:
- Survives app closes ✅
- Survives phone restarts ✅  
- Survives Safari closes ✅
- **Lost if you clear Safari data** ⚠️
- **Lost if you delete app and don't re-add from same URL** ⚠️

### Backup Your Data:
Use the "Export Data" feature regularly to save a backup file!

---

## 🆚 Version Comparison

| Feature | Old Version | New Version v2 |
|---------|-------------|----------------|
| 3 Practice Modes | ✅ | ✅ |
| Offline Support | ✅ | ✅ |
| Progress Bar | ✅ | ✅ |
| **Auto-Resume** | ❌ | ✅ NEW! |
| **Bookmarks** | ❌ | ✅ NEW! |
| **Statistics** | ❌ | ✅ NEW! |
| **Data Export** | ❌ | ✅ NEW! |
| **4th Mode (Bookmarks)** | ❌ | ✅ NEW! |

---

## 🎉 You're All Set!

Your apps now remember your progress and let you bookmark verses! 

### Pro Tips:
1. **Bookmark difficult verses** during practice
2. **Review bookmarks** before tests or presentations  
3. **Export data** monthly as backup
4. **Check statistics** to track your dedication

---

## 🤔 Want TMS 60 v2 Too?

Should I create the same enhanced version for TMS 60?

Just let me know and I'll create:
- `tms60_pwa_v2.html` with all the same features
- Auto-resume for 60 verses
- Bookmarks for longer study
- Statistics tracking

---

**Enjoy your enhanced Bible verse practice! 📖✨🙏**

*"Your word I have hidden in my heart, that I might not sin against You." - Psalm 119:11*