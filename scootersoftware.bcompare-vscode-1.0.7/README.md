# Open files in Beyond Compare directly from VSCode

This extension allows you to open Beyond Compare directly from VSCode in several useful ways.

## Requirements

- Beyond Compare must be installed.
- macOS: **bcomp** command line tool must be installed.  Within Beyond Compare use the **Beyond Compare > Install Command Line Tools...** menu command to install it.
- Compatible with Visual Studio Code for Windows, macOS, and Linux.

## Commands

- [Compare two open files](#compare-two-open-files)
- [Compare highlighted text](#compare-highlighted-text)
- [Compare folders](#compare-folders)
- [Compare files to non-open files](#compare-files-to-non-open-files)
- [Compare parent to folder](#compare-parent-to-folder)
- [Compare to saved version](#compare-to-saved-version)
- [Compare to git repository](#compare-to-git-repository)
- [Compare selected](#compare-selected)
- [Compare to clipboard](#compare-to-clipboard)
- [Open Beyond Compare from Diff Editor](#open-beyond-compare-from-diff-editor)

### Compare two open files
Use this option to select a file for comparison.

![Select a left file](https://github.com/ScooterSoftware/bcompare-vscode/raw/HEAD/images/SelectLeft.PNG)

And then pick another file to compare it to.

![Select a right file](https://github.com/ScooterSoftware/bcompare-vscode/raw/HEAD/images/CompareToLeft.PNG)

You can also right-click on files in the File Explorer.

### Compare highlighted text
Use this option to select the highlighted text for comparison, and then another selection of text to begin the comparison.

![Select text for comparison](https://github.com/ScooterSoftware/bcompare-vscode/raw/HEAD/images/SelectLeftText.PNG)

Text can also be compared to files by selecting a file for comparison first.

### Compare folders
Use this option to select a folder for comparison, and then another folder to begin the comparison.

![Select a folder for comparison](https://github.com/ScooterSoftware/bcompare-vscode/raw/HEAD/images/SelectLeftFolder.PNG)

### Compare files to non-open files 
Use this option to compare a file you pick with an open dialog.

![Select a file for comparison](https://github.com/ScooterSoftware/bcompare-vscode/raw/HEAD/images/CompareToFile1.PNG)
![And then another file to compare it to](https://github.com/ScooterSoftware/bcompare-vscode/raw/HEAD/images/CompareToFile2.PNG)

A similar option exists for folders in the File Explorer.

### Compare parent to folder
Use this option to choose a file and compare the folder it's in to another folder with an open dialog.

![Select a file's parent for comparison](https://github.com/ScooterSoftware/bcompare-vscode/raw/HEAD/images/ParentToFolder.PNG)

### Compare to saved version
Use this option to compare the version of a file you have open in the editor to the version stored on disk.

![Compare a file to the saved version](https://github.com/ScooterSoftware/bcompare-vscode/raw/HEAD/images/CompareToSave.PNG)

### Compare to git repository
Use this option to compare staged or unstaged changes to the last commit in the current branch or compare staged changes to unstaged changes.

![Compare a file to git repository](https://github.com/ScooterSoftware/bcompare-vscode/raw/HEAD/images/GitCompare.PNG)

### Compare Selected
Use this option to compare 2 selected files or folders from the File Explorer.

![Compare 2 files or folders from the File Explorer](https://github.com/ScooterSoftware/bcompare-vscode/raw/HEAD/images/CompareSelected.PNG)

### Compare to Clipboard
Use this option to compare the text on your clipboard to an open file.

![Compare text to an open file](https://github.com/ScooterSoftware/bcompare-vscode/raw/HEAD/images/CompareFileToClipboard.PNG)

Or to a highlighted selection of text.

![Compare text to your clipboard](https://github.com/ScooterSoftware/bcompare-vscode/raw/HEAD/images/CompareTextToClipboard.PNG)

### Open Beyond Compare from Diff Editor
Use this button when you have a comparison open in VSCode to open it in Beyond Compare.

![Open a comparison in Beyond Compare](https://github.com/ScooterSoftware/bcompare-vscode/raw/HEAD/images/OpenCompare.PNG)
