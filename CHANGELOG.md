# Changelog

All notable changes to **Slashboard Sinhala Keyboard (Android & Windows PC)** will be documented in this file.

---

## [4.2.6] - 2026-11-25 (versionCode 52)

### 🖥️ Slashboard Windows Integration (PC Edition)
- **Official Windows PC Keyboard & Typing Companion:** Integrated **Slashboard Windows** support for Windows PC users, enabling seamless Singlish and Sinhala phonetic typing, fast Unicode conversion, and workspace utilities across both Android and Windows platforms (`https://dinushlakmal.github.io/Slashboard-sinhala-Keyboard/`).

### 🔒 Direct Privacy Policy & Google Play Compliance
- **Official Privacy Policy URL Integration:** Added direct in-app and web links to `https://dinushlakmal.github.io/Slashboard-sinhala-Keyboard/privacy.html` inside the Privacy Policy dialog, Settings action rows, and Home Privacy disclosure cards.
- **Data Safety Compliance:** Reaffirmed 100% offline, zero-tracker, and secure on-device processing guarantees.

### 💼 Smart Wallet ("මුදල් පොත") Delete Fix & Enhancements
- **Clean Item Deletion & Instant Balance Refresh:** Fixed Smart Wallet transaction deletion so that added income/expense items delete cleanly and update account balances instantly with visual feedback and Room DB synchronization.

### ⚙️ Default Settings & UX Polishes
- **Recent Suggestions Default OFF:** Recent suggestions are now disabled by default for a cleaner default typing experience (can be enabled anytime in Typing Settings).
- **1-Second Splash Animation Limit:** Capped app return/re-entry loading animation to exactly 1.0 second (`1000ms`) for maximum responsiveness.
- **Expanded WhatsApp Emojis & Clean Emoji Styles:** Added full WhatsApp smileys, hearts, gestures, and people categories, and removed redundant "Open-Source CDN" wording from the Emoji Style UI.

---

## [4.2.4] - 2026-11-22 (versionCode 50)

### 🖼️ New Categorized Theme Wallpapers & Ultra-Fast Loading
- **15 Diverse Categories (95+ Wallpapers):** Added **🇱🇰 Sri Lanka & Heritage**, **✨ Luxury & Gold**, **💖 Love & Romantic**, and **🏙️ City & Nightlife**, expanded existing categories with deduplicated images, and bundled **5 instant offline HD artworks** (`⚡ Instant`).
- **Blazing-Fast Loading Engine:** Switched grid previews to 15x smaller `360px` WebP thumbnails, true lazy grid rendering, background prefetching, shared persistent disk/memory Coil caching, `RGB_565` decoding, and category gradient placeholders.

---

## [4.2.3] - 2026-11-19 (versionCode 49)

### 🧠 Sequential Next-Word Recent Suggestions & Instant Top Bar Control
- **Continuous Next-Word Chain Learning:** ඔබ එක දිගට ටයිප් කරන වාක්‍ය රටා (උදා: `"මං ඔයාට ආදරෙයි"`) bigram/trigram ලෙස සුරක්ෂිතව ඉගෙනගෙන, ටයිප් කරන විටම ඊළඟ වචනය (`මං` -> `ඔයාට` -> `ආදරෙයි`) අඛණ්ඩව යෝජනා කරයි.
- **Typing-Only Visibility & Instant Top Bar Reveal:** Recent Suggestions පෙන්වන්නේ වචනයක් ටයිප් කරන විට හෝ chain select කරන විට පමණි. Space එබූ සැණින් හෝ මගදී Backspace එබූ සැණින් Top Bar එක ක්ෂණිකව දිස්වේ.

### ✨ Smooth Zero-Delay Slide-In Fade Animations
- **Crisp Visual Feedback:** Space, Backspace හෝ suggestion selection එකෙන් පසු Top Bar icons, next-word chips, සහ inline suggestions කිසිදු පමාවකින් තොරව (`0ms`) සුමට slide-in fade animation එකකින් දිස්වේ.

