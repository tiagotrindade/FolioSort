<div align="center">

# 📸 FolioSort

### Your photos are a mess. FolioSort fixes that in one click.

**FolioSort is a photo organizer app for macOS and Windows** that automatically sorts, renames, deduplicates, and organizes thousands of photos & videos into clean dated folders — using the real EXIF date, camera, and GPS location baked into every file. On-device AI lets you **search your whole library in plain language**, group every face into named people, read the text inside images, and clear screenshots, duplicates, and blurry shots. Native apps, one-time purchase, and **your files never leave your computer**.

🌐 **[foliosort.app](https://foliosort.app)**  ·  ⬇️ **[Download free](https://github.com/tiagotrindade/FolioSort/releases/latest)**  ·  🍎 macOS  ·  🪟 Windows

[![Latest release](https://img.shields.io/github/v/release/tiagotrindade/FolioSort?label=latest&color=8b5cf6)](https://github.com/tiagotrindade/FolioSort/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/tiagotrindade/FolioSort/total?color=8b5cf6)](https://github.com/tiagotrindade/FolioSort/releases)
![Platforms](https://img.shields.io/badge/platform-macOS%2014%2B%20%7C%20Windows%2010%2F11-blue)
![Privacy](https://img.shields.io/badge/privacy-100%25%20on--device-2ea44f)
[![License](https://img.shields.io/badge/license-proprietary-lightgrey)](LICENSE)

<br>

| 🍎 **macOS 14+** | 🪟 **Windows 10/11** |
|:---:|:---:|
| [**Download FolioSort.dmg**](https://github.com/tiagotrindade/FolioSort/releases/latest/download/FolioSort.dmg) | [**Get from Microsoft Store**](https://apps.microsoft.com/detail/9nlw1xwgk181?cid=github) |
| Apple Silicon & Intel · Signed & notarized | One-click install · Auto-updates |

**Jump to:** [Who it's for](#who-its-for) · [Screenshots](#see-it-in-action) · [How it compares](#how-foliosort-compares) · [Pricing](#free-vs-pro-vs-elite) · [FAQ](#faq) · [Install](#how-to-install)

<br>

![FolioSort photo organizer sorting thousands of photos into date folders on macOS](docs/screenshots/Organize.png?v=5)

</div>

---

## Sound familiar?

> *"I exported my Google Photos via Takeout and got 40 GB of files with broken dates and useless names."*

> *"I have 80,000 photos across ten cameras and phones, all dumped in one giant folder."*

> *"Every shoot lands in `~/Downloads` and I never sort them. I just buy a bigger drive."*

FolioSort reads the **EXIF metadata, GPS coordinates, and capture dates** that are already inside your files and turns chaos into a clean, browsable library — `2024 › 06 › 14 › IMG_4523.jpg` — in seconds, for thousands of files at once. **Copy mode by default**, with checksum verification, so your originals are never at risk.

---

## How it works

1. **Point** FolioSort at any folder, external drive, NAS share, or Google Takeout export — or just drag it in.
2. **Preview** the exact folder structure it will create, live, before a single file moves.
3. **Start** — thousands of photos sorted into dated folders in seconds, every transfer checksum-verified, with one-click **Undo**.

No account. No upload. No scripts. **[Download free](https://github.com/tiagotrindade/FolioSort/releases/latest)** and organize your first 100 files per batch, forever.

---

## Who it's for

### 🗂️ Google Photos refugees
Leaving Google Photos? The Takeout export is notoriously broken — dates live in sidecar `.json` files, names are scrambled, and RAWs are disguised as JPEGs. **FolioSort's Google Photos mode reads those sidecars, writes the real date + GPS + people tags back into each file, and sorts everything** into the structure you want. It even detects Canon CR2/CR3 files that Google silently renamed to `.jpg`.

### 📷 Photographers & videographers
Sort by **date, camera body, lens, or GPS city**. Built-in presets for date-based archives, multi-camera workflows, and video production — or build your own folder template with tokens like `{YYYY}/{MM}/{Camera}/{City}`. Handles **80+ formats including RAW** (CR3, NEF, ARW, DNG…) and cinema video (BRAW, R3D, ARRI).

### 🎯 Event shooters
Sorting a competition, wedding, or multi-day trip? **Define time ranges** and FolioSort drops every photo into the right event/sub-event folder automatically, based on when it was actually taken.

### 🧹 Everyone with a messy Downloads folder
One **Wizard**, three clicks, done. No metadata expertise required.

---

## See it in action

### 🪄 Start with the Wizard — pick what you want, follow the steps
![FolioSort Wizard guiding photo organization step by step](docs/screenshots/Wizard.png?v=5)

### 🗂️ Organize — sort by date, camera, or location with live preview
![Organize photos into folders by date, camera, or GPS location with live folder preview](docs/screenshots/Organize.png?v=5)

### ☁️ Google Photos Takeout — fix the export Google broke
![Google Photos Takeout import fixing broken dates from JSON sidecar files](docs/screenshots/GooglePhotos.png?v=5)

### 🔤 Rename — batch-rename thousands of files with date & camera patterns
![Batch rename thousands of photos with date and camera naming patterns](docs/screenshots/Rename.png?v=5)

### 📅 Events — sort by occasion using custom time ranges
![Sort photos into event folders using custom time ranges](docs/screenshots/Events.png?v=5)

<div align="center">

**Like what you see?** ⬇️ **[Download FolioSort free](https://github.com/tiagotrindade/FolioSort/releases/latest)** — macOS & Windows, no account, first 100 files per batch free forever.

</div>

---

## 🚪 Leave the cloud — Exit Cloud Kit

Getting your photos *out* of a cloud service is half the battle; the export is always a mess. FolioSort's **Exit Cloud Kit** is a guided wizard that ingests the export from wherever your photos are trapped, recovers the real capture dates, and hands you a clean local library — with an **Exit Report** so you can see exactly what came across.

- **Import connectors** for **Google Takeout**, **WhatsApp** exports (with filename date recovery), **Amazon Photos**, **OneDrive**, and **iCloud** exports (CSV/JSON date recovery)
- Auto-detects the source and badges it in the picker; `{Album}` / `{Chat}` template tokens; NAS-safe folder names
- One-click **Synology** and **Immich** destination presets for landing straight on your NAS or self-hosted server

![Exit Cloud Kit importing Google Takeout, WhatsApp, Amazon Photos, OneDrive and iCloud exports into a clean library](docs/screenshots/ExitCloudKit.png?v=5)

---

## 📍 Place names written into your photos

FolioSort has always turned GPS coordinates into a place and used that place to **name** things — folders, filenames, the file list. Now it can also write the place **into the file**, so it survives leaving FolioSort.

- Writes both of the places a cataloguing app actually reads: the legacy **IPTC** block **and** the Photoshop **XMP** namespace — so **Lightroom, Bridge, Photo Mechanic and Apple Photos** see the same city you just resolved.
- JPEG, HEIC, TIFF and DNG are written in place. Proprietary RAW files (CR2, CR3, NEF, ARW…) get a **sidecar**, and the RAW itself is never touched.
- **Fully reversible.** FolioSort remembers what each tag said before it wrote, and restores exactly that — a tag that did not exist before is *removed* on revert, not blanked, because an empty city and no city are different things.
- Your capture dates never move. A place name is a fact about the photo, not an edit to it.
- Before writing, FolioSort **names the places it found** — "Lisboa, Porto, Sintra and 1 more" — so you can judge them first.

Resolving place names is **free**, up to 100 photos per scan; Pro removes the cap. If you're leaving Lightroom, this is the part that survives the move.

---

## Clean up your photo library

Cleanup tools that form a single narrative: **Merge** collapses every scattered copy of your library into one · **Duplicates** removes the copies that merging exposes · **Blurry** clears the shots you'd never keep · **Screenshots** pulls the receipts and memes out of your photos. Every removal goes to the system **Recycle Bin / Trash and is always undoable**, you approve every decision before anything moves, and everything runs **100% on your computer**.

### 🔀 Merge Sources — combine every copy into one clean library
A guided 5-step wizard that merges any number of folders, drives, or Google Takeout exports into **one clean, de-duplicated library**. It detects exact copies, visually similar near-duplicates, and blurry shots in a single scan, and keeps the **best version of each photo** using a deterministic rule (RAW > resolution > size > original-vs-edited > capture date). Non-destructive by default — redundant files are skipped in place, never deleted — with optional one-click cleanup of redundant exact copies to the Trash.

![Merge Sources wizard combining multiple photo folders and drives into one deduplicated library](docs/screenshots/Merge.png?v=5)

### 🧬 Duplicates — find exact *and* visually similar copies
Finds exact **and visually similar** duplicate photos via perceptual fingerprinting — catching resized, re-compressed, cropped, and slightly-edited copies that byte/hash tools miss. Groups every version of a shot (labelled by *why* they match), suggests the keeper, shows a live "space to recover" counter, and a side-by-side compare view with EXIF and **zoom up to 8×** — because choosing between two near-identical photos shouldn't be done blind. Quick and Comprehensive scan modes.

**Nothing arrives pre-selected for the Trash unless the files are genuinely identical.** Byte-for-byte copies — verified by reading both files end to end, not by a fingerprint — arrive ticked. Anything matched *visually* arrives **unticked**, labelled **"possible match"** rather than a confident-looking percentage, and grouped under **Similar**. You choose what goes, and marking is never deleting: moving to the Trash is a separate press, and undoable.

When a large library produces thousands of Similar groups, **"Keep suggested, mark all the rest"** clears them in a single action — scoped to the tier you have selected in the sidebar (never "All"), and it tells you how many groups and how many files it is about to mark before it marks anything.

![Duplicate photo finder detecting exact and visually similar copies with space-to-recover counter](docs/screenshots/Duplicates.png?v=5)

### 👁️ Blurry — clear out-of-focus shots
Scores every photo for sharpness and sorts **blurriest-first**. A live sensitivity slider sets the cut-off and re-filters instantly with no re-scan; every photo shows its score. Resolution-independent and **ML-free by design** — a transparent, on-device sharpness measure.

![Blurry photo detection scoring every image for sharpness with live sensitivity slider](docs/screenshots/Blurry.png?v=5)

### 📱 Screenshots — get your photos back
Automatically detects the screenshots polluting your photo library — receipts, memes, UI captures — and moves them out in one click, so your library is photos again. Content-based detection, entirely on your machine.

![Screenshot detector finding receipts, memes and UI captures mixed into a photo library](docs/screenshots/FindScreenshots.png?v=5)

> On macOS, Duplicates uses Apple's on-device Vision; on Windows it uses on-device perceptual hashing — both fully on-device. Blurry is ML-free by design.

---

## 🤖 AI Search (Elite) — find any photo, without the cloud

The kind of search you gave up when you left Google Photos — except **nothing ever leaves your computer**. No account, no upload, no cloud processing. On-device models (MobileCLIP2 for images, plus face recognition and OCR) index your library locally.

### 💬 Search in plain language
Type **"the dog on the beach"**, "my passport", or "birthday cake with candles" and FolioSort surfaces the matching photos — semantic search over your whole library, running entirely on-device. On a **100,000-photo** library a query comes back in **62 ms**. A mode picker says whether you mean **what a photo shows** or **what it says**, and a plain filename or number still finds its photo — `4782` finds `_DIV4782.NEF`, whatever your camera decided to call it.

![On-device AI semantic photo search finding pictures from a plain-language description](docs/screenshots/SemanticSearch.png?v=5)

### 🧑 People — every face in your library, grouped and named
FolioSort scans a folder and **groups the faces it finds into people**, automatically — no reference photo needed. Name someone once and the name sticks, even after you add more photos and re-scan. When two piles turn out to be the same person, FolioSort asks *"same person?"* instead of making you tune a threshold, and every correction you make is remembered.

![People pane grouping every face in a photo library into people, with a same-person review queue](docs/screenshots/People.png?v=5)

Then take the names with you: **write people into XMP sidecars** so **Lightroom and Capture One** see the same names you just assigned — your face tagging is no longer locked inside one app. Your photos are never opened or changed: the names go into a separate file beside each one. After every Organize run, a **People strip** shows who FolioSort just found.

![Write People to XMP Sidecars dialog showing named people and photo counts before writing](docs/screenshots/PeopleXMP.png?v=5)

### 👤 Find by Photo
Already know who you're looking for? Pick one photo of them and FolioSort finds **every photo of that person** across your library. Review the matches, then **move them all to a folder** in one click — perfect for pulling every shot of your kid out of 40,000 files.

![Find a Person on-device face recognition locating every photo of one person](docs/screenshots/FindPerson.png?v=5)

### 🔎 Text-in-photo search (OCR) & Auto-Events
Find photos by the **text inside them** — signs, receipts, whiteboards, screenshots — indexed on-device. FolioSort also proposes **Auto-Events** from natural time-and-place clusters and **infers dates** for undated files, so nothing is left stranded.

> Runs entirely on your machine — no cloud, no account, photos never uploaded. Free includes an **AI taster** — index 500 photos for search, and move 20 photos from People or Find by Photo. Elite unlocks it across your entire library.

---

## 🔁 Automate (Elite) — organizing on autopilot

### ⚙️ Workflows
Chain **Organize → Duplicates → Rename → Screenshots → Blurry** into a single run and let FolioSort execute the whole cleanup end to end. A review-pause between steps keeps you in control, and every step has its own undo (per-step LIFO), so any stage can be rolled back independently.

![Workflows chaining organize, deduplicate, rename and cleanup steps into one automated run](docs/screenshots/Workflow.png?v=5)

### 👀 Watch Folders
Point FolioSort at your `~/Downloads`, an SD-card mount, or an import folder and it **organizes new files as they land** — the sorting you always meant to do, happening on its own.

### 📂 Smart Folders
Saved searches that **fill themselves**. Define a query once — a person, a place, a text match, a date range — and get a live folder that updates as your library grows.

![Smart Folders — self-updating saved photo searches by person, place, text or date](docs/screenshots/SmartFolders.png?v=5)

### 🏆 Best Shots — AI Culling
Shot a burst? FolioSort scores every frame and **keeps the best one of each group**, so you archive the keeper and clear the rest — automatic culling, entirely on-device. Then **Review** the calls yourself: a whole-folder grid that dims what you've already decided, ⌘/⇧ selection that Copy and Move act on, camera settings and a histogram beside each frame, star ratings written into the files (and undoable), and zoom that shows the actual photograph rather than the small JPEG preview buried inside the RAW.

![Best Shots AI culling keeping the sharpest frame of every burst automatically](docs/screenshots/BestShots.png?v=5)

---

## Why FolioSort

- **🔒 Private by design** — your photos never leave your computer. No cloud, no account, no upload. All AI search, face recognition, and OCR run on-device. Optional reverse geocoding sends only GPS coordinates (never your files); anonymous usage analytics are opt-out.
- **⚡ Built for bulk** — tested on libraries of 1,000s of files; fast XXHash64 integrity checks by default. A move **within one disk** never rewrites the file, a duplicate scan holds a flat ~6 MB of memory however large the drive, and the destination is tested **once before a run starts** instead of failing on every file for hours.
- **🛟 Safe by design** — Copy mode is the default, every transfer is checksum-verified, and **one-click Undo** reverses any batch — including the star ratings and place names FolioSort wrote into your files.
- **☁️ It won't drag your cloud library onto your disk** — photos kept in **OneDrive, iCloud Drive or Dropbox** are often just placeholders. FolioSort recognises them *without opening them*, leaves them alone, and says how many it skipped, instead of quietly pulling your whole library down your connection.
- **🖥️ Truly native on both platforms** — Swift/SwiftUI on macOS, .NET WPF on Windows. No Electron, small footprint.
- **🎯 Reads metadata properly** — EXIF date chain (DateTimeOriginal → Digitized → TIFF) with subsecond precision, video creation dates, and GPS reverse-geocoding to city/country.
- **💶 One-time purchase** — no subscription. Free tier is genuinely useful; **Pro is €19.99** and **Elite is €49.99**, both forever.

---

## How FolioSort compares

| | **FolioSort** | Library apps¹ | Cloud photo services² | DIY scripts³ |
|---|:---:|:---:|:---:|:---:|
| Organizes the **actual files & folders on disk** | ✓ | — | — | ✓ |
| Fixes **Google Takeout** broken dates | ✓ | — | — | partial |
| Duplicate + blurry + screenshot **cleanup** | ✓ | partial | partial | — |
| **AI search** (plain language, faces, OCR) | ✓ on-device | device-dependent | ✓ in the cloud | — |
| Photos **stay on your computer** | ✓ | ✓ | — | ✓ |
| **macOS and Windows**, native | ✓ | varies | web | varies |
| No technical skills needed | ✓ | ✓ | ✓ | — |
| Pricing | **one-time** | free–subscription | subscription | free |

¹ Apple Photos, Lightroom — great at editing and browsing a *library database*, but they don't produce a clean folder structure on disk. ² Google Photos, Amazon Photos — convenient, but your photos live on their servers under a subscription. ³ ExifTool one-liners and classic date-sorter utilities — powerful but manual, no preview, no undo, no cleanup or AI.

FolioSort is the tool for the job *underneath* all of those: turning raw files on disks, SD cards, NAS shares, and cloud exports into a clean, future-proof folder archive that outlives any app.

---

## Free vs Pro vs Elite

FolioSort is **free to use** with a generous limit. **Pro** unlocks the unlimited organizer and every cleanup tool; **Elite** adds everything that runs a neural network — on-device AI search, face recognition, OCR, and automation. Both are a **one-time purchase, no subscription**.

| | Free | Pro · €19.99 | Elite · €49.99 |
|---|:---:|:---:|:---:|
| **Files per operation** | 100 | **Unlimited** | **Unlimited** |
| Organize by date (Mover) | ✓ | ✓ | ✓ |
| Batch rename (patterns) | ✓ | ✓ | ✓ |
| Google Takeout import | ✓ *(unlimited)* | ✓ | ✓ |
| Scan, score & review — duplicates, blurry, screenshots | ✓ *(unlimited)* | ✓ | ✓ |
| One-click Undo | ✓ | ✓ | ✓ |
| Exact + visual duplicate cleanup | First 20 | ✓ | ✓ |
| Blurry photo cleanup | First 20 | ✓ | ✓ |
| Screenshot cleanup | First 20 | ✓ | ✓ |
| Merge Sources (unlimited) | — | ✓ | ✓ |
| **Custom folder templates & profiles** | — | ✓ | ✓ |
| **RAW photo & video formats** | — | ✓ | ✓ |
| **Regex rename** | — | ✓ | ✓ |
| **Place names from GPS** (reverse geocoding) | ✓ *(100 photos/scan)* | ✓ | ✓ |
| **Write place names into your photos** (IPTC + XMP, reversible) | ✓ *(100 photos/scan)* | ✓ | ✓ |
| **Location tokens in folder names** (`{City}`, `{Country}`, `{State}`) | — | ✓ | ✓ |
| **Event Organizer** (time-range sorting) | — | ✓ | ✓ |
| **Cloud / NAS & Exit Kit import** (SMB/AFP/iCloud, WhatsApp, Amazon, OneDrive) | ✓ *(100 files/run)* | ✓ | ✓ |
| **AI semantic search** — *"the dog on the beach"* | Taster · indexes 500 photos | — | ✓ |
| **People** — automatic face grouping & naming | Taster · move 20 photos | — | ✓ |
| **Find by Photo** (on-device face search) | Taster · move 20 photos | — | ✓ |
| **People → XMP sidecars** (Lightroom / Capture One) | — | — | ✓ |
| **Text-in-photo search (OCR) & Auto-Events** | — | — | ✓ |
| **Workflows + Watch Folders** | — | — | ✓ |
| **AI Culling — Best Shots** | — | — | ✓ |
| **Smart Folders** (self-filling saved searches) | — | — | ✓ |
| Devices per license | — | 1 (Mac *or* Windows) | 3 (Mac + Windows) |
| Priority support | — | — | ✓ |

### 💜 Buy a license — one-time, no subscription

- **[→ Buy Pro — €19.99](https://www.foliosort.app/upgrade?utm_source=github&utm_medium=readme&utm_campaign=buy_pro)** — the unlimited organizer + every cleanup tool
- **[→ Buy Elite — €49.99](https://www.foliosort.app/upgrade?utm_source=github&utm_medium=readme&utm_campaign=buy_elite)** — everything in Pro **plus** on-device AI search, People, OCR & automation

1. Complete checkout → receive your **license key** by email
2. Open FolioSort → **Settings → Upgrade** → paste key → **Activate**
3. Unlocked forever on **both macOS and Windows** — **Pro** activates on 1 computer, **Elite** on up to 3 devices you can mix across Mac + Windows

> Already own **Pro** and want the AI features? Open **Settings → Upgrade** in the app — Elite is offered right there, no need to hunt for it.

---

## Features at a glance

<details>
<summary><b>🗂️ Media Organization (Mover)</b></summary>

- Custom folder templates with tokens: `{YYYY}/{MM}/{DD}`, `{Camera}`, `{City}`, `{Month}`, `{Album}`, `{Chat}`, and more
- 4 built-in presets (date, camera, video production, flat archive) + custom profiles
- Simple pattern dropdown or Advanced template builder with token palette
- EXIF-based date sorting for photos; creation-date for MOV/MP4/MKV and more
- Copy or Move · optional date-prefix rename · dedicated Videos subfolder
- Include non-media files (documents, archives) optionally
- Live preview tree before you commit · thumbnail previews · drag & drop folders
</details>

<details>
<summary><b>☁️ Google Photos Takeout & Exit Kit</b></summary>

- Point at any exported Takeout folder — structure-agnostic
- **Writes original capture date, GPS, and people tags back into each file** via bundled ExifTool
- Reads the real camera model from EXIF, even inside Takeout archives
- Detects CR2/CR3 RAWs that Google renamed to `.jpg` and handles them correctly
- **Exit Kit** import connectors: WhatsApp (filename date recovery), Amazon Photos, OneDrive, iCloud export (CSV/JSON date recovery)
- Source auto-detection badge · `{Album}` / `{Chat}` tokens · NAS-safe folder names · Synology & Immich destination presets
- Flat mode (free) or date-folder organisation with 7 patterns · Copy or Move · live ETA · **Exit Report**
</details>

<details>
<summary><b>🔤 Mass Rename</b></summary>

- 7 naming patterns (date prefix, date-time, sequential, camera model…)
- Regex find/replace with capture groups (`$1`, `$2`) and case-insensitive option
- Live before/after preview with match highlighting
- Common presets: remove prefix, replace spaces, extract date digits, strip trailing numbers
- Rename in place or copy to a new folder
</details>

<details>
<summary><b>📅 Event Organizer (Pro)</b></summary>

- Define events and sub-events with start/end times; files sorted by capture timestamp
- Two-level hierarchy (e.g. competition → heats)
- **Auto-grouping interval** from 1 minute to 3 days, and an option to include files with **no capture date** (screenshots, exports, downloads)
- Real-time overlap validation · between-slot fallback to parent event
- Unmatched files → "Unmatched" folder or kept in source
- UTC-aligned date pickers · live matched/unmatched counts · full undo
</details>

<details>
<summary><b>🔀 Merge Sources</b></summary>

- Guided 5-step wizard: combine unlimited folders, drives, and Google Takeout exports into one library
- Detects exact copies, visually similar near-duplicates, and blurry shots in a single scan
- Keeps the best version of each photo (deterministic: RAW > resolution > size > original-vs-edited > capture date)
- Non-destructive by default — redundant files skipped in place, never deleted
- Every move is hash-verified · full keep/skip report
- Optional opt-in cleanup of redundant exact copies to the Recycle Bin / Trash (undoable)
</details>

<details>
<summary><b>🧬 Duplicates, 👁️ Blurry & 📱 Screenshots</b></summary>

- **Duplicates** — exact **and** visually similar detection via perceptual fingerprinting; groups every version, suggests the keeper, live "space to recover" counter, side-by-side compare with EXIF and 8× zoom, Quick vs Comprehensive modes
- Only byte-for-byte identical copies are ever pre-selected; visual matches arrive unticked as **"possible match"** under **Similar** — and **"Keep suggested, mark all the rest"** clears thousands of Similar groups in one tier-scoped, counted action
- Cancel works during the confirm step, and scrolling a huge result no longer stalls the window
- **Blurry** — sharpness score per photo, sorted blurriest-first, live sensitivity slider with no re-scan, ML-free by design
- **Screenshots** — content-based detection of receipts, memes, and UI captures mixed into your photos, moved out in one click
- macOS uses Apple's on-device Vision · Windows uses on-device perceptual hashing
- Removals go to the Recycle Bin / Trash with one-tap undo
</details>

<details>
<summary><b>🤖 AI Search (Elite)</b></summary>

- **Semantic search** — describe a photo in plain language (*"the dog on the beach"*); on-device MobileCLIP2 + CLIP tokenizer, recall-gate validated; **62 ms per query on a 100,000-photo library**
- A mode picker for **what a photo shows** vs **what it says**, a match-strength slider that filters every kind of hit, filename/number matching (`4782` → `_DIV4782.NEF`), and ⇧-click range selection
- **Clear index** in the Index Status panel; indexing writes **one** file (~1.1 KB per photo) and never puts anything beside your photos
- **People** — automatic face grouping into people, with names that survive a re-scan; a *"same person?"* merge queue instead of a threshold slider; per-person move/export; People strip after every Organize run
- **People → XMP sidecars** — write your named people into XMP so Lightroom and Capture One read the same names; choose named people only, or everyone
- **Find by Photo** — pick a reference photo, get every photo of that person; on-device face detection + recognition (Vision + Core ML on macOS, ONNX YuNet + SFace on Windows)
- **OCR text search** — find photos by the text they contain, indexed on-device
- **Auto-Events & date inference** — suggested events from time/place clusters, dates recovered for undated files
- One-click **Move to Folder** on any result set
- 100% on-device — no cloud, no account, photos never uploaded
- Free **AI taster** (search 500 photos, find a person in 20); unlimited with Elite
</details>

<details>
<summary><b>🔁 Automation — Workflows, Watch Folders, Smart Folders & Best Shots (Elite)</b></summary>

- **Workflows** — chain Organize → Duplicates → Rename → Screenshots → Blurry in one run, with a review-pause between steps and per-step LIFO undo
- **Watch Folders** — auto-organize new files as they land in a watched folder
- **Smart Folders** — self-filling saved searches (person, place, text, date range) that update as your library grows
- **Best Shots (AI Culling)** — scores every frame of a burst and keeps the best one, on-device; **Review** adds a whole-folder grid, ⌘/⇧ selection that Copy and Move act on, info + histogram, undoable star ratings, and zoom on the real RAW rather than its embedded preview
</details>

<details>
<summary><b>📍 GPS Reverse Geocoding & Date Handling</b></summary>

- Reads GPS from EXIF; resolves to city/country/state via reverse geocoding (Apple CLGeocoder on macOS) — **free up to 100 photos per scan**
- Location tokens: `{City}`, `{Country}`, `{State}`, `{Locality}`
- **Writes the place into the file** — legacy IPTC block + Photoshop XMP namespace (what Lightroom, Bridge, Photo Mechanic and Apple Photos read); JPEG/HEIC/TIFF/DNG in place, sidecar for proprietary RAW
- Reversible per tag — the previous value is restored exactly, and a tag that did not exist before is removed rather than blanked; capture dates never move
- Smart disk + memory cache (~11 m precision), rate-limited, Null-Island `(0,0)` rejected; roughly ¾ of lookups reuse an answer from within ~110 m
- EXIF date chain: DateTimeOriginal → DateTimeDigitized → TIFFDateTime (supports scanned photos)
- Subsecond precision · file creation/modification fallback · UTC-consistent sorting
</details>

<details>
<summary><b>🛟 Integrity, Duplicates, Cloud/NAS & Undo</b></summary>

- Post-transfer checksum verification (XXHash64 free · SHA-256 Pro)
- Duplicate handling: Skip (free) · Ask Each Time / Automatic (Pro)
- Cloud/NAS (free): SMB/AFP shares, retry with backoff, disconnect handling, live MB/s — where your photos live was never a tier question
- **Cloud placeholders** (OneDrive · iCloud Drive · Dropbox) are recognised *without being opened*, skipped, and reported with a count and what to do about them — so a scan never silently downloads your library. Organize is the deliberate exception: it downloads what it needs, with a progress bar, because it cannot sort a photo by a date it hasn't read
- **Write pre-flight**: the destination is tested once before a run starts, across all nine modules that move, copy or delete — a refused folder is reported in seconds, and a *locked* file is told apart from a permissions one
- Undo: reverse the last batch in one click · persistent history up to 50 batches (Pro) · covers star ratings and place names written into files
- Searchable, exportable Activity log
- Automatic updates via Sparkle (macOS), and the Microsoft Store or the built-in updater (Windows)
</details>

---

## How to install

### macOS
1. Download [`FolioSort.dmg`](https://github.com/tiagotrindade/FolioSort/releases/latest/download/FolioSort.dmg).
2. Open the DMG and drag **FolioSort** to **Applications**.
3. Launch it — FolioSort is **signed and notarized by Apple**, so it opens with no Gatekeeper warning.

### Windows
1. Open the **[FolioSort listing on the Microsoft Store](https://apps.microsoft.com/detail/9nlw1xwgk181?cid=github)**.
2. Click **Get** — the Store installs and launches FolioSort automatically, and keeps it up to date.

> Distributed through the Microsoft Store: signed, sandboxed, and auto-updated — no SmartScreen warnings, no manual unzip.

Prefer a portable version? Grab `FolioSort-x.y.z-windows.zip` from the [latest release](https://github.com/tiagotrindade/FolioSort/releases/latest), right-click → Properties → **Unblock**, extract, and run `FolioSort.exe`. The zip is self-contained — no separate .NET install — and bundles the on-device AI models, so it's larger (~300 MB).

**Uninstall (Windows):** Start → right-click **FolioSort** → **Uninstall**.

---

## Supported formats

**Photos:** JPG, JPEG, JFIF, PNG, HEIC, HEIF, TIFF, TIF, BMP, GIF, WebP, AVIF, JXL, JP2, J2K, JPF, JPX, JXR, WDP, HDP

**RAW Photos (Pro):** CR2, CR3, CRW (Canon) · NEF, NRW (Nikon) · ARW, SR2, SRF (Sony) · DNG (Adobe) · ORF (Olympus) · RAF (Fujifilm) · RW2 (Panasonic) · PEF, PTX (Pentax) · SRW (Samsung) · X3F (Sigma) · RWL, RAW (Leica) · MRW (Minolta) · 3FR, FFF (Hasselblad) · IIQ, CAP (Phase One) · KDC, DCR, K25 (Kodak) · ERF (Epson) · GPR (GoPro) · MEF (Mamiya) · BAY (Casio) · STI (Sinar) · MOS (Leaf)

**Videos:** MOV, MP4, AVI, MKV, M4V, 3GP, 3G2, WMV, ASF, FLV, F4V, WebM, MTS, M2TS, TS, M2T, MPG, MPEG, MP2, VOB, DV, OGV, OGG, RM, RMVB, DivX, XviD

**RAW Video (Pro):** BRAW (Blackmagic) · R3D (RED) · ARI, ARX (ARRI) · CRM (Canon Cinema) · MXF (Sony) · CINE (Phantom) · INSV (Insta360) · LRV (GoPro) · OP1, OP2 (Panasonic P2) · DNxHD (Avid) · FCPVID (Final Cut)

**Other (Pro):** any file type via the "Other Files" toggle

---

## Requirements

- **macOS** — macOS 14 (Sonoma) or later · Apple Silicon (M1–M4) or Intel
- **Windows** — Windows 10 or 11 (x64) · .NET runtime bundled, no separate install

---

## About this repository

This repository hosts FolioSort's **releases, documentation and issue tracker**.
FolioSort is a proprietary application and its source code is not published —
see [LICENSE](LICENSE).

Every macOS and Windows build is published here under
[Releases](https://github.com/tiagotrindade/FolioSort/releases), and that is
also where the in-app updater fetches them from. Bug reports and feature
requests are welcome in [Issues](https://github.com/tiagotrindade/FolioSort/issues).

---

## FAQ

### How do I organize thousands of photos into folders by date?
Download FolioSort, point it at the folder (or drive, or NAS share) holding your photos, pick a structure like `Year/Month/Day`, and press Start. It reads the **real capture date from EXIF metadata** — not the file's copied-on date — previews the result before anything moves, and sorts thousands of files in seconds with checksum verification and one-click Undo.

### How do I fix the broken dates in my Google Photos Takeout export?
Point FolioSort's Google Photos mode at the extracted Takeout folder. It reads the sidecar `.json` files Google ships alongside each photo, writes the real capture date, GPS, and people tags back into the files themselves, and sorts everything into dated folders. No scripts, no ExifTool command lines. Takeout import is free with no file limit.

### Can I search my photos like I did in Google Photos — without the cloud?
Yes — Elite adds on-device **AI search**: type *"the dog on the beach"* and get the photo, browse your library **by person** (FolioSort groups the faces itself and remembers the names you give them), or search the text inside your images (OCR). It all runs on your machine — no account, no upload. The free tier includes a taster so you can try it before buying.

### How do I tag people in my photos without uploading them anywhere?
Use **People** (Elite). FolioSort detects and groups the faces in your folder into people on your own machine, you name them once, and it asks *"same person?"* when two groups look like a match. Then export those names to **XMP sidecars**, so **Lightroom** and **Capture One** read the same people — your face tagging isn't trapped in one app, and no photo or face ever leaves your computer.

### How do I merge photo libraries from several drives or backups into one?
Use **Merge Sources**: a guided wizard that combines any number of folders, drives, and Takeout exports into one clean, de-duplicated library. It detects exact and visually similar duplicates in one scan and keeps the best version of each photo (RAW > resolution > size), without deleting anything by default.

### Is it safe to run on the only copy of my photos?
FolioSort is built around not losing files: **Copy mode is the default** (originals untouched), every transfer is checksum-verified before the source is ever removed, deletions go to the system Trash/Recycle Bin, and every batch has one-click Undo. Before a run starts it also tests that the destination can actually be written to, so a folder you don't have permission for is reported in seconds rather than as thousands of identical errors. That said — you should always have a backup of irreplaceable photos, with or without FolioSort.

### Does it work offline? Where do my photos go?
Nowhere. All scanning, AI search, face recognition, OCR, duplicate detection, and organizing runs on your computer. No account, no upload, no cloud processing. The only optional network feature is reverse geocoding, which sends GPS coordinates (never images) to resolve city names.

### Will it download my OneDrive, iCloud or Dropbox photos onto my disk?
No. Those services often leave a placeholder on disk and keep the photo itself in the cloud until something opens it — and opening a photo is the first thing any organizer does. FolioSort recognises placeholders **without opening them**, skips them, and tells you how many it skipped and how to include them next time (right-click in Finder → *Download Now*). The one deliberate exception is Organize, which does download what it needs, with a progress bar, because it cannot sort a photo by a date it hasn't read.

### Can I get the place names into Lightroom?
Yes. FolioSort resolves your GPS coordinates into a city and can **write it into the file** — both the legacy IPTC block and the Photoshop XMP namespace, which is what **Lightroom, Bridge, Photo Mechanic and Apple Photos** read. JPEG, HEIC, TIFF and DNG are written in place; proprietary RAW gets a sidecar and is never touched. It's reversible tag by tag, and your capture dates never move. Resolving places is free up to 100 photos per scan.

### Is FolioSort free? What's the catch?
No catch, no trial clock, no watermarks: the free tier processes **100 files per batch**, forever. Scanning, scoring and reviewing are always free and unlimited — you can see every duplicate, blurry shot and screenshot in your library before paying anything — and free includes your **first 20 cleanups** plus an AI taster. **Pro** (€19.99 one-time) removes the limit and unlocks power features like RAW formats, custom templates, and regex rename; **Elite** (€49.99 one-time) adds on-device AI search, face search, OCR, and automation. No subscription, ever.

### Does it handle RAW photos and video?
Yes — 80+ formats including Canon CR2/CR3, Nikon NEF, Sony ARW, DNG, plus cinema video (BRAW, R3D, ARRI). See the [full list](#supported-formats). RAW formats are a Pro feature.

### Why not just use Apple Photos or Lightroom?
Those manage a *library database*. FolioSort organizes the **actual files and folders on disk** — ideal if you archive to a NAS or external drive, want a future-proof folder structure that outlives any app, or need to clean up a mess *before* importing it anywhere. See [How FolioSort compares](#how-foliosort-compares).

---

## Changelog

See the [Releases page](https://github.com/tiagotrindade/FolioSort/releases) for the full version history.

**Latest — v4.9.7 · both macOS and Windows.** AI Search answers **12.7× faster** — a query on a 100,000-photo library went from 789 ms to **62 ms** · a search **mode picker** that says whether you mean *what a photo shows* or *what it says*, so the match-strength slider can filter filename and OCR hits too · **zoom to 8×** in the photo preview and the duplicate comparison, with drag to pan and double-click to fit · **Events**: pick the grouping interval (1 minute → 3 days), include files with no capture date, and every event now matches its own last photo · **Duplicates**: a new bulk **"Keep suggested, mark all the rest"** for the thousands of *Similar* groups a large library produces — scoped to one tier, counted before it marks anything · in **Copy** mode a free user could never reach file 101 — fixed · **cloud and NAS folders are free**: the 100-file limit is the whole rule.

**v4.9.6 — First-launch crash:** installing FolioSort on a brand-new Mac on 4.9.3–4.9.5 quit the app the moment it launched — the welcome screen looked for its logo in the wrong place inside the installed bundle. Fixed, with a test that fails the build if the mistake is ever reintroduced. Upgrades were never affected.

**v4.9.5 — Cloud files, and duplicates you can trust:** photos that live in **OneDrive, iCloud Drive or Dropbox** are no longer downloaded behind your back — FolioSort recognises placeholder files without opening them, and says how many it skipped and what to do about it · in **Quick** duplicate mode **only byte-for-byte identical copies arrive pre-selected**; anything matched visually arrives unticked, labelled **"possible match"** instead of a percentage, and grouped under *Similar* · scrolling a huge duplicates result no longer locks up · AI Search matches the digits inside a filename whatever the camera named it (`1643` finds `DSC01643`), and says when it couldn't read a folder instead of reporting a green "0 new photos" · the Mover reports throughput on every run, not just on network volumes.

**v4.9.4 — A 2 TB duplicate scan on a 16 GB Mac:** the last step of a duplicate scan held on to every byte it read — a drive with 63 GB of duplicates made the app ask for 63 GB. Now **flat at 5.8 MB** however much it reads, so the size of the drive no longer decides whether the scan can run · the same mistake in file hashing, fixed in the same release · **"Run in Background"** no longer blocks Organize just as hard as waiting did, and only asks for a place lookup when your folder pattern actually contains a place token · when a Move empties the folder you picked, the results panel offers it to you instead of leaving it there silently · AI Search can find a file by its name.

**v4.9.3 — A first screen that shows the work:** the welcome screen now *shows* camera filenames settling into `Photos › 2019 › 07 July › Lisbon`, with both halves left on screen to compare · **Pro and Elite side by side**, five lines each, so the tiers can be compared without scrolling, and the licence-key box stops competing with the buttons · **Best Shots → Review, rebuilt**: whole-folder grid (`G`) with decided photos dimmed rather than hidden, ⌘/⇧ selection that Copy and Move act on, `Next left` to the next undecided photo, camera settings and histogram back and on by default · zooming a RAW now shows the photograph, not the small JPEG preview inside it — which on some bodies covers only 17% of the frame.

**v4.9.0 & v4.8.1 — People that aren't people, and same-disk moves:** face detections that aren't faces are rejected outright on two measured gates, and **"Not a person"** hides whatever still slips through, across re-scans · the duplicate scan's byte-for-byte confirm is now its own visible step and **Cancel works during it** · the People grid no longer freezes the window on a large library · **moving files within one disk is nearly instant** with *Verify Integrity* on — it used to write a complete second copy, ~3 GB of disk work to move a 1 GB video; if you switched verification off to work around that, switch it back on · place lookups reuse a nearby answer, so roughly ¾ of them disappear · the **Photos / Videos / Other** tabs carry their own counts and stop implying they change what gets organized · **Rescan needed** on the Scan button when a file-type setting changes after a scan · **Clear index** for AI Search.

**v4.9.1 — The runs that failed every file, and never said why:** the destination is now tested **once, before the run starts**, across all nine modules that move, copy or delete — one customer's Duplicates → Move to Folder ran five times over four days, up to 8 hours each, and never moved a file · failures name their cause once instead of repeating the same error 605 times, and a **locked** file is told apart from a permissions one · relocating many same-named files no longer slows to a crawl (4,000 files: 157 s → 0.7 s) · star ratings written into photos can be undone, and a rescan no longer throws away the stars you just gave.

**v4.8.0 — Place names written into your photos:** FolioSort always turned coordinates into a place and used it to name folders; now it can write the place **into the file** — the legacy **IPTC** block *and* the Photoshop **XMP** namespace, the two that Lightroom, Bridge, Photo Mechanic and Apple Photos actually read. JPEG/HEIC/TIFF/DNG in place, a sidecar for proprietary RAW, **fully reversible** (a tag that didn't exist is removed on revert, not blanked), and your capture dates never move · **resolving place names is now free**, up to 100 photos per scan.

> 4.8.0 through 4.9.3 shipped on macOS first; Windows caught up over 4.9.4–4.9.6 and both platforms are now on **4.9.7**.

**v4.7.x — AI Search quality & honest walls:** plain-language search got better at saying what it actually found — results say what was searched and flag a weak match as weak, one-word queries are translated before they're matched, and an OCR substring can no longer hijack the result set · the panel at the end of a run leads with **proof of what changed**, not a table of counts · the free-limit wall names the outcome you're buying instead of a tier, and counts your RAW files honestly · a consistent **Scan** button across Rename and Google Photos · **Universal binary** (Apple Silicon + Intel) on macOS.

**v4.6.0 — People:** FolioSort now **groups the faces in your library into people, automatically** — name someone once and the name survives a re-scan, with a *"same person?"* merge queue instead of a threshold slider · **write your named people into XMP sidecars** so Lightroom and Capture One see them · a **People strip** after every Organize run · pick exactly which **file types** a copy/move includes · a **Custom** folder-pattern card that opens the template builder · Elite is now offered wherever Pro is, so Pro owners can actually find it. **Both platforms.**

**v4.5.0 — First-run activation:** one onboarding screen that puts the main action at the entrance, and a destination that defaults to `<source>/Organized` — so the first run works without configuring anything.

**v4.4.0 — Reliability hardening:** 112 correctness fixes from a subsystem-by-subsystem risk review, on **both macOS and Windows** — a cancelled Merge, Organize, Move-to-Folder or Workflow step now always leaves a reachable **Undo** · Undo can no longer destroy its own record, or race a Rename/Organize on the same files · destructive operations never delete a destination they did not create · licensing no longer misreads a transport failure as "not licensed" · folder-name sanitizers match across platforms.

**v4.3.0 — Takeout Auto-Sync & Archive Report:** watch-folder auto-sync for Google Takeout deliveries with incremental merge and duplicate skipping · end-of-run **Archive Report**.

**v4.1.0 — Windows Parity & Polish:** self-contained Windows build — **no .NET install**, with the AI Search and Find a Person models bundled in · macOS and Windows unified on one version number · macOS **visual parity** across every page (true surface colors, right-sized typography, button & heading polish).

**v4.0.0 — Cloud Exit, AI Discovery & Workflows:** the **Exit Kit** cloud-import wizard (WhatsApp, Google Takeout, Amazon Photos, OneDrive, iCloud) with Synology/Immich presets · on-device **AI search** — plain-language + semantic (MobileCLIP2) + **OCR** text search · **Auto-Events** & date inference · **Find a Person** and **Screenshots** as dedicated modes · **Workflows** chaining Organize → Duplicates → Rename → Screenshots → Blurry with per-step undo · **Smart Folders** & **Best Shots** AI culling · sidebar regrouped (Organize · Import & Merge · Clean Up · Find with AI · Automate).

**Earlier — v3.x:** Library-cleanup suite — **Merge Sources**, **Duplicates**, and **Blurry** — on both macOS and Windows · faster NAS/network-drive scanning · in-app Send feedback · signed & notarized macOS build, Microsoft Store on Windows.

---

## License

MIT License — see [LICENSE](LICENSE).

---

<div align="center">

**If FolioSort saved you an afternoon of manual sorting, [⭐ star this repo](https://github.com/tiagotrindade/FolioSort) — it's how other people find it.**

⬇️ **[Download for macOS](https://github.com/tiagotrindade/FolioSort/releases/latest/download/FolioSort.dmg)** · 🪟 **[Get it on the Microsoft Store](https://apps.microsoft.com/detail/9nlw1xwgk181?cid=github)** · 🌐 **[foliosort.app](https://foliosort.app)**

![Page visits](https://hits.sh/github.com/tiagotrindade/FolioSort.svg?style=flat-square&label=Page%20visits&color=8b5cf6)

</div>
