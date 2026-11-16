Файл .gitignore в папке terraform

Благодаря добавленному файлу `.gitignore` в папке `terraform`, Git будет игнорировать следующие типы файлов:
- Файлы состояния Terraform (`*.tfstate`, `*.tfstate.backup`);
- Файлы crash-логов (`crash.log`, `crash.*.log`);
- Переопределения переменных (`*.tfvars`);
- Каталог (`.terraform/`);
- Файлы планов (`*.tfplan`);
- Файлы с расширением `.override` и `.auto.tfvars`.