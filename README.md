# lab2
Ahmed Mohamed Desoky

1)Create a new project on your local machine , then push it your remote repo
    >: git remote add origin git@github.com:kinddark96/lab2.git
    
2)Create two branches (dev & test) then create one file on each branch, and push this changes to the remote repo.
    >: git checkout -b dev ==> git add devfile.html  ==> git commit -m " commit file to dev branch" ==> git push origin dev
    >: git checkout master ==> git checkout -b test ==> git add testfile.html  ==> git commit -m " commit file to test branch" ==> git push origin test
    #used checkout master , becuz if i create branch in dev branch it will get dev file too 
    
3)Merge this changes on Main branch and then push it to your remote main branch.
    >: git merge dev -m "dev branch merge to master"  ==> git push origin master 
    >: git merge test -m "test branch merge to master"  ==> git push origin master
    
4)Tell me how to remove them locally and remotely.
    delete local if it had commit ( git branch -D branch_name ), if it not ( git branch -d branch_name )
    delete remote (git push origin :branch_name)

5)Tell me how to checkout another branch without commit changes
    to hide current commit ( git stash ) then ( git checkout branch_name )

6)Create an annotated tag with tagname (v1.7)
    >: git tag -a v1.7 -m "version 1.7 enhancement"
    

7)Push it to the remote repository
    >: git push origin v1.7 

8)Tell me how to list tags
    >: git tag
    
9)Tell me how to delete tag locally and remotely
    local: ( git tag -d tag_name )
    remote: ( git push origin --delete tag_name )
    
![lab2](https://user-images.githubusercontent.com/114282503/232780715-fece80f8-ca18-4ef8-bbce-00986c83f448.jpg)
