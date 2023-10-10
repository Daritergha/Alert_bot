![image](https://github.com/Daritergha/Alert_bot/assets/101475231/22d3c89c-399a-4c7c-8a0e-acc92daa745e)# Alert_bot
Alert_bot for Prometheus-Grafana-nodeexporter-alertmanager stack

Интегрируемый телеграм-бот для сбора метрик Grafana с подключаемой системы. Вывод данных экспортёра осуществляется через Prometheus.
Применялся в проекте Avalanche-Bonch для сбора данных с рабочего сервера, на котором располагались парсеры, вычислительные блоки, 3 базы данных и ИИ нода-обработчик поступаемых метрик.
P.S. Код брался с встроенной в сервер ВМ Ubuntu 18.04 LTS

Для изменения вида сообщений необходимо менять параметры внутри блока alert в alert.rules:
![]([https://github.com/[username]/[reponame]/blob/[branch]/image.jpg](https://github.com/Daritergha/Alert_bot/blob/main/img1.png)https://github.com/Daritergha/Alert_bot/blob/main/img1.png?raw=true)

Параметры отображения больше зависят от настроек непосредственно задействованных сервисов, телеграм-бот же всего лишь отправляет данные в указанном виде.