### 💾 POS & Smart Wallet Draft Persistence
- **Zero Lost Typing on Accidental Back:** Mini-POS (Quick Bill, Customer Book, Catalog, History), Smart Wallet (මුදල් පොත), සහ Keyboard POS/Wallet boards තුළ ටයිප් කරමින් සිටියදී Back press කළත්, tabs මාරු කළත්, වෙනත් ඇප් එකකට ගියත් හෝ keyboard hide වුණත්, ඇප් එකෙන් සම්පූර්ණයෙන්ම පිටවන තුරු හෝ Save/Clear කරන තුරු ඔබ ටයිප් කළ දත්ත රැඳී පවතී.

---

## [4.2.2] - 2026-11-19

### 💼 Smart Wallet ("මුදල් පොත") — Reimagined Money & Expense Tracker
- **New User-Friendly Identity:** Cashbook විශේෂාංගය වඩාත් පහසු **"💼 මුදල් පොත (Smart Wallet)"** නමින් නැවත හඳුන්වා දෙන ලදී.
- **⚡ 1-Tap Instant Log & Inline Entry:** දෛනික වියදම්/ආදායම් (තේ, බස්, දිවා ආහාරය, Data/Reload, ඉන්ධන, විකුණුම්) එක් ටැප් එකකින් සටහන් කිරීමේ Preset Chips සහ `450 Petrol` / `+2500 Order` කෙටි ආදාන තීරුව.
- **💵 Wallet Account Balances & 🎯 Safe Daily Spend:** අතේ ඇති මුදල් (Cash), බැංකු (Bank) සහ කාඩ්පත් (Card) ශේෂයන් වෙන වෙනම පෙන්වීම, ඉතිරි කිරීමේ ප්‍රතිශතය (Savings Rate %), සහ දිනකට ආරක්ෂිතව වියදම් කළ හැකි මුදල (Safe/Day) ගණනය කිරීම.
- **🔍 Instant Search, Filters & 📲 1-Tap WhatsApp Summary:** සටහන්/මුදල් ක්ෂණික සෙවුම, Account Filter, යතුරුපුවරුවේ `📋 Paste` සාරාංශ බොත්තම, සහ PDF / Excel (CSV) / WhatsApp Text වාර්තා.

### ⚡ 2GB / 3GB Low-RAM Turbo Engine & Universal Multi-Device Support
- **Custom Memory Management:** යතුරුපුවරුව වැසෙන විට ස්වයංක්‍රීය Bitmap/Sprite-sheet නිදහස් කිරීම (`clearCacheAndRecycleBitmaps`), `WeakReference` background tasks, සහ Viewport-aware 60fps UI layouts.
- **Emoji Pack Hub:** WhatsApp Emoji Style පෙර-ස්ථාපිතව (100% Offline) + Download කළ හැකි iOS, Facebook, Twitter/X සහ Google Noto Emoji Packs.
- **Phone, Tablet, Android TV & Media Box Support:** TV Remote D-Pad හැසිරවීම සහ Non-Fullscreen Landscape සහාය.

---

## [4.0.0] - 2026-11-05

### 🎨 Clean & Simple Age-Friendly UI + Experimental Lab Tab
- **Age-Friendly Settings UI:** ඕනෑම වයස් මට්ටමක කෙනෙකුට පහසුවෙන් කියවා භාවිතා කළ හැකි පරිදි Slate-Navy (`#0F172A`) පසුබිම සහ පැහැදිලි කාඩ්පත් සහිතව Settings අතුරුමුහුණත ප්‍රතිනිර්මාණය කරන ලදී.
- **Experimental Tab (අත්හදා බැලීම්):** සාමාන්‍ය පරිශීලකයින්ට එදිනෙදා අවශ්‍ය නොවන සියලුම සංකීර්ණ විකල්ප (RGB Border, Particle Effects, Hitbox AI, Per-Key Color Pickers, Gestures, Font Studio, AES-256 Cloak) වෙනම **Experimental** ටැබ් එකකට ගෙන ගොස්, එහි ප්‍රධාන ස්විචය ON කළ විට පමණක් දිස්වන ලෙස සකස් කරන ලදී.

### 🧠 Memory-Efficient Singlish Typo Auto-Correction
- Singlish ටයිප් කිරීමේදී සිදුවන අත්වැරදීම් (උදා: `kohomda` -> `කොහොමද`, `sththi` -> `ස්තූතියි`) නිවැරදිව හඳුනාගන්නා Local Dictionary-Based Auto-Correction පද්ධතිය සහ `ComponentCallbacks2` මතක පීඩන පාලනය (Memory-Pressure Trimming) එක් කරන ලදී.

