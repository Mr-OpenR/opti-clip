# opti-clip
Photo Editing Prompt Vault

# Photo Editing Prompt Vault

A zero-install, single-file web utility for managing, categorizing, pinning, and quick-copying AI photo editing and generation prompts. Pre-loaded with a master collection of 100+ prompt templates from the AI editing guide [source: 1].

## Features

* **One-Click Copy**: Click any prompt card to copy text straight to your clipboard with a confirmation toast.
* **Categorization & Filtering**: Organize prompts into tags with live search, dropdown filters, and category badge chips.
* **Pinning**: Pin individual priority prompts or entire categories to float them to the top.
* **Full CRUD**: Add, edit, and delete prompts or categories directly through the UI.
* **Backup & Restore**: Export and import complete vault states via JSON.
* **Theme Support**: Seamless toggle between dark and light modes (persisted locally).
* **Local Persistence**: Saves all changes automatically to browser `localStorage`.

<img width="932" height="882" alt="image" src="https://github.com/user-attachments/assets/0e2479c6-a565-4794-93b8-cbafcfa78367" />

## Quick Start

1. Download `index.html`.
2. Double-click to open in any web browser (Chrome, Safari, Edge, Firefox).

---

# User Guide: AI Photo Editing Prompt Vault

## 1. Interface Overview

* **Top Bar**: Search bar, category filter dropdown, JSON export/import buttons, theme switcher (`☀ Light Theme` / `🌙 Dark Theme`), and `+ New Prompt`.
* **Category Manager Strip**: Displays all tags with item counts. Click a tag to filter; click `★` to pin/unpin an entire category; click `✕` to delete a category and its prompts.
* **Pinned Section**: Floating priority zone for starred prompts and categories.
* **Prompt Library**: Main grid of prompt cards.

## 2. Core Actions

* **Copy a Prompt**: Click directly on any prompt card body text. A green toast (`Copied to clipboard!`) confirms copy.
* **Add a Prompt**:
1. Click `+ New Prompt` in the top right.
2. Enter or select a category tag.
3. Enter your prompt instruction text (fill in bracketed placeholders like `[object]` or `[outfit]` specific to your photo).
4. Click `Save Prompt`.


* **Edit a Prompt**: Click the pencil icon (`✎`) on a prompt card, modify fields in the modal, and save.
* **Delete a Prompt**: Click the red danger icon (`✕`) on a card and confirm deletion.
* **Pin / Unpin**: Click the star icon (`★`) on a prompt card header to float it to the top pinned section.

## 3. Managing Categories

* **Add Category**: Click `+ Add Category` in the category bar, enter the name, and fill in the first prompt shortcut.
* **Pin Category**: Click `★` on any category badge in the category strip to elevate all prompts in that group.
* **Filter by Category**: Click a category badge chip or use the category dropdown selector.

## 4. Backup & Restore

* **Export**: Click `Export JSON` to download a timestamped `.json` backup file containing your prompts and pinned category states.
* **Import**: Click `Import JSON`, select a backup `.json` file, and confirm replacement/merge.

## 5. Quick Pro-Tips for AI Photo Editing

* **Upload First**: Always upload your source photo into your target AI editor (Gemini, ChatGPT multimodal, or Photoshop Generative Fill) before prompting.
* **Protect Identity**: For portraits, include explicit preservation cues: *"Preserve exact identity, face shape, pores, and facial structure."*
* **Ground Elements**: When adding or replacing objects in a scene, specify lighting, scale, camera angle, and contact shadows to prevent a "sticker" look.



