# 🆕 Update Guide - Version 3 Features!

## ✨ What's New in Version 3

Your Bible verse apps now have **enhanced GUI** with better navigation and cleaner interface!

### New Features in v3:

#### 1️⃣ **Settings Modal (Popup Menu)** ⚙️
- Clean main menu - settings options now hidden in a popup
- Click "⚙️ 設定 | Settings" button to open modal
- Three options in modal:
  - 📊 View Statistics
  - 📤 Export Data
  - 🔄 Reset All Progress
- Click X or outside modal to close
- **Why this is better:** Main menu is cleaner and less cluttered!

#### 2️⃣ **Toggle Reveal/Hide Button** 🔄
- **Old way (v2):** Click "Reveal" once → verse shows forever
- **New way (v3):** Click to toggle between show/hide
  - First click: "Reveal 顯示" → Verse appears, button becomes "Hide 隱藏" (orange)
  - Second click: "Hide 隱藏" → Verse disappears, button becomes "Reveal 顯示" (green)
  - Repeat as many times as you want!
- **Why this is better:** Test yourself multiple times without going to next verse!

#### 3️⃣ **Navigation Arrows** ← →
- **Left Arrow (←):** Go to previous verse
- **Right Arrow (→):** Go to next verse
- Located on same line as Reveal/Hide button
- Disabled when at start (left) or end (right)
- **Why this is better:** Quick navigation without returning to menu!

#### 4️⃣ **All v2 Features Preserved** ✅
- Auto-Resume from last session
- Bookmarks (★)
- Statistics tracking
- Data export
- Offline support
- All 4 practice modes

---

## 📥 How to Update to Version 3

### Step 1: Download New Files

I've created 6 new v3 files:
- `14basic_pwa_v3.html` - Enhanced 14 Basic
- `tms60_pwa_v3.html` - Enhanced TMS 60
- `manifest_14basic_v3.json` - 14 Basic config
- `manifest_tms60_v3.json` - TMS 60 config
- `sw_14basic_v3.js` - 14 Basic service worker
- `sw_tms60_v3.js` - TMS 60 service worker

### Step 2: Upload to GitHub

1. **Go to your GitHub repository:**
   ```
   https://github.com/YOUR-USERNAME/bible-verses
   ```

2. **Upload all 6 new files:**
   - Click "Add file" → "Upload files"
   - Drag and drop all 6 files
   - Click "Commit changes"

3. **Wait 1-2 minutes** for GitHub Pages to update

### Step 3: Access v3 Apps

Your new URLs will be:
```
https://YOUR-USERNAME.github.io/bible-verses/14basic_pwa_v3.html
https://YOUR-USERNAME.github.io/bible-verses/tms60_pwa_v3.html
```

### Step 4: Install on iPhone

1. **Clear Safari cache first:**
   - Settings → Safari → Clear History and Website Data

2. **Open Safari and go to v3 URL**

3. **Add to Home Screen:**
   - Tap Share button (⬆️)
   - Scroll down → "Add to Home Screen"
   - Edit name if you want (e.g., "14 Basic v3")
   - Tap "Add"

4. **Done!** New v3 app icon appears on home screen

### Keep or Replace Old Versions?

