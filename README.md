# git-comands
To never lost some util command!

- Change repository origin -> `git remote set-url origin new.git.url/here`
- Undo last commit -> `git reset HEAD~1` 

# postgres-sql

- To get all columns of a table
``` sql
  SELECT *
    FROM information_schema.columns
   WHERE table_schema = 'public'
     AND table_name   = 'AgriculturalProjects'
  ;
````
