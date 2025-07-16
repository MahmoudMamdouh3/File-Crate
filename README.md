# File-Crate
## What is FileCrate?
FileCrate is a desktop tool I’m building in Python to help organize messy folders in a smart, modular way. It's designed for Linux systems and runs through a Jupyter Notebook (for now) inside VS Code. The idea is to handle large sets of files—images, videos, documents, you name it—without wasting time doing it manually.

At its core, FileCrate detects and moves duplicate files, groups everything by date, and uses an advanced YOLO model to filter images that contain people. It's not trying to be pretty or overly automated—just effective, fast, and built with full control in mind. I'm keeping the code modular (DuplicateFinder.py, groupbydate.py, etc.) so it’s clean and easy to scale.

This is a work-in-progress, but the goal is to turn it into a solid file management utility that actually saves time, cleans up disk space, and makes sense of huge, unstructured directories.
