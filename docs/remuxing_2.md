# *Guide on How to Make a Blu-ray REMUX from a Blu-ray Disc (MKVtoolNix #2)*

### *Programs needed*
*   **[MKVtoolNix](https://mkvtoolnix.download/downloads.html)**

### *Method #2 (using MKVtoolNix GUI)*

1.  Open MKVtoolNix. Select the `index.bdmv` file from the BDMV folder of your Blu-ray.

    ![Select index.bdmv](https://files.catbox.moe/qoxurm.png)

2.  A list of playlists will appear. Choose the one with the correct runtime and most chapters (use a site like blu-ray.com to check the official runtime). Ignore playlists with bugged, extremely long runtimes.

    ![Choose playlist](https://files.catbox.moe/adl0ya.png)

3.  Click "Add". The tracks will be added. Languages are often detected automatically.

![Click "Add"](https://files.catbox.moe/33451t.png)

4.  Edit the tracks as described in the [eac3to method](remuxing_1#method-1-using-eac3to) (follow from step 7 to step 10): set languages, rename tracks based on BDInfo, convert audio to FLAC where required, and remove unnecessary tracks (like DTS Core).

5.  Chapters are usually included automatically but sometimes are not. If chapters are missing, you must extract them using eac3to and then add the chapter file in the "Chapter editor" or "Output" tab before multiplexing.

6.  Set the output file name and start multiplexing.

### *Credits*
**Old owners** - Unknown (not a username)
**New / Current owner** - [Clara](/claraiscute)

[![Fuck AI](https://files.catbox.moe/os5g6k.png)](https://notbyai.fyi)

*(With %deeppink% <3 %%)*

**If you have any feedback you want to give me, please fill in a form [here](https://formulaer.com/f/aa502b70-f46d-4e81-98a2-bd6b2de24540).**

*************
[Go back to the top](#guide-on-how-to-make-a-blu-ray-remux-from-a-blu-ray-disc-mkvtoolnix-2)