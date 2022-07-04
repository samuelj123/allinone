# What the App Should Do

1. OS File Manipulation
2. Text and Text Manipulation
3. SVG Manipulation - Can be a library
4. Video Screening and Controls

### UI for GUI
Based on SVG manipulation and Text Manipulation for GUI with
1. Clickable on shapes or text
2. Clicks/key-presses create animations

### UI for CLI 
1. Text has to be stored in buffers for manipulation
2. Must have a not-too-complicated Command-line interface

## Basic Architecture

### Relies on Packages.
* Base Code should not be more than 2000 lines
* Should contain the languages all the packages speak to each other
* Packages can be installed/uninstalled to add functionality
* Packages can be binaries written in any language.
* Packages can be installed via Github/GitLab

### Possible Packages (BASE)
1. Text-manipulation (backend)
	1. Get input text
	2. Manipulate it using vim-bindings
	3. Send out manipulated text as arguments for other functions
		1. such as file-manipulation
		2. Text-manipulation
		3. Text-formatting (Sync with TeX)
		4. Mind-mapping and Organizing
		5. Task-Organizing and Scheduling
		6. Data Analysis and Management
2. Connect with Database(s) 
	1. For Easy Data entry, 
	2. storage, 
	3. querying and 
	4. analysis
3. Make SVGs
 1. Ability to fill GUI with SVGs
 2. SVGs are clickable
 3. SVGs can animate
4. Talk with OS services
 1. Cut/Paste/Rename/files
5. Work with an LSP Server
