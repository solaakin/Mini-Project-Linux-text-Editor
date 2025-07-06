# Mini Project – Text Editing in Linux: VIM and NANO

# 1. Introduction to Linux Text Editors

### The use of Linux text editors are essential for configuring system files, writing shell scripts, and managing application data. In this project, we explore VIM, a powerful modal editor preferred by advanced users, and NANO, a user-friendly editor great for beginners.

Tool	Description
|Table Name| Description|
|-----|-----|
|Ubuntu 22.04	|Operating system|
|VIM	Advanced |CLI text editor|
|Nano	|Simple CLI text editor|
|Terminal	|Command-line interface (CLI)|

## Starting with VIM

#### VIM (Vi IMproved) is a powerful and highly configurable text editor used for efficient text manipulation in the terminal.

## 2. Lanuching VIM

##### vim filename.txt

#### (NOTE) If the file doesn't exist, VIM creates it.

![ vimfilenametxt](https://github.com/user-attachments/assets/4e2fd147-936f-479f-8f7b-01def379e00f)

![viminstall](https://github.com/user-attachments/assets/11416020-bb0d-412e-86e0-7d77edcbd9b8)

![ VimNormal](https://github.com/user-attachments/assets/d138d392-ee4e-4083-b084-b0d05e0f4be5)

# 3. Understanding VIM Modes
#### VIM operates in different modes to separate actions like navigation, editing, and executing commands.

- Normal Mode – Navigation and command execution

![ VimNormal](https://github.com/user-attachments/assets/b9447b84-7412-433e-89b8-7ea38749f959)

- Insert Mode – Typing and editing text

![ InsertingVim](https://github.com/user-attachments/assets/6db56402-4db2-4d93-b146-a7ecb47989b4)

- Command Mode – Saving, quitting, searching, etc.

![ vimCommand](https://github.com/user-attachments/assets/72de6ce0-b838-40b6-87d4-96a662200c95)

 ## Switching Between Modes

 ![ vimWQ](https://github.com/user-attachments/assets/d9f789ab-5fb8-474e-8f91-47cb569e57c4)

  - To Return to Normal Mode

![ vimfilenametxt](https://github.com/user-attachments/assets/21418faf-65ab-4eb9-9e76-587e50e85d5e)

# 4. Essential VIM Commands

|Table Name| Description |
|-----|-----|
|Task| Command|
|Save and exit|	:wq or ZZ|
|Save only|	:w|
|Quit without saving|	:q!|
|Delete a line	|dd|
|Copy a line	|yy|
|Paste	|p|
|Move to beginning of line	|0|
|Move to end of line	|$|
|Search for a word	|/word|

### Visual Walkthrough
#### Save and Exit

![ vimWQ](https://github.com/user-attachments/assets/1896687d-a2e6-485a-b0a5-f6cfb047ff75)

## Cat saved content
![ catFilename](https://github.com/user-attachments/assets/7fd27561-6670-4e62-bef8-6165763afab6)

### Then Save without existing

![ saveWithoutExiting](https://github.com/user-attachments/assets/f830671b-1d11-4465-bfac-76969d8c4906)

![ SavedWithoutExiting](https://github.com/user-attachments/assets/4409248d-1bb9-4c22-9307-50407ac0a386)

### Then Quit without saving

![ QuitWithoutSaving](https://github.com/user-attachments/assets/e4e2948b-0167-4a74-ab75-5243f4964bce)

### Confirm unsaved change

![ Catunsavedchange](https://github.com/user-attachments/assets/d0cd39e7-277e-4981-89bd-35fd218f8a5a)

### Delete a line with 

![ linetodelete](https://github.com/user-attachments/assets/69e22561-34f4-4eab-b511-f0ab9e9a4b6f)

### Now line deleted

![ NowLinedeleted](https://github.com/user-attachments/assets/6a34e527-5dfd-4ab8-a067-933b40b62f58)

### Copy a line with 

![Tocopyline](https://github.com/user-attachments/assets/636812b1-6b99-4cb0-a2e6-f25f7ac11b75)

### Pasting the copied line with p

![ LineNowCopy](https://github.com/user-attachments/assets/93658b64-f2c8-4098-8219-e7916efccfd6)

![ CopyPasted](https://github.com/user-attachments/assets/f4b09507-9563-42f3-ade9-6fd206a01c67)

### Moving beginning of line with 0

![ Tomovebetweenlines](https://github.com/user-attachments/assets/d7bf2236-8417-46d4-94e2-7351c0d133bb)

![ Movedbetweenlines](https://github.com/user-attachments/assets/b30f9e42-dcde-4c2d-b77a-ae8602e4313d)

### Move to the end of line with $

![ movedtoendoflin](https://github.com/user-attachments/assets/12a24d75-5c0f-4e73-9fa5-0edb26e5b650)

### Searching for word with /word 

![ Searchforwords](https://github.com/user-attachments/assets/54ebf512-5b7a-4fd6-b893-fef535c7c913)

# 5. Editing a File with VIM

#### vim filename.txt

![ VimEditFile](https://github.com/user-attachments/assets/a6ecada0-bebd-457a-b2e1-46029259dff5)

## Insert the following text:

### They are
#### Hello world!
#### This is VIM.

![InsertingVim](https://github.com/user-attachments/assets/3b7f2717-81af-4c3e-9dff-015c9a3fbb0e

### Save and Exit

### Type :wq to exit vim from normal mode

![VimEditFile](https://github.com/user-attachments/assets/38d9ee9b-bcf0-4202-b3a7-b14c5a218cae)

### You are back to the terminal

![ BacktoTerminal](https://github.com/user-attachments/assets/577bc8d3-2160-4c6c-878e-9fb281cb1a22)

# 6. Introduction to NANO

### NANO is a simple and easy-to-use terminal text editor. Its commands are listed at the bottom of the screen, making it beginner-friendly.

![ NanoInterface](https://github.com/user-attachments/assets/88e122da-6fc5-40b2-a4be-390be58be513)

###  Launching NANO

### nano filename.txt

![ variousCommands](https://github.com/user-attachments/assets/b103af77-bf73-4e06-83c9-cc003e13641f)

# 7. Common NANO Commands

![ NanoTxtFile](https://github.com/user-attachments/assets/bb7d1ede-2f01-42d8-be47-95723e05bf19)

|Table Name| Description|
|-----|-----|
|Task	|Command|
|Save	|Ctrl + O|
|Exit	|Ctrl + X|
|Cut line	|Ctrl + K|
|Paste line	|Ctrl + U|
|Search	|Ctrl + W|
|Go to line number	|Ctrl + _|

## Editing a File with NANO

#### nano example.txt

![variousCommands](https://github.com/user-attachments/assets/b9b65256-2e3e-4705-ba7b-8949f9eb90b3)

### Type the following:

#### Welcome to NANO editor!
#### Simple and fast.

![ TypeInNanoFile](https://github.com/user-attachments/assets/5c16450b-ad47-4f8c-a484-b7a63318d9eb)

## Save and Exit

- Ctrl + O → Enter to save

![ NanoToSave](https://github.com/user-attachments/assets/a8d70bf3-5fce-4139-bf25-5a0e9a3e2e20)

![ ToSaveNano](https://github.com/user-attachments/assets/b183d557-b6d6-42d8-99a3-1b9fd3967531)

### Save and Exit
#### Ctrl + O → Enter to save

![ Nanoexit](https://github.com/user-attachments/assets/7b65feb6-ec7c-474e-87c2-bd3b10875fc8)

# 9. VIM vs NANO: Feature Comparison

|Table Name| Description|
|-----|-----|
|Feature|	VIM| NANO|
|Learning |Curve	Steep	|Beginner-friendly|
|Speed	|Very fast (with mastery)	|Moderate|
|Interface	|Modal	|Non-modal (menu-driven) |
|Use Case	|Power users, developers	|New users, quick edits|

# 10. Conclusion
### The Study of both VIM and NANO equips you with flexibility and confidence to work efficiently in various Linux environments—whether you're configuring servers or writing code on the fly.