### 🛡️ 100% Google Play Store Policy Compliance
- **Zero Self-Updater Violation:** Play Store ප්‍රතිපත්තිවලට 100%ක් අනුකූල වන පරිදි බාහිර APK බාගත කිරීමේ කේත ඉවත් කර නිල Google Play Store Update ප්‍රවාහය එක් කරන ලදී.
- **Least-Privilege Permissions & Data Safety:** අනවශ්‍ය `NotificationListenerService`, `POST_NOTIFICATIONS`, සහ `MODIFY_AUDIO_SETTINGS` ඉවත් කර, Setup Card තුළ පැහැදිලි Keystroke Privacy සහතිකය එක් කරන ලදී.

---

## [3.0.7] - 2026-10-28

### ⚡ 0ms Instant Top Bar Reveal on Space & Suggestion Selection
- වචනයක් ටයිප් කර **Space** යතුර තද කළ සැනින් හෝ Suggestion Bar එකෙන් වචනයක්/Emoji එකක් තේරූ සැනින්, කලින් පැවති තත්පර 1ක (`1000ms`) පමාව සම්පූර්ණයෙන්ම ඉවත් කර `0ms` ක්ෂණිකව Top Bar එක (Clipboard, Settings, Emoji, Font Studio, Translate ආදී Tools සහිත Toolbar එක) දිස්වන පරිදි සකසන ලදී.

### 🛑 Auto-Space After Period (.) Disabled by Default
- තිතක් (`.`) තැබූ විට ස්වයංක්‍රීයව `Space` එකක් එකතු වීම ඉවත් කර ඇත.

### 😊 Smart Emoji Suggestions (Sinhala, Singlish & English)
- සිංහලෙන්, Singlish වලින් හෝ English වලින් වචන ටයිප් කරන විටම අදාළ Emoji එක Suggestion Bar එකේ මුලටම ක්ෂණිකව යෝජනා වේ (O(1) Offline `EmojiDictionary`).

### 📦 APK Size Compression & 120fps Ultra-Smooth Engine
- `material-icons-extended` bloat ඉවත් කර, JSON සහ PNG assets සම්පීඩනය කර APK ප්‍රමාණය ~8MB+ කින් අඩු කරන ලදී.
- `KeyCap`, `KeyboardPanel`, සහ `SuggestionRail` තුළ 100% View/Drawable pooling සහ zero-allocation 120fps rendering එක් කරන ලදී.

### 🛡️ Rare Auto Force-Stop Fix, UI Polish & Creator Credit
- **Auto Force-Stop / ANR / OOM Fix:** `CrashLogger` ගොනු ලිවීම background thread එකකට යොමු කර, Main Looper burst rate-limiting, `SlashboardSyncWorker` duplicate RAM වැළැක්වීම, සහ `SlashboardApp` තුළ `EmojiStyleManager` ආරම්භක ආරක්ෂාව එක් කර කලාතුරකින් සිදුවූ Force-Stop ගැටලුව සම්පූර්ණයෙන්ම විසඳන ලදී.
- **UI Polish & Creator Credit:** Settings Dialogs වල පසුබිම් විනිවිද පෙනීම (surface bleed-through) සහ පේළි පරතරයන් නිවැරදි කර, **"Created by Dinush Lakmal | Slash Studios"** ලෙස Splash Screen, Header, About Card සහ Footer තුළ එක් කරන ලදී.

---

## [3.0.6] - 2026-10-16

### 🔑 GitHub Action "App Not Installed" (Signature Mismatch) Permanent Fix
- **Canonical Keystore Enforcement in CI/CD:**
  - GitHub Actions හිදී Sideload APK එක sign කිරීමේදී canonical keystore එක (`C3:8F:7D:10:11:E9:E5:90:78:19:20:1F:1F:DC:94:D4:A3:8A:F5:26`) වෙනුවට වෙනත් secret එකක් හෝ අහඹු keystore එකක් භාවිතා වීම වැළැක්වීමට CI pipeline එක ස්වයංක්‍රීයව canonical keystore එක enforce කර SHA1 සහතිකය තහවුරු කරයි.
  - `.gitignore` ගොනුවෙන් `!debug.keystore` un-ignore කර git repository එක තුළ සෘජුවම ආරක්ෂිතව තබා ඇත.