**Option A: Keep Both (Recommended)**
- Keep v2 apps as backup
- Install v3 apps as separate icons
- Both versions work independently
- Different localStorage keys (won't interfere)

**Option B: Replace v2**
- Delete old v2 app icons from home screen
- Install only v3 apps
- Start fresh with new interface

---

## 🎯 How to Use New v3 Features

### Using the Settings Modal:

1. **On main menu**, look for "⚙️ 設定 | Settings" button at bottom
2. **Click the button** → Modal popup appears with 3 options
3. **Choose an option:**
   - 📊 View Statistics - See your practice stats
   - 📤 Export Data - Download backup JSON file
   - 🔄 Reset All Progress - Clear all data (asks for confirmation)
4. **Close modal:**
   - Click the X in top right
   - OR click outside the modal (grey area)

### Using Toggle Reveal/Hide:

**Basic Usage:**
1. Practice any mode (Sequential, Random, Review, Bookmarks)
2. Try to recite the verse from memory
3. Click "Reveal 顯示" → Verse text appears, button changes to "Hide 隱藏"
4. Read the verse to check your memory
5. Click "Hide 隱藏" → Verse disappears, button changes back to "Reveal 顯示"
6. Try to recite again from memory
7. Repeat steps 3-6 as many times as you want!

**Pro Tip:**
- Use toggle to test yourself multiple times per verse
- Only reveals count toward your "Total Practiced" statistic
- Hides don't affect stats - practice as much as you want!

### Using Navigation Arrows:

**Quick Navigation:**
1. While practicing, see three buttons in a row:
   ```
   [  ←  ] [ Reveal 顯示 ] [  →  ]
   ```
2. **Left Arrow (←):**
   - Click to go back to previous verse
   - Disabled (grey) when at first verse
   - Resets reveal state (starts hidden)
3. **Right Arrow (→):**
   - Click to go to next verse
   - Disabled (grey) when at last verse
   - Resets reveal state (starts hidden)
4. **"Back to Menu" button still below** - returns to main menu

**Use Cases:**
- **Skip verses:** Quickly jump to specific verse without finishing all
- **Review previous:** Go back to check a verse you just saw
- **Flexible practice:** Jump around instead of strict order
- **No need to finish:** Can stop anywhere, progress is saved

---

## 📊 v2 vs v3 Comparison

| Feature | v2 | v3 |
|---------|----|----|
| 4 Practice Modes | ✅ | ✅ |
| Auto-Resume | ✅ | ✅ |
| Bookmarks | ✅ | ✅ |
| Statistics | ✅ | ✅ |
| Data Export | ✅ | ✅ |
| Offline Support | ✅ | ✅ |
| **Settings Menu** | Visible buttons | Hidden in modal ⭐ |
| **Reveal Button** | One-time click | Toggle Reveal/Hide ⭐ |
| **Navigation** | Must finish/back to menu | Left/Right arrows ⭐ |
| **Main Menu** | Cluttered (6 buttons) | Clean (5 buttons) ⭐ |

---

## 🔄 Data Migration

### Will my v2 data transfer to v3?

**No - v2 and v3 use separate storage:**
- v2 storage keys: `14basic_progress`, `14basic_bookmarks`
- v3 storage keys: `14basic_progress_v3`, `14basic_bookmarks_v3`
- They don't interfere with each other
- Can use both versions side-by-side

### How to migrate data manually:

1. **In v2 app:** Export data (📤 Export Data)
2. **Download the JSON file**
3. **In v3 app:** There's no import feature (yet)
4. **Recommended:** Just start fresh in v3 with your muscle memory!

### Which version should I use?

**Use v3 if you want:**
- ✅ Cleaner interface
- ✅ Toggle reveal/hide for better memorization
- ✅ Navigation arrows for flexibility
- ✅ Modern, polished experience

**Keep v2 if you prefer:**
- Simple one-click reveal
- Don't need navigation arrows
- Want to keep existing progress

**Or use both!** They work independently.

---

## 🐛 Troubleshooting v3

### "Settings modal won't open"
- ✅ Make sure you uploaded all 6 v3 files
- ✅ Clear Safari cache and reload
- ✅ Check if JavaScript is enabled in Safari

### "Toggle button doesn't change color"
- ✅ This is normal if CSS didn't load
- ✅ Clear cache: Settings → Safari → Clear History
- ✅ Re-add to home screen

### "Navigation arrows not working"
- ✅ Arrows are disabled at start/end of verse list (this is normal)
- ✅ Try clicking middle verses where both arrows should work
- ✅ If still broken, re-upload files and clear cache

### "Modal appears behind content"
- ✅ This is a rare CSS issue
- ✅ Delete app icon and re-add from Safari
- ✅ Make sure using latest files

### "Can't close settings modal"
- ✅ Click the X button in top right
- ✅ Or click the grey area outside modal
- ✅ Refresh page if stuck

### "v3 app shows old v2 interface"
- ✅ You're opening wrong URL - check it ends with `_v3.html`
- ✅ Clear Safari cache completely
- ✅ Delete old icon and re-add from correct v3 URL

### "Lost all my v2 progress"
- ✅ Don't worry! v2 and v3 data are separate
- ✅ Open your v2 app - progress is still there
- ✅ v3 starts fresh with its own storage

---

## 💾 Storage Details

### v3 Storage Keys:

**14 Basic v3:**
- Progress: `14basic_progress_v3`
- Bookmarks: `14basic_bookmarks_v3`
- Stats: `totalPracticed`, `lastPractice`

**TMS 60 v3:**
- Progress: `tms60_progress_v3`
- Bookmarks: `tms60_bookmarks_v3`
- Stats: `totalPracticed_tms60`, `lastPractice_tms60`

### Data Safety:
- ✅ Stored locally on your iPhone
- ✅ Not uploaded to internet
- ✅ Private and secure
- ✅ Persists across app closes
- ✅ Persists across phone restarts
- ⚠️ Lost if you clear Safari data
- ⚠️ Lost if you delete app without backup

### Backup Recommendation:
1. **Use Export Data feature monthly**
2. **Save JSON file to iCloud or email**
3. **Keep backup in case you need to restore**

---

## 📱 Testing Your v3 Update

### Test Settings Modal:
1. Open v3 app
2. Click "⚙️ 設定" button
3. ✅ Modal should appear with 3 options
4. Click X or outside
5. ✅ Modal should close
6. Click button again
7. ✅ Modal should reappear (toggle works)

### Test Toggle Reveal/Hide:
1. Start any practice mode
2. See "Reveal 顯示" button (green)
3. Click it
4. ✅ Verse appears, button says "Hide 隱藏" (orange)
5. Click it again
6. ✅ Verse disappears, button says "Reveal 顯示" (green)
7. Repeat 3-6 several times
8. ✅ Should toggle smoothly each time

### Test Navigation Arrows:
1. Start Sequential mode
2. At verse 1, left arrow should be disabled (grey)
3. Click right arrow (→)
4. ✅ Should go to verse 2
5. Click left arrow (←)
6. ✅ Should go back to verse 1
7. Go to last verse
8. ✅ Right arrow should be disabled (grey)

### Test Offline:
1. Use v3 app once (loads and caches)
2. Turn on Airplane Mode ✈️
3. Close and reopen app
4. ✅ Everything works offline
5. ✅ Settings modal works
6. ✅ Toggle works
7. ✅ Navigation works
8. ✅ All features work without internet!

---

## 🎨 Interface Changes Summary

### Main Menu (Before Practice):
```
[Before v3]
📊 View Statistics
📤 Export Data  
🔄 Reset All Progress
👆 Three buttons taking space

[After v3]
⚙️ Settings
👆 One button - cleaner!
     (opens modal with 3 options)
```

### Practice Screen (During Practice):
```
[Before v2]
[ Reveal 顯示 ]
👆 One button, one-time use
[ Back to Menu ]

[After v3]
[  ←  ] [ Reveal 顯示 ] [  →  ]
👆 Three buttons in a row!
        Toggle + Navigate
[ Back to Menu ]
```

---

## 🚀 Pro Tips for v3

### Memorization Strategy:
1. **First time seeing verse:**
   - Read reference and topic
   - Try to recall from memory
   - Click Reveal → Check yourself
   - Click Hide immediately
   
2. **Second attempt (same verse):**
   - Try to recite again
   - Click Reveal → Verify
   - Click Hide
   - Repeat until perfect!

3. **Move on:**
   - Click right arrow (→) when ready
   - Or bookmark (★) for later review

### Bookmark Workflow:
1. While practicing, toggle Reveal/Hide multiple times
2. If verse is difficult, click ★ bookmark
3. Continue through other verses
4. Later: Choose "Mode 4: My Bookmarks"
5. Practice only your difficult verses!

### Navigation Tricks:
- **Quick review:** Use arrows to jump back 2-3 verses
- **Skip easy verses:** Arrow forward past verses you know well
- **Random navigation:** Jump around with arrows in Random mode
- **No pressure:** Can stop anywhere, progress auto-saves

### Settings Management:
1. **Check stats regularly:** Open modal → View Statistics
2. **Export monthly:** Open modal → Export Data → Save to iCloud
3. **Fresh start option:** Open modal → Reset (if you want clean slate)

---

## 🆚 Should You Upgrade from v2?

### Upgrade to v3 if:
- ✅ You want a cleaner main menu
- ✅ You want to test yourself multiple times per verse
- ✅ You want flexible navigation (back/forward)
- ✅ You like modern, polished interfaces
- ✅ You don't mind starting fresh with stats

### Stay on v2 if:
- ❌ You're happy with current simple interface
- ❌ You don't need navigation arrows
- ❌ You want to keep accumulated statistics
- ❌ "If it ain't broke, don't fix it" mindset

### Or do both:
- Install v3 as separate app
- Keep v2 for comparison
- Use whichever you prefer
- Delete the other later

---

## 📞 Need Help?

### Common Questions:

**Q: Can I have v2 and v3 at the same time?**
A: Yes! They're completely separate. Different URLs, different storage, different icons.

**Q: Will v3 replace v2 on my home screen?**
A: No. v3 installs as a new app icon. You manually delete v2 icon if you want.

**Q: How do I delete old v2 apps?**
A: Long press app icon → Remove App → Delete

**Q: What happens to my v2 bookmarks?**
A: They stay in v2. v3 starts with no bookmarks. Rebuild them in v3.

**Q: Can I use v3 offline?**
A: Yes! Works 100% offline after first load, just like v2.

**Q: Do I need to update again in the future?**
A: Only if I create v4 with new features. v3 works forever as-is.

**Q: Can I rename the app icon?**
A: Yes! When adding to home screen, edit the name field before tapping "Add".

---

## 🎉 Enjoy Your v3 Apps!

You now have the most polished version of the Bible verse practice apps!

### Key Improvements:
- 🎨 Cleaner interface
- 🔄 Better memorization with toggle
- ⬅️➡️ Flexible navigation
- ⚙️ Organized settings

### All v2 Features Preserved:
- 📝 4 practice modes
- 🔖 Bookmarks
- 💾 Auto-save progress
- 📊 Statistics
- 📤 Data export
- ✈️ Offline support

---

**Happy practicing! May God's Word dwell richly in your heart! 📖✨🙏**

*"Your word I have hidden in my heart, that I might not sin against You." - Psalm 119:11*

---

## 📋 Quick Reference Card

### v3 Button Guide:

| Button | What It Does |
|--------|--------------|
| ⚙️ 設定 | Opens settings modal (toggle) |
| ← | Previous verse (disabled at start) |
| Reveal 顯示 | Show verse text, becomes "Hide" |
| Hide 隱藏 | Hide verse text, becomes "Reveal" |
| → | Next verse (disabled at end) |
| ⬅ Back to Menu | Return to main menu |
| ☆ | Bookmark verse (empty star) |
| ★ | Unbookmark verse (filled star) |
| X | Close settings modal |

### Practice Flow:
1. Choose mode
2. Try to recite
3. Click Reveal → Check
4. Click Hide → Try again
5. Repeat 3-4 until perfect
6. Click → to next verse
7. Or ★ to bookmark for later

### Settings Modal Options:
- 📊 View Stats: See practice count, bookmarks, last date
- 📤 Export Data: Download JSON backup
- 🔄 Reset: Clear all progress (confirms first)

---

*End of v3 Update Guide*
