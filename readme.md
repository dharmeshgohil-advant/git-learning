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
