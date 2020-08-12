Git 
------------------------------------------------------------------------------------------------------------------------------------------------------------
Git Merge                                                                                 Git Rebase

Preserves the history Data                                                           Rewrites the history data
when merge is happened , It will merge into one branch to another &                  When rebase is happened, It will merge one branch to another completely , it's checkout branch 
  It's history is still there in checkout branch.                                    is not there, it will overwrite history & creating single path.
When we are getting conflicts , Git merge is easy to resolve the problem,             Conflict problem to difficult to resolve
because it preseves the history                                         

------------------------------------------------------------------------------------------------------------------------------------------------------------

How to resolve git conflict:-

When we are getting merge conflict
we check the status & go through the files , modified that files
git add then commit that code

--------------------------------------------------------------------------------------------------------------------------------------------------------------

Git Reset:

       Git reset is used to reset the changes in staging are in to working directory.
       
       Git reset --Soft
       Git reset --mixed
       git reset --hard