### 🛑 Auto-Space After Period (.) Disabled by Default (තිතකට පසු ස්වයංක්‍රීය Space එකක් එක්වීම අක්‍රීය කිරීම)
- තිතක් (`.`) හෝ විරාම ලකුණක් ටයිප් කළ සැනින් ස්වයංක්‍රීයව `Space` එකක් එකතු වීම ඉවත් කර ඇත. දැන් පරිශීලකයාට අවශ්‍ය නම් පමණක් Space යතුර භාවිතා කළ හැක (මෙය Settings -> Punctuation & Auto-Formatting තුළින්ද පාලනය කළ හැක).

### ⚡ 0ms Instant Top Bar Reveal on Space & Suggestion Selection (තත්පර 1ක පමාව ඉවත් කර එසැණින්ම Top Bar පෙන්වීම)
- වචනයක් ටයිප් කර **Space** යතුර තද කළ සැනින් හෝ Suggestion Bar එකෙන් වචනයක්/Emoji එකක් තේරූ සැනින්, කලින් පැවති තත්පර 1ක (`1000ms`) පමාව සම්පූර්ණයෙන්ම ඉවත් කර `0ms` ක්ෂණිකව Top Bar එක (Clipboard, Settings, Emoji, Font Studio, Translate ආදී Tools සහිත Toolbar එක) දිස්වන පරිදි සකසන ලදී.
- `onUpdateSelection` මඟින් Space එබීමෙන් පසු නැවත Suggestions පෙන්වීමද නවතා, ඊළඟ වචනයේ පළමු අකුර ටයිප් කරන තුරු Top Bar එක එසැණින්ම රැඳී පවතී.

### 🛡️ Zero False Positive OTP Engine
- සාමාන්‍ය අංක, දුරකථන අංක, මුරපද හෝ කේත OTP ලෙස වැරදියට හඳුනාගැනීම සම්පූර්ණයෙන්ම ඉවත් කර, සැබෑ SMS OTP පණිවිඩයක් පැමිණි විට පමණක් `📋 Paste OTP` Chip එක පෙන්වන පරිදි context-aware detection එන්ජිම යාවත්කාලීන කරන ලදී.

### 😊 Emoji Suggestions & Smart Emoji Mapping (ඉමෝජි යෝජනා පද්ධතිය)
- **Instant Sinhala, Singlish & English Emoji Suggestions:**
  - පරිශීලකයා සිංහලෙන්, Singlish වලින් හෝ English වලින් වචනයක් ටයිප් කරන විටම (උදා: තරහයි, taraha, angry, ගෙදර, gedara, home, ආදරෙයි, adare, love, හිනා, hina, smile, කෑම, kama, food, තේ, the, tea, කාර්, car, බයික්, bike), Suggestion Strip එකේ සාමාන්‍ය වචන සමඟම අදාළ Emoji එක කැපී පෙනෙන ලෙස (Highlight Pill සහ 21sp විශාල අකුරින්) මුලටම එකතු වී දිස්වේ.
  - O(1) Zero-Latency Offline `EmojiDictionary` මඟින් ඉතා අඩු RAM (2GB) සහිත දුරකථන වලදී පවා කිසිදු ප්‍රමාදයකින් (lag) තොරව ක්‍රියාත්මක වේ.

---

## [3.0.5] - 2026-10-13
- Added In-App Bug Reporter and silent crash recovery telemetry.

---

## [3.0.2] - 2026-10-07
- Added WhatsApp, iOS, Google, and Twitter/X emoji packs and pure black AMOLED default theme.

---

## [2.9.0] - 2026-09-29
- Added Double Space instant toolbar shortcuts and low-RAM optimizations.

---

## [2.8.0] - 2026-09-26
- Added horizontal swipe pager for settings and slow-motion water bubble effects.

---

## [2.6.0] - 2026-09-23
- Automated GitHub release pipelines and instant share links.

---

## [2.5.0] - 2026-09-20
- Added interactive IME space adjuster and modularized settings.

---

## [2.4.0] - 2026-09-20
- High-performance zero-lag keyboard launch and Rakaransaya improvements.

---

## [2.3.0] - 2026-09-18
- Introduced Font Studio, Live Unit Converter, and Custom Theme creator.

---

## [2.2.0] - 2026-09-10
- Initial native Sinhala keyboard release with on-device prediction and smart clipboard.
