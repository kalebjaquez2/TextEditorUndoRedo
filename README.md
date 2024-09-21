# TextEditorUndoRedo
This project contains a basic text editor with implemented functionality for **Undo** and **Redo** operations, as well as file opening and saving features. It uses C# and Windows Forms for the GUI.


## Features
- **Undo/Redo**: Users can undo or redo the last text modifications, including both text insertions and deletions.
- **File Open/Save**: Users can open text files to edit and save their changes back to the file system.
- **Encryption**: A simple character rotation encryption feature using ROT13 to encrypt text in the editor.

## Key Components
- **Edit History Management**: Implemented using two stacks (`_editHistory` and `_undoHistory`) to store the user’s text modifications and allow undo/redo actions.
- **File Handling**: The program can open text files from the user's file system and save them after modifications.

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/TextEditorUndoRedo.git
    ```

2. Open the project in Visual Studio or your preferred IDE.

3. Run the project:
    - Compile and run the project using the built-in tools of your IDE.

## Example
- **Undo/Redo**: When the user modifies the text and then undoes or redoes the changes, the program uses a stack-based system to revert or reapply the edits.
- **File Open/Save**: After opening a text file, the user can modify the content, and then save the changes back to the file.

## Future Enhancements
- Add keyboard shortcuts for Undo (Ctrl+Z) and Redo (Ctrl+Y).
- Improve file handling to support additional file formats.
