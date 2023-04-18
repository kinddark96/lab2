# lab2
Ahmed Mohamed Desoky <br />

1)Create a new project on your local machine , then push it your remote repo <br />
    >: git remote add origin git@github.com:kinddark96/lab2.git <br />
    
2)Create two branches (dev & test) then create one file on each branch, and push this changes to the remote repo. <br />
    >: git checkout -b dev ==> git add devfile.html  ==> git commit -m " commit file to dev branch" ==> git push origin dev <br />
    >: git checkout master ==> git checkout -b test ==> git add testfile.html  ==> git commit -m " commit file to test branch" ==> git push origin test <br />
    #used checkout master , becuz if i create branch in dev branch it will get dev file too  <br />
    
3)Merge this changes on Main branch and then push it to your remote main branch. <br />
    >: git merge dev -m "dev branch merge to master"  ==> git push origin master  <br />
    >: git merge test -m "test branch merge to master"  ==> git push origin master <br />
    
4)Tell me how to remove them locally and remotely. <br />
    delete local if it had commit ( git branch -D branch_name ), if it not ( git branch -d branch_name ) <br />
    delete remote (git push origin :branch_name) <br />

5)Tell me how to checkout another branch without commit changes <br />
    to hide current commit ( git stash ) then ( git checkout branch_name ) <br />

6)Create an annotated tag with tagname (v1.7) <br />
    >: git tag -a v1.7 -m "version 1.7 enhancement" <br />
    

7)Push it to the remote repository <br />
    >: git push origin v1.7 

8)Tell me how to list tags <br />
    >: git tag <br />
    
9)Tell me how to delete tag locally and remotely <br />
    local: ( git tag -d tag_name ) <br />
    remote: ( git push origin --delete tag_name ) <br />
    
![lab2](https://user-images.githubusercontent.com/114282503/232780715-fece80f8-ca18-4ef8-bbce-00986c83f448.jpg)
