# git-comands
To never lost some util command!

- Change repository origin -> `git remote set-url origin new.git.url/here`
- Undo last commit -> `git reset HEAD~1` 
- Change default editor -> `config --global core.editor 'code --wait'`
- See git configs -> `git config --global -e`
- Some util alias: 

> c = checkout
> 
> s = status -s
> 
> comm = add --all && git commit -m
> 
> l = log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'
`

# postgres-sql

- To get all columns of a table
``` sql
  SELECT *
    FROM information_schema.columns
   WHERE table_schema = 'public'
     AND table_name   = 'AgriculturalProjects'
  ;
````
