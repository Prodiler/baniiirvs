# baniiirvs
### Rvs project

добавлены все серверы соответсвуюшие процессам (см рисунок)
каждый сервер экспресс настроен так, что все модули каждый сервер берет из корня проекта.
порты:

* экипаж самолета: 3000               npm run plane
* диспетчер АДП:3001                  npm run dadp
* дис-р руления(?): 3002              npm run drulen
* дис-р старта(? что он делает): 3003 npm run dstart
* д-р АДЦ(?): 3004                    npm run dadc
* д-р РДЦ(?): 3005                    npm run drdc

Они действительно все нужны?

#### TODO: Настроить корс(установлен см package.json)
#### TODO: Протетстить как они будут сообщаться хоть как нибудь
#### TODO: Оформить интрфейс каждому(самый простой) чтобы были видны сообщения
#### TODO: Собстна логика

## Сразу договоримся:

* Все сообщения ввиде json {Type: "", data""}
* Делай документацию блэт сразу!(типо что сделал и как использовать)(как у фирсова :/ )
* Мне кажется, что это сложный проект и поэтому надо потратить на это время
* Я не знаю как разрешать конфликты, поэтому по-аккуратней с комитами

Надеюсь на активное сотруднечество
:-)