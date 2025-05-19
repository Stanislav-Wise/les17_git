https://git-scm.com/downloads
brew install git
sudo apt install git


git --version   - Проверка версии

Настройки Гита - делается 1 раз на ПК
git config --global user.name "Stanislav"
git config --global user.email "stanislav@gmail.com"

Необязательные настройки
git config --global color.ui auto  - цветовая схема
git config --global core.editor nano

Проверка настроек
git config --global --list

Инициализация проекта git
git init

Проверка статуса
git status

Добавили файл для отслеживания
git add ./README.md

Сделали коммит
git commit -m "Добавлен README"

