# EzLewdAdder

A simple **Playnite Generic Plugin** that creates a game entry based on a f95 link.

---

## ✅ Features
- Adds a **"Add Game from F95 Link"** option to the Playnite main menu.
- Fetches the gamename and creates entry in the format ```gamename [version]```.
- Sets the correct tags.
- Sets Plattform to ```hidden``` to easily hide all F95 games 😉.
- Sets AgeRating to ```18```.
- Sets Source to ```f95```.
- Sets Categorie to ```HTML```, ```Ren'Py```, ```RPGM```, etc.
- Sets the f95 thread link.
- Tries to set plattform to ```VN``` if found in title.
- Creates a screenshotsdirecotry in the ExtraMetaData folder ```gameID/Screenshots``` for ScreenshotsVisualizier.
- Creates installdirectory named ```gamename```
- Downloads the game images and gives you the option which to pick as background, screenshots and cover image.
- Coverimage crop function.

---

## 📝 Task you have to manually do
- (Optional) Fill missing information like description etc.
- Download and install/dezip the actual game to the correct folder.
- Set the game as installed in playnite under edit game details -> installation (checkmark installed).
- Add the start action under edit game details -> Actions -> add action (just set the games .exe as the path, for HTML games you have to set the Path to your browser and give the games index.html as an argument).

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
