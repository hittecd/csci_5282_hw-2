CSCI 5282 - Fall 2016

Homework 2

Chris Hitte & Sorayya Niazi

git command log:

	git init
	git add *
	git commit -m "commit 0"
	git checkout -b bug-fix
	git checkout master
	git add *
	git commit -m "commit 1"
	git add *
	git commit -m "commit 2"
	git checkout bug-fix
	git add *
	git commit -m "commit 3"
	git add *
	git commit -m "commit 4"
	git checkout -b bug-fix-experimental
	git checkout bug-fix
	git merge master
	git add *
	git commit -m "commit 5"
	git add *
	git commit
	git checkout bug-fix-experimental
	git add *
	git commit -m "commit 7"
	git add *
	git commit -m "commit 8"
	git add *
	git commit -m "commit 9"
	git checkout master
	git add *
	git commit -m "commit 10"
	git checkout bug-fix
	git merge bug-fix-experimental
	git add *
	git commit -m "commit 11"
	git add *
	git commit -m "commit 12"
	git checkout master
	git merge bug-fix
	git add *
	git commit -m "commit 13"
	git remote add origin https://github.com/hittecd/csci_5282_hw-2.git
	git checkout bug-fix
	git push -u origin bug-fix
	git checkout bug-fix-experimental
	git push -u origin bug-fix-experimental
	git checkout master
	git add hw_2_graph.png README.md
	git commit -m "commit 14"
