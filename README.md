# Домашнее задание к занятию «2.1. Системы контроля версий.»

## Репозиторий devops-netology

### Описание /terraform/.gitignore

Будут игнориться:

 - все папки .terraform на всех уровнях вложенности;
 - все файлы .tfstate, а так же все .tfstate."любое добавочное 
   расширение" (файлы состояния)
 - файл crash.log (логи ошибок)
 - все файлы с расширением .tfvars (файлы, которые могут содержать
   пароли, закрытые ключи и другие данные)
 - файлы переопределения override.tf, override.tf.json, и оканчивающиеся 
   на _override.tf, _override.tf.json
 - файлы конфигурации CLI .terraformrc, terraform.rc

Evgeniy Kudryavtsev