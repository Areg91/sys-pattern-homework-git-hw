# Домашнее задание к занятию "`Git`" - `Арег Огумцян`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

`Задание сделал - ссылка на коммит`
1. [First commit](https://github.com/Areg91/new-repo-1/commit/596b274c37fff6e84543dfacc50957ecc3c1d4e3)`


```
aper@ariken-PC:~/new-repo-1$ git status
Текущая ветка: main
Эта ветка соответствует «origin/main».

нечего коммитить, нет изменений в рабочем каталоге
aper@ariken-PC:~/new-repo-1$ ls
README.md
aper@ariken-PC:~/new-repo-1$ nano README.md 
aper@ariken-PC:~/new-repo-1$ git status
Текущая ветка: main
Эта ветка соответствует «origin/main».

Изменения, которые не в индексе для коммита:
  (используйте «git add <файл>...», чтобы добавить файл в индекс)
  (используйте «git restore <файл>...», чтобы отменить изменения в рабочем каталоге)
	изменено:      README.md

индекс пуст (используйте «git add» и/или «git commit -a»)
aper@ariken-PC:~/new-repo-1$ git diff
diff --git a/README.md b/README.md
index f189ba6..c935e0b 100644
--- a/README.md
+++ b/README.md
@@ -1 +1,3 @@
 # new-repo-1
+
+Add new text
aper@ariken-PC:~/new-repo-1$ git add README.md 
aper@ariken-PC:~/new-repo-1$ git status
Текущая ветка: main
Эта ветка соответствует «origin/main».

Изменения, которые будут включены в коммит:
  (используйте «git restore --staged <файл>...», чтобы убрать из индекса)
	изменено:      README.md

aper@ariken-PC:~/new-repo-1$ git diff
aper@ariken-PC:~/new-repo-1$ git status
Текущая ветка: main
Эта ветка соответствует «origin/main».

Изменения, которые будут включены в коммит:
  (используйте «git restore --staged <файл>...», чтобы убрать из индекса)
	изменено:      README.md

aper@ariken-PC:~/new-repo-1$ git commit -am "First commit"
[main 596b274] First commit
 1 file changed, 2 insertions(+)
aper@ariken-PC:~/new-repo-1$ git statos
git: «statos» не является командой git. Смотрите «git --help».

Самые похожие команды:
	status
aper@ariken-PC:~/new-repo-1$ git status
Текущая ветка: main
Ваша ветка опережает «origin/main» на 1 коммит.
  (используйте «git push», чтобы опубликовать ваши локальные коммиты)

нечего коммитить, нет изменений в рабочем каталоге
aper@ariken-PC:~/new-repo-1$ git push origin master
error: src refspec master ничему не соответствует
error: не удалось отправить некоторые ссылки в «github.com:Areg91/new-repo-1.git»
aper@ariken-PC:~/new-repo-1$ git status
Текущая ветка: main
Ваша ветка опережает «origin/main» на 1 коммит.
  (используйте «git push», чтобы опубликовать ваши локальные коммиты)

нечего коммитить, нет изменений в рабочем каталоге
aper@ariken-PC:~/new-repo-1$ git push
Перечисление объектов: 5, готово.
Подсчет объектов: 100% (5/5), готово.
Запись объектов: 100% (3/3), 277 байтов | 277.00 КиБ/с, готово.
Всего 3 (изменений 0), повторно использовано 0 (изменений 0), повторно использовано пакетов 0
To github.com:Areg91/new-repo-1.git
   1aa84ac..596b274  main -> main
aper@ariken-PC:~/new-repo-1$ git status
Текущая ветка: main
Эта ветка соответствует «origin/main».

нечего коммитить, нет изменений в рабочем каталоге

```

---

### Задание 2

`Задание выполнил в 2 коммита`
1. [update gitignore](https://github.com/Areg91/new-repo-1/commit/ba8b35683bf3956566f21ae2b272019a9993927d)`
2. [update gitignore](https://github.com/Areg91/new-repo-1/commit/c1ac79371b240238c260b9fd463b6ced37bcc91b)

```
aper@ariken-PC:~/new-repo-1$ touch .gitignore
aper@ariken-PC:~/new-repo-1$ git add .gitignore 
aper@ariken-PC:~/new-repo-1$ echo .pyc > .gitignore 
aper@ariken-PC:~/new-repo-1$ echo *.pyc > .gitignore 
aper@ariken-PC:~/new-repo-1$ echo cache* > .gitignore 
aper@ariken-PC:~/new-repo-1$ git commit -am "update gitignore"
[main ba8b356] update gitignore
 1 file changed, 1 insertion(+)
 create mode 100644 .gitignore
```

---

### Задание 3

`Сделал задание, прикрепляю ссылку на сеть git веток`

1. [Network of Areg91](https://github.com/Areg91/new-repo-1/network)

```
aper@ariken-PC:~/new-repo-1$ git branch dev
aper@ariken-PC:~/new-repo-1$ git checkout dev
Переключились на ветку «dev»
aper@ariken-PC:~/new-repo-1$ echo "echo test.sh" > test.sh
aper@ariken-PC:~/new-repo-1$ git add test.sh 
aper@ariken-PC:~/new-repo-1$ git commit -am "add script"
[dev 1d50eb2] add script
 1 file changed, 1 insertion(+)
 create mode 100644 test.sh
aper@ariken-PC:~/new-repo-1$ echo "echo add new output" >> test.sh
aper@ariken-PC:~/new-repo-1$ git commit -am "add some outputs"
[dev b451faf] add some outputs
 1 file changed, 1 insertion(+)
aper@ariken-PC:~/new-repo-1$ echo "echo 1 + 1 = 2" >> test.sh
aper@ariken-PC:~/new-repo-1$ git commit -am "integrate some math to test.sh"
[dev 395b293] integrate some math to test.sh
 1 file changed, 1 insertion(+)
aper@ariken-PC:~/new-repo-1$ git push
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

aper@ariken-PC:~/new-repo-1$ git push origin dev
Перечисление объектов: 10, готово.
Подсчет объектов: 100% (10/10), готово.
При сжатии изменений используется до 8 потоков
Сжатие объектов: 100% (6/6), готово.
Запись объектов: 100% (9/9), 841 байт | 841.00 КиБ/с, готово.
Всего 9 (изменений 2), повторно использовано 0 (изменений 0), повторно использовано пакетов 0
remote: Resolving deltas: 100% (2/2), done.
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/Areg91/new-repo-1/pull/new/dev
remote: 
To github.com:Areg91/new-repo-1.git
 * [new branch]      dev -> dev
aper@ariken-PC:~/new-repo-1$ git checkout main 
Переключились на ветку «main»
Эта ветка соответствует «origin/main».
aper@ariken-PC:~/new-repo-1$ git merge dev
Обновление c1ac793..395b293
Fast-forward
 test.sh | 3 +++
 1 file changed, 3 insertions(+)
 create mode 100644 test.sh
aper@ariken-PC:~/new-repo-1$ git commit -am "merge commit"
Текущая ветка: main
Ваша ветка опережает «origin/main» на 3 коммита.
  (используйте «git push», чтобы опубликовать ваши локальные коммиты)

нечего коммитить, нет изменений в рабочем каталоге
aper@ariken-PC:~/new-repo-1$ git push
Всего 0 (изменений 0), повторно использовано 0 (изменений 0), повторно использовано пакетов 0
To github.com:Areg91/new-repo-1.git
   c1ac793..395b293  main -> main
```

