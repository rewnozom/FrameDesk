# FrameDesk
FrameDesk is an Electron desktop (File-Explorer) for project management, designed for users who work across many local projects simultaneously. 
It uses a JavaScript-based Electron architecture with IPC between the renderer and main process, and includes a Rust-based Scanning_Engine for framework detection.

<img width="1378" height="1389" alt="Interface" src="https://github.com/user-attachments/assets/46f77d81-7dbf-4fbb-b859-50f818438987" />

---

https://github.com/user-attachments/assets/53aea527-923b-4a49-b96e-06631f9c46bc

---

## High performence (Properties with data sections)
<img width="832" height="694" alt="image" src="https://github.com/user-attachments/assets/60bff79a-81a2-4872-9e74-e35ab8eeabbe" />


### Press F1 for ``(Settings menu)``
<img width="1377" height="859" alt="settings_menu" src="https://github.com/user-attachments/assets/e596fed5-6db4-41b0-802e-929abd79fcb4" />

### Use (Scan folder) to automaticly pick up your frameworks/projects
<img width="1376" height="856" alt="image" src="https://github.com/user-attachments/assets/e5a7c98b-54b7-4b19-add0-aa9f7925599d" />

### Orginize all tabs into dropdown-like: `FOLDABLE` with color and naming
<img width="884" height="223" alt="GroupTabs" src="https://github.com/user-attachments/assets/4e74115c-ddfc-484b-a459-a220f06b1968" />
<img width="360" height="193" alt="grouptags_color" src="https://github.com/user-attachments/assets/2a579217-d847-49ea-9102-80177ed8999c" />


### Take help from the WIZARD to create the fondation and personalize your categories:
<img width="1377" height="858" alt="WIZARD" src="https://github.com/user-attachments/assets/12015416-dc5a-482e-af33-0b1fe35feb80" />

### Mark the path and enter (cmd) or (ps1) to open the path in terminal:
<img width="1105" height="355" alt="image" src="https://github.com/user-attachments/assets/1fd68e6b-2859-49a7-aa3d-c2cee343d3c0" />

### View inside (Zip/Tar or other archive) with markdown-tree view with (Preview):
<img width="928" height="825" alt="image" src="https://github.com/user-attachments/assets/995315a1-c59e-4678-9dbb-5da1a9b0a8b7" />


---
# NEW FETURE WorkspaceOS panel. **WorkspaceOS panel is currently: (beta)**
> FrameDesk Setup v1.1.4
# What Is WorkspaceOS?

WorkspaceOS is a fast navigation panel for your SSD workspace structure.
It gives you one place to browse root folders, child folders, projects, favorites, and per-drive indexes.
 
to index your (SSD/Drive) run = (Update Index).
If you want to index all drives run = (Upt Indx All SSD) instead.


---
# Full View:

<img width="1918" height="1031" alt="_FullView4" src="https://github.com/user-attachments/assets/6089d5f9-d35c-497e-9136-d0691e621ffb" />

<img width="2557" height="1387" alt="_FullView2" src="https://github.com/user-attachments/assets/e3953a04-798b-463c-87db-877decdee909" />

<img width="2555" height="1394" alt="_FullView" src="https://github.com/user-attachments/assets/22a5d071-be2f-4ee4-b3a8-045f057ec580" />

---

## Why It Helps

- Jump around large SSD workspaces without digging through folders manually.
- Easier visualize all project and can navigate throughout very easy
- Toggle `Project View` when you want to view all (depth-3 project) folders can be mixed with diffrent layout (grid/list/content list)
- WorkspaceOS has its own separate favorites list from normal FrameDesk favorites, so you can personalize it for a project and keep your main favorites for personal directories.

## Expected Structure
WorkspaceOS expects a simple 3-level organization:

```
Level 1: Root directories
Level 2: Children directories
Level 3: Projects
```

Example:

```markdown
01_Development/
└── 00_Active_Projects/
    └── _FrameDesk_Family/
```

However, 
After level 3, you can organize the project however you want. WorkspaceOS treats level 3 as the project entry point, not the end of your structure.

```markdown
.
└── 01_Development/
    └── 00_Active_Projects/
        └── _FrameDesk_Family/
            ├── .Framework-Principle.md
            ├── FrameDesk/
            │   ├── FrameDesk_V0a_001
            │   ├── FrameDesk_V0a_002
            │   ├── ....+n
            │   ├── FrameDesk_V0a_339
            │   └── FrameDesk_V0a_340
            ├── script
            ├── ScrollMenu
            └── sibbling_apps
```

## Layouts

#### `Content List`
<img width="713" height="983" alt="contentlist" src="https://github.com/user-attachments/assets/d3b10137-500a-43b2-ae9c-da355b08e346" />

----

#### `Grid`
<img width="722" height="994" alt="grid" src="https://github.com/user-attachments/assets/3653b1ab-61d0-4e58-874b-b1a9a4367266" />

---

#### `List`
<img width="717" height="995" alt="list" src="https://github.com/user-attachments/assets/23ae386d-fe4a-481e-91f3-e443c33ba7ff" />


---

## Where Data Is Saved
WorkspaceOS saves its own data in FrameDesk appdata:

```
C:\Users\{username}\AppData\Roaming\framedesk\data\WorkspaceOS>
favorites.json
.gitignore
A_Drive_.gitignore
A_Drive_Workspace_Structure_Index.jsonl
A_Drive_Workspace_Structure_Projects_Index.jsonl
B_Drive_.gitignore
B_Drive_Workspace_Structure_Index.jsonl
B_Drive_Workspace_Structure_Projects_Index.jsonl
config.json
C_Drive_.gitignore
C_Drive_Workspace_Structure_Index.jsonl
C_Drive_Workspace_Structure_Projects_Index.jsonl
D_Drive_.gitignore
D_Drive_Workspace_Structure_Index.jsonl
D_Drive_Workspace_Structure_Projects_Index.jsonl
E_Drive_.gitignore
E_Drive_Workspace_Structure_Index.jsonl
E_Drive_Workspace_Structure_Projects_Index.jsonl
F_Drive_.gitignore
F_Drive_Workspace_Structure_Index.jsonl
F_Drive_Workspace_Structure_Projects_Index.jsonl
G_Drive_.gitignore
G_Drive_Workspace_Structure_Index.jsonl
G_Drive_Workspace_Structure_Projects_Index.jsonl
```

------
---

## Why FrameDesk exists
Instead of forcing users into a rigid system, FrameDesk is designed to adapt.
Day-to-day work usually needs more than one tool at the same time.
FrameDesk was built to bring those needs together in one workspace.

When projects live across many folders and naming styles, they become harder to navigate, harder to maintain, and easier to forget.
FrameDesk helps turn that into a structure people actually can work with.

## What it helps solve / Key features:
- organize projects into categories, subcategories, families, groups, and uncategorized areas
- open a project in its preferred tool
- launch PowerShell, CMD, Explorer, VSCode or even run the projects main directly.
- scan_folders and detect projects automatically (Auto-detection for runnable Node, Rust, Python, and PowerShell-related projects)
- Framework-oriented tools for scanning, detecting, and organizing local project collections
- Split explorer view for working with project structure and real files side by side

FrameDesk gives users UI control without losing structure, including:
- Theme control with both global presets and per-section overrides
- Visual customization for header, sidebar, explorer, panels, buttons, popups, icons, and directories
- directory and file and icon styling choices

## In short

FrameDesk is built for developers and technical users who want a better way to organize, launch, browse, and manage many local projects from one place.

