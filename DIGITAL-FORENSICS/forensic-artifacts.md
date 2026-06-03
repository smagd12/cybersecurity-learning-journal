# Forensic Artifacts

This file contains notes on common digital forensic artifacts and how they can be used during investigations.

---

## What are Forensic Artifacts?

Forensic artifacts are pieces of evidence left behind by user activity, applications, and operating systems.

These artifacts help investigators determine what occurred on a system.

---

## Common Forensic Artifacts

### Browser History

Browser history may reveal:

- Websites visited
- Downloaded files
- Timestamps
- Search activity

---

### Recent Files

Windows maintains records of recently opened files.

This can help determine whether a user accessed a specific document.

---

### Recycle Bin

Deleted files may still contain useful metadata including:

- Original file name
- Original location
- Deletion time

---

### Prefetch Files

Windows Prefetch can indicate:

- Applications that have executed
- Execution frequency
- Last execution time

---

### NTFS Master File Table (MFT)

The MFT stores metadata about files including:

- Creation timestamps
- Modification timestamps
- File deletion information

---

## Why Artifacts Matter

Artifacts help investigators:

- Reconstruct events
- Verify user activity
- Identify malicious behaviour
- Establish timelines

---

## What I Learned

- Evidence often remains even after files are deleted.
- Multiple artifacts can be combined to build an investigation timeline.
- Metadata can be just as valuable as the file itself.