# OmnisToGit
This is an Omnis plugin for handling a git repository.

Required Systems
---

- Windows 10
- Omnis 8.1.4 (or higher)
- git scm 2.25.1 (or higher) -> Download: https://git-scm.com/downloads

Install
---

1. Download or clone the repository.
2. Extracts appData.zip into the root directory of AppData Omnis Studio
3. Open Omnis studio and press "New Lib from JSON..." -> follow the instruction
4. Moves the previously created git.lbs into the startup directory in the AppData Omnis Studio
5. Restart Omnis Studio
6. Set git.lbs.$ispravite=kTrue
7. open menu git->settings

done - congratulation you installed OmnisToGit succesfull

Important Things
---

If the library is not private, everytime you import a library (over the menu pull + import) you close the git library and the function stop.

The CMD window must be closed manually when you push.
