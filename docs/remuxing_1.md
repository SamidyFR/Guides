# *Guide on How to Make a Blu-ray REMUX from a Blu-ray Disc (eac3to)*

[TOC3]

### *Programs needed*
*   **[BDINFO](https://www.videohelp.com/software/BDInfo)** (Optional)
*   **[eac3to (CLI)](https://www.videohelp.com/software/eac3to)**
*   **[MKVtoolNix](https://mkvtoolnix.download/downloads.html)**

### *REMUX Rules*
DTS HD MA 2.0=> FLAC
DTS HD MA 1.0=> FLAC
All PCM audio=> FLAC

Saves space. FLAC is lossless, no quality loss.

Omit the DTS Core track. Keep the AC-3 compatibility track if main audio is TrueHD. Use BDInfo to name tracks correctly.

### *Naming Rules*
Name Year (Edition Info) Resolution Source Remux V/A Codecs-Group Tag

Examples:
French Exit 2020 1080p Bluray REMUX AVC DTS-HD MA 5.1-4K4U
Dantes Inferno An Animated Epic 2010 1080p Blu-ray REMUX AVC TrueHD 5.1-4K4U
Nobody 2021 1080p Blu-ray REMUX AVC TrueHD Atmos 7.1-4K4U

Place edition info (Theatrical Cut, Director's Cut, etc.) as needed.

### *Method #1 (using eac3to)*

1.  Open cmd in the eac3to folder.

    ![Step 1](https://files.catbox.moe/4jgoz9.png)

2.  Type `eac3to` to list drives. Find the BDMV drive (or mount ISO).

    ![Step 2](https://files.catbox.moe/dpzv5s.png)

3.  Identify the main playlist by runtime (longest, has chapters). Here, "1)" is the movie.

    ![Step 3](https://files.catbox.moe/zmtw04.png)

4.  Press Up arrow, add the playlist number: `eac3to K: 1)`.

    ![Step 4](https://files.catbox.moe/hgr2pa.png)

5.  To demux all, press Up, add `-demux`. For specific tracks: `eac3to K: 1) 2: 6: 7: 8: -demux`.

    ![Step 5](https://files.catbox.moe/ea1s7h.png)

   !!! Note: AC3 192kbps 2.0 tracks are often commentary. Verify on DVDCompare or by listening.

6.  Press Enter to demux. Time depends on drive speed.

    ![Step 6](https://files.catbox.moe/fdpp7y.png)

7.  Open MKVToolNix. Import demuxed files. Set track languages and names (from BDInfo).

    ![Step 7](https://files.catbox.moe/b0f1wi.png)

8.  Go to Output tab. Set file name, add chapter file.

    ![Step 8](https://files.catbox.moe/jqjhlk.png)

9.  Final setup should look like this:

    ![Step 9](https://files.catbox.moe/m2hvj6.png)

10. Click Start Multiplexing. Keep the eac3to log for private trackers.

### *Q&A*

**Q1: What does `.*` mean?**
Automatically names files with correct extension. Can specify manually (e.g., `en.flac`).

**Q2: What is `E:\c\`?**
Output path for demuxed files. Defaults to eac3to folder if no path is set.

### *Credits*
**Old owners** - Parnex and an unknown person
**New / Current owner** - [Clara](/claraiscute)

[![Fuck AI](https://files.catbox.moe/os5g6k.png)](https://notbyai.fyi)

*(With %deeppink% <3 %%)*

**If you have any feedback you want to give me, please fill in a form [here](https://formulaer.com/f/aa502b70-f46d-4e81-98a2-bd6b2de24540).**

*************
[Go back to the top](#guide-on-how-to-make-a-blu-ray-remux-from-a-blu-ray-disc-eac3to)