# Introduction
Short and sweet intro

## Index or Table of Contents
- [About](#about)
- [Usage](#usage)
- [Development](#development)
  - [TO-DO](#to-do)
  - [File Structure](#file-structure)

## About
Detailed intro to the game. Everything someone would need to know.

## Usage
A brief synopsis on how to download and use/develop the project
1. Clone repo to your machine
2. Open unity and click Add
3. Navigate to the repo and find the ProjectName folder and open it
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
    - [ ] We can go farther
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

| File Name | File Decription | File Path 
|-|-|-|
| MovementController  | Uses the user input from the action map script to move the player using the WASD keys or controller input | ProjectName/Assets/Scripts/MovementController.cs
| Input | Action map for input, creates input and auto generates Input.cs script. All controls are first created here | ProjectName/Assets/Input/Input

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
I keep two branches open

1. **`stage`** is the development branch.

2. **`main`** is the production branch.

3. No other permanent branches should be created in the main repository, you can create feature branches but they should get merged with the master.

**Steps to work with feature branch**

1. To start working on a new feature, create a new branch prefixed with `feat` and followed by feature name. (ie. `feat-FEATURE-NAME`)
2. Once you are done with your changes, you can raise PR.

**Steps to create a pull request**

1. Make a PR to `stage` branch.
2. Comply with the best practices and guidelines e.g. where the PR concerns visual elements it should have an image showing the effect.
3. It must pass all continuous integration checks and get positive reviews.

After this, changes will be merged.

## Gallery
Pictures of your project.

## Credit/Acknowledgment
Credit the authors here.
