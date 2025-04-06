## Роли, их полномочия и группы пользователей

|  Роль       |                    Права роли                   |Группы пользователей|  namespace |
|-------------|-------------------------------------------------|--------------------|------------|
|secret-reader|просмотр секретов                                |secret-manager      |secure-space|
|operations   |просмотр подов                                   |manager             |operations  |
|devops-role  |разворачивать новые поды в неймспейсе            |devops-group        |development |
|analytics    |доступ к конфигурационным файлам в неймспейсе    |analytics-group     |analytics   |
|developers   |просмотр логов и состояния подов в тестовой среде|developers          |testing     |

[Скрипт для создания пользователей](users.yaml)

[Скрипт для создания ролей](roles.yaml) 

[Скрипты связей пользователей с ролями](rolesBinding.yaml)

