устанваливаем значения для гита git config --global user.name Generallisimo имя и почту git config --global user.email 
инициализируем для готовности работать git init
так же мы добавляем с помощью git add и можем указать только один файл или все сразу git add index.html или git add . в ожидание для работы 
git add *.html так можно добавить все файлы с html
git status позваляет просмотреть файлы ветку и комит к ним также можно узнать какие именно файлы изменены после последней выгрузки 
git rm --cached <файл>.. удалит из статуса ожидания
 git commit -m "Tets" добавляем в локальное хранилеще и добавляем комментарий 