# Задание 4

Роли:

| Роль                 | Права роли                                                                   | Группы пользователей        |
|----------------------|------------------------------------------------------------------------------|-----------------------------|
| cluster-viewer       | Просмотр всех ресурсов в namespace: pods, deployments, services, events      | Разработчики, аналитики     |
| cluster-configurator | Управление конфигурацией кластера: configmaps, ingress, network policies     | DevOps, SRE                 |
| admin                | Доступ на чтение и изменение secrets, configmaps                             | Специалисты по безопасности |
| namespace-owner      | Полные права в рамках определённого namespace                                | Владельцы сервисов          |


[Создание пользователей](create-users.sh)
[Создание ролей](create-roles.sh)
[Создание связей](create-binding.sh)