# File Search Tool

A simple and intuitive GUI application built in Python using Tkinter, the File Search Tool empowers users to efficiently search and list files based on specific criteria such as file name, extension, and folder location. This tool is designed to simplify the file-finding process for users who prefer a graphical interface.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [How to Run](#how-to-run)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Navigating through directories to find specific files can be a cumbersome task, especially when dealing with numerous files and folders. The File Search Tool addresses this challenge by providing a user-friendly interface that streamlines the search process. Users can input the target file name, choose an extension, and specify the search folder, resulting in a focused and efficient file search.

## Features

### 1. Intuitive User Interface
The graphical user interface is designed for simplicity, making it accessible for users of all experience levels. Clear labels, input fields, and buttons guide users through the file search process.

### 2. Versatile Search Criteria
Users can search for files based on both name and extension, allowing for precise and customizable searches. The tool recursively scans directories to find matching files and provides a consolidated list of results.

### 3. Result Presentation
Upon completion of the search, users have the option to view the results in Notepad for further inspection. In cases where no matching files are found, a messagebox notifies the user, preventing unnecessary confusion.

### 4. Extension Customization
The tool supports a default set of common file extensions, but users have the flexibility to customize the list based on their specific needs. This ensures adaptability to different use cases.

## Usage

1. **Enter Search Criteria:**
   - Input the desired file name in the "Finding Name" field.
   - Choose the target extension from the dropdown list.
   - Specify the search folder by entering the folder path or using the "Browse" button.

2. **Initiate the Search:**
   - Click the "Find" button to start the search process.

3. **View Results:**
   - Results are presented in Notepad, providing a convenient way to review and analyze the list of matching files.
   - If no files are found, a messagebox notifies the user.

## Dependencies

- **Python 3.x:** The tool is built using Python, so ensure you have a compatible version installed.
- **Tkinter:** Tkinter is included with most Python installations and serves as the GUI toolkit for the application.

## How to Run

1. Ensure you have Python installed on your system.
2. Clone or download the repository.
3. Run the script using the command: `python Find-by-name-extension.py`.

## Customization

Users can customize the list of supported file extensions by modifying the `getJSON` function in the script. Additionally, the default set of extensions is loaded from a JSON file (`Extension-data.json`), which users can update according to their requirements.

## Executable Version

An executable version of the File Search Tool is available for easy use. Download the executable [here](link_to_executable) and follow the instructions in the [How to Run](#how-to-run) section to get started quickly.

## Contributing

Contributions are welcome! Feel free to open issues, submit pull requests, or suggest improvements to enhance the functionality and usability of the File Search Tool.

## License

This project is licensed under the [MIT License](LICENSE), making it open for collaboration and adaptation.

Explore, search efficiently, and simplify your file management tasks with the File Search Tool!
