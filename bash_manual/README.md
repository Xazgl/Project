# Bash мануал 

### Создание папки: 
`$ mk namedir`

### перейти в папку:

`$ cd namedir`

### Полный путь (абсолютный) путь

`$ pwd`

### Создать файл:

`$ touch test.tss`


### Посмотреть  Файлы в папке:

`$ ls`

### Посмотреть ВСЕ (и скрытые)   Файлы в папке:

`$ ls -la`



### Переименовать файл:


`$ mv test.js scrpt.js`

### Переместить файл выше:

`$ mv scrpt.js ../somedirect/main.js`


### Удалить файл:

```shell
$ touch style.css
$ rm style.css
```

### Перейти на уровень выше:

`$ cd ..`


### Удалить папку:

`$ rm -rf namedir`


## Работа с ветвями:


### Создание новой ветви:
`$ git branch new-branch`

### Переключится на новую ветвь:
`$ git checkout new-branch`

### Вносим изменения в файлы и делаем  commit:
`$ git commit -am "Commits name"`

### Переходим обратно в главную ветвь разработки:
`$ git checkout master`

### Вносим измененения в файлы и делаем commit (необязательно)
`$ git commit -am "Commits name"`


### Делаем слияние ветвей (необходимо убедится что мы в ветке master `$ git status`)

`$ git merge new-branch`

### В случе конфликтов редактируем файлы и делаем индексацию файлов и commit:
`$ git commit -am "Commits name"`

### Просмотре всех веток:
`$ git branch --list`