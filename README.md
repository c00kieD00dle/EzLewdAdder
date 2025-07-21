# EzLewdAdder

A simple **Playnite Generic Plugin** that creates a game entry based on a f95 link.

---

## ✅ Features
- Adds a **"Add Game from F95 Link"** option to the Playnite main menu.
- Fetches the gamename and creates entry in the format ```gamename [version]```.
- Sets the correct tags.
- Sets Plattform to ```hidden``` to easily hide all F95 games.
- Sets AgeRating to ```18```.
- Sets Source to ```f95```.
- Sets Categorie to ```HTML```, ```Ren'Py```, ```RPGM```, etc.
- Tries to set plattform to ```VN``` if found in title.
- Creates a screenshotsdirecotry in the ExtraMetaData folder ```gameID/Screenshots``` for ScreenshotsVisualizier.
- Creates installdirectory named ```gamename```
- Downloads the game images and gives you the option which to pick as background, screenshots and cover image.
- Coverimage crop function.

---

## 🛠 Requirements
- **Playnite** 10.37 (or newer)
- **Playnite SDK** 6.12
- **ScreenshotsVisualizier**

---

## ⚙️ Settings
Accessible under **Extensions → UpdateChecker → Settings**:

- **Library Games Folder**  
- **Extra Metadata Directory** (usually found at AppData\Local\Playnite\ExtraMetadata)
