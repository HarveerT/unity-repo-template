# Introduction
Short and sweet intro
- REPLACE ALL METIONS OF ${\textsf{\color{red}'ProjectName'}}$ WITH THE ACTUAL PROJECT NAME



## Index or Table of Contents
- [About](#about)
- [Usage](#usage)
- [Development](#development)
  - [TO-DO](#to-do)
  - [File Structure](#file-structure)
  - [File Descriptions](#file-descriptions)
  - [Style Sheet](#style-sheet)
- [Branches](#branches)
- [Gallery](#gallery)
- [Credits/Acknowledgments](#creditsacknowledgments)

## About
Detailed intro to the game. Everything someone would need to know.

## Usage
A brief synopsis on how to download and use/develop the project
1. Clone repo to your machine
2. Open unity and click Add
3. Navigate to the repo and find the ${\textsf{\color{red}'ProjectName'}}$ folder and open it
4. Allow unity to load and compile, open the StartingStage scene 

## Development
All about the development of this project

### TO-DO
A list of things that need to be done
- [x] Create character controller
  - [x] Create player graphics
  - [x] Create action map
  - [ ] Create AimManager script
  - [ ] Create MovementManager script
  - [x] Create MiscControlsManager script
- [ ] Create Weapons
  - [ ] Import weapons
  - [ ] MAKE EM SHOOT
- [ ] Create Enemies
  - [ ] Create enemy controller
- [ ] Create maps
  - [ ] Map01
  - [ ] Map02
- [ ] Finishing Touches
  - [ ] Post processing
  - [ ] Lighting?
    - [ ] We can go further
- [ ] Etc.
  - [ ] Etc.
    - [ ] Etc.

### File Structure
Add a file structure here with the basic details about files, below is an example.
```
.
├── Assets
│   ├── Input
│   │   ├── Input
│   │   └── Input.cs
│   ├── Scripts
│   │   ├── PlayerControl
│   │   │   ├── MovementController
│   │   │   └── AimController
│   │   ├── SomeOtherFolder
│   │   └── YetAnotherFolder
│   └── MoreFolders
├── .gitignore
├── .gitattributes
└── README.md
```

Another Example
```
Assets
+-- Scripts
|   +-- PlayerScripts
|   |   +-- PlayerMovementController.cs
|   |   +-- PlayerAimController.cs
|   +-- WeaponScripts
|   |   +-- someFile
+-- Prefabs
|   +-- Drops
|   |   +-- SomeDrop
|   |   +-- AnotherDrop       
```

### File Descriptions
| File Name | File Decription | File Path 
|-|-|-|
| MovementController  | Uses the user input from the action map script to move the player using the WASD keys or controller input | ${\textsf{\color{red}'ProjectName'}}$/Assets/Scripts/MovementController.cs
| Input | Action map for input, creates input and auto generates Input.cs script. All controls are first created here | ${\textsf{\color{red}'ProjectName'}}$/Assets/Input/Input

###  Style Sheet
Style sheet for all C# code in this project
> Clean code always looks like it was written by someone who cares  
> \- Michael Feathers, author of Working Effectively with Legacy Code

Please follow the rules laid out in [Google's C# Style Sheet](https://google.github.io/styleguide/csharp-style.html) for this project

**Short Recap of Style Sheet**
- Names of files and directories/folders: **`PascalCase`**
- Names of classes, methods, enumerations, public fields, public properties, namespaces: **`PascalCase`**
- Names of local variables, parameters: **`camelCase`**
- Names of private, protected, internal and protected internal fields and properties: **`_camelCase`**
- For casing, a “word” is anything written without internal spaces, including acronyms. For example, **`MyRpc`** instead of **`MyRPC`**
- Names of interfaces start with **`I`**, e.g. **`IInterface`**
- Modifiers occur in the following order **`public protected internal private new abstract virtual override sealed static readonly extern unsafe volatile async`**
- Class member ordering:
  - Group class members in the following order:
    1. Nested classes, enums, delegates and events
    2. Static, const and readonly fields
    3. Fields and properties
    4. Constructors and finalizers
    5. Methods
  - Within each group, elements should be in the following order:
    1. Public
    2. Internal
    3. Protected internal
    4. Protected
    5. Private

## Branches
1. **`stage`** branch for staging changes to main

2. **`main`** current most clean branch

3. **`temp`** branch for implementing new features

**Temporary Branches**  
Temporary branches are for adding new features which should not be developed in the regular staging branch. To create a temporary branch, create a branch with the format: `temp-feature`. Where `temp` is the prefix for all temporary branches and `feature` is the feature this branch is implementing. For example `temp-bullet-time` would be the branch name for a bullet time feature.

**Pull Requests for Temporary Branches**
1. Make a PR to `stage` branch.
2. Comply with the best practices and guidelines
3. Pass reviews and merge with stage.

After this, changes will be merged.

## Gallery
Pictures of project

## Credits/Acknowledgments
Credit to authors  
@me lmao I don't have friends
