---
layout: page
title: Efficient Querying of File System Changes
description: Prototype software to efficiently process file modifications.
img: assets/img/hpeCTY.png
importance: 2
category:
related_publications: False
---

This repository contains my final implementation of the project work completed at HPE CTY. The project is a program that captures and records all file modifications within a specified directory into a Cassandra database, enabling efficient querying of file changes. It begins by constructing an initial.json file containing metadata for all files in the target directory. The program then monitors the directory at set intervals (defaulting to every 1 minute), recording changes in HH_MM_changes.json files. These JSON files are loaded into Cassandra, which powers a simple user interface for searching files and retrieving their latest metadata and modification records.

Instructions to Run:

1. Modify the path in changes.py to the directory you wish to monitor.
2. Specify the path where the JSON files should be stored.
3. Run changes.py to start recording file modifications.
4. After modifying the default path in cassandra_queries.py to the location of the JSON files, run it.
5. Execute queries.py and input the desired filename to view its metadata and modification history.

View the project on GitHub [here.](https://github.com/sai-samarth/HPE_CTY_2023)