---
lab:
  title: 'Lab setup: Prepare sample data for Microsoft Copilot'
  description: Microsoft Copilot - Upload sample files to OneDrive for use throughout the labs.
  level: Lab 100
  duration: '10'
  islab: true
  status: 'released'
  targetDate: 2026-12-31
  primarytopics:
    - Microsoft 365
    - Microsoft Copilot
---

# Follow along using sample data with Microsoft Copilot

Throughout these labs, we'll be crafting prompts for Microsoft Copilot that reference the following files:

- [Promotion Plan for Chai Tea in Latin America.docx](https://go.microsoft.com/fwlink/?linkid=2269126)
- [Market Analysis Report for Mystic Spice Premium Chai Tea.docx](https://go.microsoft.com/fwlink/?linkid=2268826)
- [Contoso Chai Tea market trends.xlsx](https://go.microsoft.com/fwlink/?linkid=2268822)

To ensure that these files are accessible later on by Microsoft Copilot, we'll first upload them to OneDrive.

## Uploading Files to OneDrive

Follow the steps below to upload all files needed to **OneDrive**:

1. Log into the virtual machine provided by your tenant provider.

1. Open a **Microsoft Edge** browser and go to +++https://onedrive.live.com/login/+++. Enter the credentials provided to log in.

1. If prompted to stay signed in, select **Yes**.

1. Select **Your OneDrive is ready**, skip any welcome messages, then select **Create or upload > Files upload**.

1. In **File Explorer**, select **This PC** > **Local Disk (C:)** and open the **Allfiles** (MS-4018 ResourceFiles) folder.

1. Select all files within the **MS-4018 ResourceFiles** folder, then select **Open**.

1. When the upload is complete, you should see **Uploaded 4 items to Documents** in the bottom center of the screen.

### Referencing files

When referencing files from Copilot, you might find that you can't find some files from the suggestions provided to you. This happens sometimes because certain experiences with Copilot only reference files from the Most Recently Used (MRU) list, while others let you browse OneDrive to find your file. Adding them to that list is as easy as opening them up in the appropriate Microsoft 365 app.  Once they've been opened, they should appear in the MRU list.

> [!IMPORTANT]
> Microsoft Copilot  will only work with files saved to OneDrive. If files are stored locally on your PC, you'll need to move them to OneDrive to activate Copilot.

As you progress, you'll have an opportunity to try out other prompts against these files and are encouraged to do so to explore and enhance your prompting skills.
