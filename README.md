# operating-systems-projects
Operating Systems coursework: LSM-tree storage engine &amp; FAT journaling extensions


## Project 1 — LSM-tree Storage Engine (C)

### Description
This project implements a **log-structured merge-tree (LSM-tree) based storage engine**
in C, as specified by the course assignment.

The implementation focuses on the core mechanisms of LSM-trees, including in-memory
data buffering, on-disk organization, and background merging, using a multithreaded
design where required by the assignment.

### What is implemented
- In-memory structures for buffering writes
- On-disk data organization following an LSM-tree approach
- Background merging / compaction logic
- Multithreaded execution and synchronization
- Low-level data handling in C

### Contents
- `lsm-tree-storage-engine/src/` : source code
- `lsm-tree-storage-engine/report/` : project report (PDF)

---

## Project 2 — FAT File System Extension (Linux)

### Description
This project involves **source-level analysis and modification of the FAT/VFAT file system**
as part of an Operating Systems assignment.

The work focuses on understanding internal file system structures and implementing
specific extensions and experiments defined in the assignment, rather than developing
a complete journaling file system.

### What is implemented
- Study of FAT/VFAT internal data structures
- Modifications to selected source files
- Experiments related to file system consistency
- Analysis of file system behavior at source-code level

### Contents
- `fat-file-system-extension/src/` : modified source files
- `fat-file-system-extension/report/` : project report (PDF)

---

## Assignment Material

The `assignment/` directory contains the official assignment descriptions
provided as part of the course.

---

## Notes
These projects were developed strictly for academic purposes and should be
evaluated in the context of the corresponding coursework specifications.
