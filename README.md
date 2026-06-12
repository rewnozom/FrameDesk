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

<img width="1917" height="1031" alt="FullView2" src="https://github.com/user-attachments/assets/286bf517-a2da-47c3-b82e-0783849fbe51" />

<img width="1918" height="1029" alt="FullView3" src="https://github.com/user-attachments/assets/e23927c1-e619-4315-9356-c6b9d61e8b49" />

<img width="1918" height="1032" alt="FullView" src="https://github.com/user-attachments/assets/667bd719-f9b7-4d0e-82cf-400dba8ebe66" />

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

`Content List` is best when you want a compact overview.
<img width="578" height="994" alt="ContentList_Roots_Project_on" src="https://github.com/user-attachments/assets/2a46e275-e6fc-4523-b50e-29b51d160dc5" />
----

`Grid` is best when you want visual scanning.
<img width="577" height="399" alt="Grid_all_Project_off" src="https://github.com/user-attachments/assets/ee121b29-8d29-46c2-9051-dc32951181ce" />
---

`List` is best when you want clear rows and paths.
<img width="577" height="429" alt="List_Roots_Project_off" src="https://github.com/user-attachments/assets/803551cc-c460-48a7-a638-321abfa60731" />

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

