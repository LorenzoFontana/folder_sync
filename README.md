# FolderSync

Command line tool to **one-way synchronize two folders**. After each synchronization run, the content of the replica folder will match the content of the source folder. The synchronization happens at intervals specified by the user.

## Usage

```bash
foldersync [source folder] [replica folder] [sync interval in seconds] [log file path (optional)]
```

### Parameters

* **source folder**: Path of the folder that the replica folder will match after every synchronization.
* **replica folder**: Path of the folder into which the source folder will be replicated.
* **sync interval in seconds**: Sets the delay in seconds between each synchronization.
* **log file path (optional)**: Optional path to a log file. If not provided, the current folder and a default log file name will be used as the log destination.
