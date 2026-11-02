# Стенд выполненного домашнего задания по занятию "DHCP, PXE"

Для создания стенда лабораторной сети используйте команды:

```
git clone https://github.com/kosogoroff/pxe_lab.git
cd pxe_lab
vagrant up
```


Для создания репозитория использованы команды

```
[admin_insta11@mv334 pxe_lab]$ git init
подсказка: Using 'master' as the name for the initial branch. This default branch name
подсказка: is subject to change. To configure the initial branch name to use in all
подсказка: of your new repositories, which will suppress this warning, call:
подсказка: 
подсказка: 	git config --global init.defaultBranch <name>
подсказка: 
подсказка: Names commonly chosen instead of 'master' are 'main', 'trunk' and
подсказка: 'development'. The just-created branch can be renamed via this command:
подсказка: 
подсказка: 	git branch -m <name>
Инициализирован пустой репозиторий Git в /home/admin_insta11/pxe_lab/.git/
[admin_insta11@mv334 pxe_lab]$ 
[admin_insta11@mv334 pxe_lab]$ git add .
[admin_insta11@mv334 pxe_lab]$ 
[admin_insta11@mv334 pxe_lab]$ git commit -m "first commit"
[master (корневой коммит) 29f5b43] first commit
 12 files changed, 360 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md
 create mode 100644 Vagrantfile
 create mode 100644 ansible/files/default
 create mode 100644 ansible/files/ks-server.conf
 create mode 100644 ansible/files/meta-data
 create mode 100644 ansible/files/pxe.conf
 create mode 100644 ansible/files/user-data
 create mode 100644 ansible/hosts
 create mode 100644 ansible/provision.yml
 create mode 100755 gen_inv.sh
 create mode 100644 inventory.ini
[admin_insta11@mv334 pxe_lab]$ 
[admin_insta11@mv334 pxe_lab]$ git branch -M main
[admin_insta11@mv334 pxe_lab]$ 
[admin_insta11@mv334 pxe_lab]$ git status
Текущая ветка: main
нечего коммитить, нет изменений в рабочем каталоге
[admin_insta11@mv334 pxe_lab]$ 
[admin_insta11@mv334 pxe_lab]$ git remote add origin https://github.com/kosogoroff/pxe_lab.git
[admin_insta11@mv334 pxe_lab]$ 
[admin_insta11@mv334 pxe_lab]$ git push -u origin main

(gnome-ssh-askpass:48614): dbind-WARNING **: 21:06:12.356: Couldn't connect to accessibility bus: Empty address ''

(gnome-ssh-askpass:48634): dbind-WARNING **: 21:06:21.151: Couldn't connect to accessibility bus: Empty address ''
Перечисление объектов: 16, готово.
Подсчет объектов: 100% (16/16), готово.
При сжатии изменений используется до 24 потоков
Сжатие объектов: 100% (13/13), готово.
Запись объектов: 100% (16/16), 5.48 КиБ | 1.10 МиБ/с, готово.
Total 16 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/kosogoroff/pxe_lab.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
[admin_insta11@mv334 pxe_lab]$ 
```

[admin_insta11@mv334 network_lab]$ 
```
