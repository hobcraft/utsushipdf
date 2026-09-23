---
layout: default
title: Support
description: "Support and frequently asked questions for Utsushi PDF, the batch document-to-PDF converter for Mac."
lang: en_US
permalink: /en/support/
---

# Utsushi PDF Support

Questions, bug reports and requests are all welcome. Please email us.

## Getting in touch

**Email: yumsaki@gol.com**

We reply within a few days. For a bug report, it helps a lot to include:

- which Mac and macOS version you are using
- the file type you were converting (docx, xlsx, pptx, etc.)
- whether Microsoft Office is installed
- what you did, and what happened

## Frequently asked

### Does it change the original file?

No. The source file is never modified — the app only creates a new PDF.

### Word, Excel or another app opens on its own during conversion

That is expected — it launches automatically to do the conversion. Please leave it alone
until conversion finishes; using it partway through can interrupt the conversion.

### A folder window appears the first time I save into a folder

It asks you to allow saving PDFs in that folder. Keep the folder selected and click Allow.
It happens once per folder. If you declined, convert again and the same window appears.

### Excel shows “Grant File Access” for Excel files

That is Excel’s own check before it writes a PDF into the folder.
Click Select…, keep the folder as it is, and click Grant Access. Excel remembers it, so it happens once per folder.

### macOS asked to “control” an app

It is needed so the PDF can be exported, and it appears once per format.
If you decline, that format can’t be converted. Nothing about the file’s contents is sent anywhere.

### I declined and now it won’t convert

Click “Open Settings” on the results screen to jump to the right page in System Settings.
Turn on Utsushi PDF there, then click “Convert Again”.

### Can I choose files without dragging?

Yes. Use “Choose Files…” at the top right, or File → Choose Files… (⌘O). You can select several at once.

### What happens if two files share a name?

Nothing gets overwritten. The app saves the new PDF alongside the existing one with a
number, like “File name 2.pdf”.

### I don’t have Microsoft Office. Can I still use it?

Yes. Word, Excel and PowerPoint files are converted with Pages, Numbers and Keynote
instead when Office isn’t installed. Numbers, though, doesn’t always produce A4-sized
pages. If the PDF is for printing or submission, installing Microsoft Office is recommended.

### Tables are cut off, or I get lots of blank pages

That comes from the print settings in the original Excel file. Set the print area and
make sure all columns fit on one page there, then convert again.

### It says the file is damaged

This appears when a file is incomplete — for example, a download that stopped partway.
Try downloading it again, or check whether the original app can still open it.

### Where does the PDF get saved?

Choose in **Output** at the top of the window: next to the original file (the default),
or a folder you pick.

## Requirements

- macOS 14.0 or later
- Works on both Apple silicon and Intel Macs

## Privacy

[Privacy Policy]({{ site.baseurl }}/en/privacy/)
