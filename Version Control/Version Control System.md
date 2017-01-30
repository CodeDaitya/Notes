## Version Control System

Version Control is the process of keeping the history of ones work in manner that one can keep a track of all the changes. The work files are stored in a seperate database usually called repository. Since the files are stored seperately from the local work environment, any progress that one might want to revert can be done using the copy stored in the repository. Also, the sharing of the file becomes very convenient allowing better collaboration with a team one might be working with.

A Version Control System handles all the requirements of Version Control. It has the capability of handling all the changes coming from different sources and maintain the integrity of the data stored in the seperate database.

### Commit/Check-in
When a work file is ready to be added or updated in the main project storage, the user can to a _commit_ or _check-in_ and update
the project with latest version of files. Only after this step can a new update be added to the seperate VCS databse. Any file that hasn't been commited can't be uploaded into the VMS database.

### Staging
The work files, or any changes to the work file, before being commited to the local repository has to be staged. This means that the latest addition/modification has been determined to be the one preferable over the one present already in the repository.

### Reverting Changes
The changes one makes to a local database can be reverted. Any addition can be removed by simple revert procedure that different VCSs provide. The additions are stored in a _structure_ and can be removed from it's latest pointer position. Staged files and changes can be unstaged. Commits can be undone as well. Nothing in a VCS is ever deleted. What the user has deleted in their own work directory and database is still present in the repository history and can be retrieved back from there. VCSs provide a mechanism to accomplish this crucial function.

### Branching
This feature allows creating a seperate branch of the work directory and make any experinmental changes on this new branch without effecting the current version of the work files. It's possible to work on different branches and once the new branch is in a desirable state, it can be merged with the main branch, thereby creating a new version of the project.

### Push
Once it has been determined that the changes made are to preserved and are going to be a part of the project, the changes are pushed to the VCS database to it's respective repsitory on the system. Only the changes that have been committed to in the local workspace can be pushed onto the VCS.
