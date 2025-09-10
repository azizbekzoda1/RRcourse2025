
# Assignment 3 – Git Collaboration and Conflict Resolution
**Student:** Azizbek Ganiev (ID: 475150)  
**Professor:** Wojciech Hardy  
**Course:** Reproducible Research 2025  

This assignment demonstrates collaborative Git workflows, including:  
- pushing and pulling to a shared repository,  
- resolving conflicts,  
- maintaining a clear commit history.  

---

```bash
$ cd ~/RR_3/Dev1
$ git merge --abort
fatal: There is no merge to abort (MERGE_HEAD missing).

$ git push
Enumerating objects: 7, done.
...
(master -> master)

$ git commit -m "Resolved merge conflict in text3.txt"
[master 46b113d] Resolved merge conflict in text3.txt

$ git push
Everything up-to-date
```

---

### Reflection
This workflow illustrates how two developers (simulated) can:  
- edit files in parallel,  
- face merge conflicts,  
- and resolve them systematically using Git.  

The commit log shows contributions, merges, and final resolution.
