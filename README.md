# QuitAll
QuitAll is a lightweight application for macOS, created using the built-in **Automator** tool. With QuitAll, you can instantly quit all running applications except for those you choose to exclude during development.

## Features

- **Quit All Applications**: Closes all applications on your Mac with a single click.
- **Customizable Exceptions**: Keep specific applications running while quitting others.
- **Native Integration**: Built using macOS's Automator application, requiring no additional installations.

---

## How It Works

QuitAll leverages the **Automator** application on macOS, utilizing the `Quit All Applications` functionality to perform its tasks. During the creation process, you can specify certain apps to exclude, ensuring they remain open while others are closed.

## Usage

1. Open **Spotlight Search** (Command + Space).
2. Type `QuitAll` and hit **Enter**.
3. Boom! All applications except the excluded ones will be closed.

---

## Steps to Build It Yourself

### Prerequisites
- A Mac with macOS.
- Basic knowledge of Automator.

### Step-by-Step Guide

1. **Open Automator**:
   - Press Command + Space to open Spotlight Search.
   - Search for and open the `Automator` application.

2. **Create a New Application**:
   - In Automator, select **File > New Document**.
   - Choose `Application` as the document type.

3. **Add the "Quit All Applications" Action**:
   - In the left sidebar, search for `Quit All Applications`.
   - Drag the `Quit All Applications` action to the workflow area.

4. **Customize Exceptions**:
   - Click the "Options" button within the `Quit All Applications` action.
   - Add any apps you want to exclude from being closed.

5. **Save the Application**:
   - Go to **File > Save**.
   - Name it `QuitAll` and save it in a convenient location.

6. **(Optional) Move to Applications Folder**:
   - Drag and drop the QuitAll file into the `Applications` folder for easy access.

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.
