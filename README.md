# Brain View Pro (3D 知识大脑专业版)

[English](./README.md) | [简体中文](./README.zh.md)

**Turn your Obsidian vault into an interactive 3D Brain Galaxy with a built-in Study & Note-taking Workbench.**

Brain View Pro is an advanced 3D knowledge graph plugin for [Obsidian](https://obsidian.md). It organizes notes into hierarchical **3D Globular Star Clusters**, eliminates tangled wireframe clutter, and integrates a **resizable floating study card** with full Markdown preview, personal note auto-syncing, and custom node status coloring.

---

## ✨ Key Features

### 1. 🪐 3D Globular Clusters & Clean Neural Spine Links
- **Hierarchical Sector Organization**: Notes are automatically clustered into non-overlapping 3D spherical lobes according to your folder hierarchy (e.g. Subjects → Major Modules → Sub-topics).
- **Anti-Cobweb Filtering**: Fades out peer-to-peer mesh clutter across question notes in the background, rendering clean radial spine links from cluster hubs. Selecting any note immediately illuminates its 1-hop and 2-hop cross-links.
- **Floating 3D Region Badges**: Floating neon badges hover above major topic hubs with node counts. Click any badge to fly directly to that cluster.

### 2. 🎨 Node Color Marking & Status Pills
- **7 Study & Review Presets**: Instantly tag notes as **Key/Error** (`#ff3b5c`), **Doubt** (`#ff9f1c`), **Review** (`#facc15`), **Mastered** (`#10b981`), **Archetype** (`#00e5ff`), **Advanced** (`#c084fc`), or **Archived** (`#94a3b8`).
- **Free Color Picker & 1-Click Reset**: Pick any custom hex color or restore the default brain region theme.
- **3D Graph Sync & Search Priority**: Marked nodes automatically override regional colors, expand by `1.65x` in the 3D graph for instant visibility, and are pinned to the top of quick search (`Ctrl/Cmd + F`).

### 3. 📖 Full Markdown Preview & Interactive Callouts
- **No More Truncation**: Renders complete Obsidian Markdown notes inside the floating card, including YAML frontmatter badges, math equations, tables, and images.
- **Collapsible Answers & Explanations**: Click to fold/unfold `> [!success]- Click to view answer and explanation` callouts directly inside the card — practice and review questions without leaving the 3D galaxy.
- **3D Link Traversal**: Clicking internal `[[wikilinks]]` smoothly flies the 3D camera to the destination note.
- **Source Editor Toggle**: Switch between formatted Markdown preview and raw source code with one click.

### 4. 📝 Personal Note-Taking & Annotation Sync
- **Dedicated Annotation Pane**: Built-in notepad at the bottom (or side-by-side in wide mode) for study reflections, mistake logs, or personal insights.
- **Two-Way File Sync**: Automatically saves your notes directly to the end of your `.md` file under `## 📝 个人笔记` with debounced auto-save.
- **Seamless Flow**: Protected with self-save locking so saving notes never interrupts your 3D view or resets selection.

### 5. ⤢ Resizable Card & One-Click Wide Split Screen
- **Spacious Default Window**: Default size of `540 × 680 px` with complete event isolation (scrolling or typing will never trigger 3D zoom or camera rotation).
- **Split-Screen Mode**: One-click toggle to wide split mode (`860 × 720 px`) — view questions and explanations on the left, write notes on the right.
- **Smooth Drag & Resize**: Drag the header to move, and drag the corner handles to resize freely with remembered dimensions.

### 6. 🥽 VR & DNA Connectome Export
- **Noda VR (Quest 3)**: Export your 3D connectome to CSV and explore your brain graph in immersive Virtual Reality via [Noda](https://noda.io).
- **Brain DNA Export**: Export a frozen CSV connectome snapshot capturing all nodes, links, and 3D coordinates.

---

## 📥 Installation

### Method 1: Obsidian BRAT (Recommended for Instant Updates)
1. Install and enable the **BRAT** plugin from Obsidian Community Plugins.
2. In BRAT settings, click **Add Beta plugin**.
3. Enter: `P123149P/brain-view-pro`
4. BRAT will automatically download, install, and notify you of new updates.

### Method 2: Manual Installation
1. Go to [Releases](https://github.com/P123149P/brain-view-pro/releases) and download `main.js`, `manifest.json`, and `styles.css`.
2. In your Obsidian vault, navigate to `.obsidian/plugins/` and create a folder named `brain-view-pro`.
3. Copy the 3 downloaded files into `.obsidian/plugins/brain-view-pro/`.
4. Open Obsidian → Settings → Community plugins → Reload and enable **Brain View Pro**.

---

## 🎮 Keyboard & Mouse Controls

| Action | Control |
|---|---|
| **Rotate Galaxy** | Left-click drag |
| **Pan Camera** | Right-click drag |
| **Zoom In / Out** | Mouse wheel |
| **Select / Fly to Node** | Left-click node or 3D badge |
| **Free Flight** | `W` / `A` / `S` / `D` (forward/left/back/right), `Q` (down), `E` (up) |
| **Fuzzy Search** | `Ctrl + F` / `Cmd + F` |
| **Reset View** | Click **Recenter** or press `R` |
| **Close Card** | `Esc` or click `✕` |

---

## 📜 Acknowledgments & License

- Built upon [digent-view](https://github.com/yanghuaqlx/digent-view) by Yang Hua and [galaxy-view](https://github.com/longwind1984/galaxy-view) by @longwind1984.
- Licensed under the [MIT License](./LICENSE).
