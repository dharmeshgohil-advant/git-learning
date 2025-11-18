git learning started
====================Git reset command mainly used when we dont send code to repo and it is in local machine only ==============================================================

git reset --hard <code id > thi head pointer back one commit par jay ane je edit hoy te delete thay che means je file ma write karyu hoy temathi delete thay and log history mathi pan delete thay che
git reset -- soft<code id> ma log history mathi jay che pan je file ma write karyu hoy te ma thi nathi jatu ane te editin karel staged thay jay che tene manually delete karvyu pade che
git reset <code id> je mixed type che reset che jema log history mathi to
jo jay che pan working file maathi nathi jatu ane staged ma pan nathi jatu e to staged pela ni position changed ma jay che tene tya thi remove karva manually remove karva stash unchanged ma thi delete karvyu pade che
=============This are three types of reset ===========================
when we dont push our code from local to remote repository.
=>
git reflog command usedd for if we reset hard and we required that data then we this command show thad code id and current reset head so we can go that previous code id using either using previous used log command data of log or using git reflog command
which provide us again we have to use git reset --hard <codeid>

=>git checkout head~1 ==> refer to the previous commit
when head detached then use git checkout main then head will point to main otherwise it will be detached ,means attached nathi thato jo checkout kariye to attached thay jay simple che

============================Revert command use ====================================
when we push code to remote repo then find mistake then this revert command used
git revert <code(commit) id> then visual code edittor show msg and you have to see revert commit msg if you want to change then change else keep as it is and close that tab so revert will performed and new commit id will generated this is all done in locally and previous commit will not deleted but new commited will generated and all deleted commite will changed in new generated commit so change in file show
means we here not writing history again but it keep history as it is and make change in new commited so we can push in repo and it will show change in repo
so if someone get your code it also get reverted code
private history can be reset using reset but public history ko rever karna hota hai so both have different use cases
