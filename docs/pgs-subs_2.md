# *How to tonemap PGS subtitles for HDR contents (4K Blu-ray)*

Standard Blu-ray PGS subtitles are very bright on HDR content (HDR10, HDR10+, HLG, Dolby Vision). This guide shows how to tonemap them to a darker, less bright gray.

### *Requirements*
1.  [BDSup2Sub](https://www.videohelp.com/download/BDSup2Sub512.jar)
2.  [Java Runtime](https://www.java.com/download/ie_manual.jsp)
3.  [Subtitle Tonemap Tool](https://github.com/quietvoid/subtitle_tonemap/releases/latest/download/subtitle_tonemap-1.0.0-x86_64-pc-windows-msvc.zip)

### *Instructions*

1.  Install Java Runtime.
2.  Create a new folder. Place the downloaded `BDSup2Sub512.jar` and `subtitle_tonemap.exe` files inside it.

    ![Folder contents](https://files.catbox.moe/ni4jtd.png)

3.  Demux the PGS subtitle track(s) from your source (BDMV or REMUX). Use eac3to, MKVToolNix, or a tool like MKVCleaver as shown.

    ![Demuxing with MKVCleaver](https://files.catbox.moe/pkh7lh.png)
    Extract the subtitle file(s) to the folder containing `subtitle_tonemap.exe`.

4.  Open a command prompt (cmd) in the folder containing the tool and subtitle file.

    ![Open CMD](https://files.catbox.moe/ml0dj2.png)

5.  Run the command:
    `subtitle_tonemap.exe "path/to/subtitles" -o tonemapped --percentage 60`

    ![Run command](https://files.catbox.moe/fupb3q.png)
    Replace `"path/to/subtitles"` with the actual filename. The `--percentage 60` argument sets the white level to 60% (recommended). Adjust this value as needed. The `-o tonemapped` argument specifies the output folder name.

6.  After processing, find the tonemapped subtitle file in the new `tonemapped` folder.

    ![Output folder](https://files.catbox.moe/cmr30h.png)

7.  Mux the new subtitle file into your REMUX using MKVToolNix.

### *Comparison (on a SDR screen)*

#### *Original*

![Original](https://files.catbox.moe/fx7cz0.png)

#### *Tonemapped (60%)*

![Tonemapped](https://files.catbox.moe/lfa452.png)

The difference is more significant on an HDR monitor or TV.

### *Credits*
**Old owners** - Unknown (not a username)    
**New / Current owner** - [Clara](https://rentry.co/claraiscute)

[![Fuck AI](https://files.catbox.moe/os5g6k.png)](https://notbyai.fyi)

*(With <3)*

**If you have any feedback you want to give me, please fill in a form [here](https://formulaer.com/f/aa502b70-f46d-4e81-98a2-bd6b2de24540).**

*************

[Go back to the top](#how-to-tonemap-pgs-subtitles-for-hdr-contents-4k-blu-ray)

