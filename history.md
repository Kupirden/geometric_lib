●	git clone https://github.com/smartiqaorg/geometric_lib.git -клонируем репозиторий 
●	cd geometric_lib/ - переходим в папку только что клонированного репозитория
●	
●	git checkout feature – создаем и переходим в локальную ветку feature
●	
●	git checkout develop – создаем и переходим ветку develop
●	git checkout release - создаем и переходим ветку release
●	git log --all --pretty=oneline –graph- делаем граф структуры репозитория 
●	git checkout main – переходим в ветку main
●	git merge develop --no-ff- вливаем ветку develop в ветку main явным образом с созданием merg коммита
●	git log --all --pretty=oneline –graph -стоим граф репозитория 
●	git reset --hard HEAD^-удаляем последний коммит
●	git log --all --pretty=oneline –graph-строим граф
●	git merge develop –ff -вливаем ветку develop в  ветку main в fast-forge режиме 
●	git log --all --pretty=oneline –graph-строим граф
●	git config merge.conflictstyle diff3 –вывод базу слияния  при конфликте 
●	git config --global merge.tool meld-установка meld в качестве инструмента
●	git checkout release -переходим в ветку release
●	git rebase -i main-интерактивный ребейз ветки release  и ветки main
●	git mergetool-рещаем конфликт
●	git rebase –continue -продолжаем ребейз
●	git mergetool-решаем новый конфликт
●	git log --all --pretty=oneline –graph-строим граф
●	git checkout main -преходим в ветку main
●	git merge release –ff – выполняем вливаем ветку release в  ветку main в fast-forge режиме
●	git log --pretty=oneline –graph-строим граф
