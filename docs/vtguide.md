# *VirusTotal Scan Guide*

*This guide is here to help you make informed decisions, but the final call on file safety is yours. Use your best judgment and be cautious. If you're unsure, consider seeking professional help from a security expert.*

---

### *Check the Scan Date*
- Ensure that the scan date is recent. If not, click on the 'Reanalyze' button and scan to detect new threats or remove old false positives.

(Go to the VirusTotal site → Upload your file or search the file hash/url → Look at the top-right side of the screen.)

![Scan Date](https://files.catbox.moe/dpqr9d.png)

---

### *Check the Details Tab*
- **Creation Time, First Seen In The Wild, and First Submission:**
  - Creation Time may be unreliable if obviously fake (e.g., set in the future).
  - Compare First Seen In The Wild and First Submission dates with the product release date to identify recycled malware.

(Go to the VirusTotal site → Upload your file or search the file hash/url → Click on the 'Details' tab.)

![Details Tab](https://files.catbox.moe/f3ymb6.png)

---

### *Check the Submitted Names*
- Ignore names resembling hashes or generic terms like 'sample1.exe'.
- Multiple names for unrelated products suggest potential malware.

(Go to the VirusTotal site → Upload your file or search the file hash/url → Click on the 'Details' tab → Scroll down until you see the 'Names' section.)

![Submitted Names](https://files.catbox.moe/rutmg3.png)

---

### *If It's a Pirated Software*
- For pirated software, signatures won't be helpful as cracks or patched files won't be valid, but typically if there was an invalid signature it would be suspicious.

(Go to the VirusTotal site → Upload your file or search the file hash/url → Click on the 'Details' tab → Scroll down until you see the 'Signature info' section.)

![Signature](https://files.catbox.moe/zogmm6.png)

---

### *Check the Relations Tab*
- **Execution Parents/Resource Parents:**
  - Focus on installers or archives that contained, dropped, or downloaded the file. Ignore if scanning an installer that wasn't extracted from another file.

(Go to the VirusTotal site → Upload your file or search the file hash/url → Click on the 'Relations' tab → Scroll down until you see the 'Execution Parents' section.)

![Execution Parents](https://files.catbox.moe/rvkbm2.png)

- **Dropped Files/Bundled Files:**
  - Examine files extracted from the scanned file, particularly useful when scanning archive files.

(Go to the VirusTotal site → Upload your file or search the file hash/url → Click on the 'Relations' tab → Scroll down until you see the 'Bundled Files (Number of bundled files)' section → Scroll down a bit more until you see the 'Dropped Files (Number of dropped files)' section.)

![Bundled Files](https://files.catbox.moe/txzcb3.png)

- **Graph Summary**
  - Take a quick glance at everything once more.

(Go to the VirusTotal site → Upload your file or search the file hash/url → Click on the 'Relations' tab → Scroll down until you see the 'Graph Summary' section.)

![Graph](https://files.catbox.moe/xbe4a5.png)

---

### *Check the Contacted IP Addresses/URLs*
- Beware of overwhelming malicious results, but also consider false positives. (e.g. drive.google.com is currently flagged as a phishing site by one of the AVs)
- Suspicion arises if a file meant to be benign (e.g., a keygen or patcher) makes unexpected requests.

(Go to the VirusTotal site → Upload your file or search the file hash/url → Click on the 'Relations' tab → Scroll down until you see the 'Contacted IP addresses (Number of contacted IPs)' section.)

![Contact IPs](https://files.catbox.moe/4f1w84.png)

---

### *Check the Behavior Tab*
- Opening and reading files, writing/deleting temp files, and expected installer activities are generally benign.
- Suspicion arises if the file exhibits unusual behavior or accesses unnecessary areas.

(Go to the VirusTotal site → Upload your file or search the file hash/url → Click on the 'Behavior' tab → Scroll down and notice the info presented to you.)

![behavior1](https://files.catbox.moe/zhm95i.png)

---

### *Check the Detections Tab*
- Generic/gen/susgen detections (like W32.Trojan.Gen) or AI/ML labels may indicate potential malware that doesn't match known signatures.
- Common detections for cracks, patches, etc., include riskware, hacktool, and not-a-virus (last on is specific to Kaspersky).

(Go to the VirusTotal site → Upload your file or search the file hash/url → Click on the 'Detection' tab → Scroll down and notice the info presented to you.)

![Detection](https://files.catbox.moe/la1l9y.png)

---

### *Check the Highlighted Actions*
- Although rare, alarming statements like 'all your files are belong to us', take immediate action.

(Go to the VirusTotal site → Upload your file or search the file hash/url → Click on the 'Behavior' tab → Scroll down until you see the 'Highlighted actions' tab.)

![Highlight](https://files.catbox.moe/tba93u.png)

---

### *Check the File Age*
- New files may lack accurate detections, while older files should have more reliable results.
- A file's age can provide context; newer files warrant closer scrutiny.

(Go to the VirusTotal site → Upload your file or search the file hash/url → Click on the 'Details' tab → Scroll down until you see the 'History' tab.)

![File Age](https://files.catbox.moe/qvqo41.png)

---

### *Check If It Has Multiple Similar Detections*
- If numerous specific detections align, it indicates higher risk.

(Go to the VirusTotal site → Upload your file or search the file hash/url → Look at the 'Popular threat label' section → Look at the 'Threat categories' section → Look at the 'Family labels' section.)

![Similar](https://files.catbox.moe/4vbbfr.png)

---

### *Consider the Community Tab*
- While often cluttered, occasionally valuable insights or warnings are found.

![Voting Details](https://files.catbox.moe/dv15fh.png)

![Comments](https://files.catbox.moe/61bwoy.png)

(Go to the VirusTotal site → Upload your file or search the file hash/url → Click on the 'Details' tab → Scroll down until you see the 'Community' tab.)

---

### *Conclusion*
- Even with thorough analysis, some uncertainty may remain. Exercise caution with older files with generic detections.
- If unsure, refrain from using the file.

---

### *Credits*
**Old owner** - [ilike2burn](https://www.reddit.com/user/ilike2burn)
**New / Current owner** - [Clara](https://rentry.org/claraiscute)

[![Fuck AI](https://files.catbox.moe/os5g6k.png)](https://notbyai.fyi)

*(With <3)*

**If you have any feedback you want to give me, please fill in a form [here](https://formulaer.com/f/aa502b70-f46d-4e81-98a2-bd6b2de24540).**

**************
[Go back to the top](#virustotal-scan-guide)
