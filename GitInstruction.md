# Инструкция по работе с ветками в git

## Создание новой ветки и переход на нее

* **git branch** - посмотреть какие ветки есть
* **git branch branch_name** - создать ветку branch_name
* **git checkout branch_name** - перейти на ветку branch_name

## Сохранение данных из другой ветки

* проверить закоммичен ли файл в ветка_черновик
* **git checkout ветка_чистовик** - перейти в ветка_чистовик
* **git merge ветка_черновик** - перенести данные из ветка_черновик в текущую ветку

## Решение конфликтов

* **git branch ветка_чистовик** - перейти в ветку чистовик
* **git merge ветка_черновик1** - слить в текущую ветку изменения из ветки ветка_черновик1
* **git merge ветка_черновик2** - слить в текущую ветку изменения из ветки ветка_черновик2
* нажать "Resolve in Merge Editor"
* выбрать подходящие изменения
* нажать "Complete Merge"


## Удаление ветки

* **git branch -d branch_name** - удаление ветки branch_name
* **git branch -D branch_name** - удаление ветки branch_name без переноса в чистовик

## Работа с удаленными репозиториями

* **git clone ссылка** - открыть скопированный удаленный репозиторий в своем локальном репозитории
* **git push** - обновление удаленного репозитория в соответствии с изменениями в локальном репозитории
* **git pull** - обновление локального репозитроия в соответствии с изменениями в удаленном репозитории
* **fork** - создание копии чужого удаленного репозитория для внесения изменений
* сделать clone этой ветки, внести изменения, загрузить в свой GitHub
* **pull request** - нажать на сайте для предложения своих изменений в чужой проект