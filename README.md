# Git-Assignment-5

Git Commands :

1.) Create a gitflow workflow architecture on git

	mkdir git

	cd git

	git init

	touch code.txt

	git add code.txt

	git commit -m "Committing code.txt."

2.) Create all the required branches :

	git branch develop

	git branch f1

	git branch f2

3.) Starting from the feature branch, push the branch to the master, following the architecture

	git checkout f1

	touch f1.txt

	git add f1.txt

	git commit -m "Committing feature 1 file."

	git checkout f2

	touch f2.txt

	git add f2.txt

	git commit -m "Committing feature 2 file."

	git checkout develop

	git merge f1

	git merge f2

	git checkout master

	git merge develop

4.) Push a urgent.txt on master using hotfix

	git checkout -b hotfix

	touch urgent.txt

	git add urgent.txt

	git commit -m "Committing urgent.txt."

	git checkout master

	git merge hotfix

	git branch -D hotfix	
