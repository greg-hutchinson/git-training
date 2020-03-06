# Common Git Commands

---
## Clone
@img[south-east span-40](assets/img/clone.png)
@snap[west text-08 span-50]
### Clone the **remote repository** and create the **local repository**
@snapend

---
## Push
@img[south-east span-40](assets/img/push.png)
@snap[west text-08 span-50]
### Push all deltas from the **local repository** to the **remote repository**
@snapend

---
## Pull
@img[south-east span-40](assets/img/pull.png)
@snap[west text-08 span-50]
### Pull all deltas from the **remote repository** to the **local repository**
@snapend

---
## Commit
@img[south-east span-32](assets/img/commit.png)
@snap[west text-08 span-50]
### Commit the changes in the **working copy** to the **local repository**
@snapend

---
## Check-out
@img[south-east span-32](assets/img/check-out.png)
@snap[west text-08 span-50]
### Replicated the **working copy** with an exact snapshot of this point in time from the **local repository**
@snapend

---
## Github Graphs
@img[south-east span-30](assets/img/git-nodes.png)
@snap[west text-07 span-65]
- A node is created by a **commit** and represents a snapshot of the entire project at a given point in time
- You can **check-out** any node and your **working copy** is updated
- Nodes always have a 1 or 2 parents. Nodes with 2 parents are merge nodes.
    - [More on merging](https://www.atlassian.com/git/tutorials/using-branches/git-merge)
@snapend
