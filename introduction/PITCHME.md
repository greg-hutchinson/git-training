## Why Distributed VCS
- Central shared spot for documents
- Can work disconnected from network and then sync when connected with access to entire version history
- Versions are kept of the entire directory structures (not just individual files)
- Backups are implicit because of cloning

---
## Git Vs. Sharepoint
- Both are centralized locations for source documents
- Sharepoint only version controls individual files
- Sharing documents with people in the organization that do not have git already is tedious. Everyone has access to Sharepoint

---
## Git Vs. Sharepoint
- Git works locally and is really fast. Sharepoint is a little sluggish
- Git (in theory) takes an extra step or two to have the most current snapshot (pull, checkout)
- Git is more technical, steeper learning curve but because of this has a lot more features

---
## Centralized VCS - CVCS
@img[east span-60](assets/img/cvcs.png)
@snap[west text-06 span-36]
- Always had to be connected to the network
- Committing changes also released the changes (Can't commit in a partial state)
- Checking-out your local copy possibly destroyed work in progress
@snapend


---
## DVCS  - Summary
@img[east span-55](assets/img/dvcs.png)
@snap[west text-06 span-36]
- Don't have to be connected to the network
- Committing changes only affect the local repository. Commit freely and at any time
- No outstanding changes allowed before merging.
- Work can be sync to a central repo or shared among a small group since a remote repo is a remote rep
@snapend

---
## Terminology
- Remote Repository - The git repository that is hosted in the cloud or on another computer
- Local Repository - The git repository that is hosted on your local computer
- Working Copy - The current checked-out version to your local computer.
