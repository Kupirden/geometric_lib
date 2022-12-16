●	git clone https://github.com/smartiqaorg/geometric_lib.git 
●	cd geometric_lib/
●	
●	git checkout feature 
●	
●	git checkout develop
●	git checkout release 
●	git log --all --pretty=oneline –graph
●	git checkout main – переходим в ветку main
●	git merge develop --no-ff
●	git log --all --pretty=oneline –graph 
●	git reset --hard HEAD^
●	git log --all --pretty=oneline –graph
●	git merge develop –ff 
●	git log --all --pretty=oneline –graph
●	git config merge.conflictstyle diff3 
●	git config --global merge.tool meld
●	git checkout release 
●	git rebase -i main
●	git mergetool
●	git rebase –continue 
●	git mergetool
●	git log --all --pretty=oneline –graph
●	git checkout main 
●	git merge release –ff 
●	git log --pretty=oneline –graph
