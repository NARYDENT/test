# test

# если хотим добавить с Githuba репозиторий то 

echo "# test" >> README.md __(test = название репозитория)__

git init 

git add README.md

git commit -m "first commit" 

git branch -M main __(переименновываем ветку)__

git remote add origin https://github.com/NARYDENT/test.git __(ссылка на репозиторий)__

git push -u origin main __(отправляем репозиторий)__

# если хотим добавить существующий с (ПК)

git remote add origin https://github.com/NARYDENT/test.git __(ссылка на заранее созданый репозиторий)__

git branch -M main __(переиминовываем ветку)__

git push -u origin main __(отправляем репозиторий)__

## так же можно добавить что-то через браузер

## добавляем ветку на сайт

git push --set-upstream origin test (test = branch)

# добовляем с GitHub

git pull (подгрузить с сайта)

git pull --rebase __(если возник конфликт то эта команда загружает все изменения с сайта и подгружает наши с ПК)__

# после решения конфликта 

git rebase --continue (для фиксации)