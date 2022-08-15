# sf_diploma_sprint2
## _by Kuzmichev Vladislav_

> Репозиторий с workflow(pipeline GitHub Actions) с деплоем в Docker Hub

https://github.com/VlKuzmichev/django-pg-docker.git

> Генерируемый образ в Docker Hub

vlkuzmichev/my-django-pg-docker

> Деплой проекта с помощью Helm Charts:

```sh
$ git clone https://github.com/VlLuzmichev/sf_diploma_sprint2.git
$ cd sf_diploma_sprint2/charts/
$ helm upgrade --install --namespace default --values db-chart/values.yaml mydb db-chart
$ helm upgrade --install --namespace default --values app-chart/values.yaml myapp app-chart.
```

> Зайти в приложение по адресу ноды
http://ip-addr:30007

> Готово.