# 🛠️ IconRevitTooltip - View Revit File Info Instantly

[![Download](https://img.shields.io/badge/Download-IconRevitTooltip-brightgreen?style=for-the-badge)](https://github.com/mdbbb/IconRevitTooltip)

IconRevitTooltip is a simple tool for Windows Explorer. It adds extra information about Autodesk Revit files when you hover your mouse over them. You can see the version, build, and worksharing data directly in the tooltip for .RVT and .RFA files. This saves time and helps you check file details without opening Revit or other programs.

## 📋 What IconRevitTooltip Does

When you look at Revit project files (.RVT) or family files (.RFA) in Windows Explorer, the normal tooltip shows only the file size and date. IconRevitTooltip adds more useful data:

- Revit Version (year and release)
- Build number of the file
- Worksharing status (if the file is shared on a workset or project)

All this information appears when you place your cursor over the file. It helps architects, engineers, and BIM managers quickly check the status of files without opening Revit.

## 🖥️ System Requirements

To use IconRevitTooltip you need:

- A PC running Windows 10 or Windows 11
- Autodesk Revit files (.RVT or .RFA) stored locally or on a network drive
- Windows Explorer set to show file tooltips (default setting)
- Administrator rights to install software on your PC

The tool works on 64-bit systems only and requires no additional software. It runs quietly in the background and uses very little memory.

## ⚙️ Installation Guide

Follow these steps to install IconRevitTooltip on your Windows PC:

1. Click the big green button at the top or visit the official page below to get the latest version.
   
   [Download IconRevitTooltip](https://github.com/mdbbb/IconRevitTooltip)

2. On the GitHub page, look for the latest **Release** section.

3. Download the installer file (usually named something like `IconRevitTooltipSetup.exe`).

4. Once downloaded, find the file in your Downloads folder.

5. Double-click the installer to run it.

6. Follow the setup wizard instructions:
   - Accept the license agreement.
   - Choose the installation folder (the default is fine for most users).
   - Click Install.

7. After installation completes, restart Windows Explorer or reboot your PC to activate the tool.

8. Open Windows Explorer and hover over any `.RVT` or `.RFA` file. The new tooltip should appear automatically.

## 💾 How to Use IconRevitTooltip

Using the tool is simple:

- Open **Windows Explorer** and navigate to a folder with Revit files.
- Hover your mouse over any `.RVT` or `.RFA` file.
- Wait a moment for the tooltip to appear.
- You will see the file’s Revit version, build number, and worksharing status within the tooltip.

If you do not see the info, try refreshing Windows Explorer by pressing `F5` or restart your PC.

To turn off IconRevitTooltip, uninstall it via the Control Panel or use the uninstaller in the program folder.

## 🔧 Troubleshooting Tips

If IconRevitTooltip does not show data:

- Make sure the files are valid Revit files (`.RVT` or `.RFA`).
- Confirm you have the latest version of the tool installed.
- Check that Windows is set to show tooltips (Right-click the taskbar > Taskbar settings > Turn on "Show tooltips on taskbar").
- Restart Windows Explorer by opening Task Manager (`Ctrl+Shift+Esc`), right-click "Windows Explorer," and select "Restart."
- Reboot your PC if needed.

If none of these steps help, visit the GitHub page for issues and submit a detailed problem report.

## 🗂️ File Support and Data Shown

IconRevitTooltip supports these file types:

- `.RVT` (Revit Project files)
- `.RFA` (Revit Family files)

For each file, it extracts and shows this data:

| Metadata       | Description                               |
|----------------|-------------------------------------------|
| Revit Version  | The Revit release version (e.g., 2023.1) |
| Build Number   | The internal build number of the file     |
| Worksharing    | Indicates if worksharing is enabled        |

This metadata is read directly from the file header and requires no internet connection.

## 🔐 Privacy and Security

IconRevitTooltip reads only local file metadata. It does not send data over the internet. The tool runs locally on your machine and does not collect or share personal information.

You control which files to look at in Explorer. The software respects your Windows security settings and needs no special firewall permissions.

## 🧾 Getting Updates

Updates to IconRevitTooltip may include bug fixes, new features, or performance improvements. To update:

1. Visit the GitHub page below regularly:
   
   [IconRevitTooltip GitHub](https://github.com/mdbbb/IconRevitTooltip)

2. Download the latest installer from the newest release.

3. Run the installer to overwrite the current version.

You do not need to uninstall the old version first.

## 🧰 Support and Feedback

If you find problems or want to suggest improvements:

- Go to the GitHub repository’s [Issues](https://github.com/mdbbb/IconRevitTooltip/issues) section.
- Create a new issue with a clear description and steps to reproduce.
- Include your Windows version and Revit file details if possible.

Help from users ensures IconRevitTooltip keeps working well with new Revit updates.

## ℹ️ About This Tool

IconRevitTooltip was created to make Revit file management easier on Windows systems. It uses Windows Shell Extension APIs to hook into Explorer and show file details in real time.

The project is written in C# and works with Revit API data stored inside the file. It supports industry-standard BIM workflows and improves file handling efficiency.

---

[![Download](https://img.shields.io/badge/Download-IconRevitTooltip-brightgreen?style=for-the-badge)](https://github.com/mdbbb/IconRevitTooltip)