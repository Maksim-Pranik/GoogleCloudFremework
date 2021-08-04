# Параметризованная сборка с использованием Jenkins
Сборка выполняется командами:
* npm install
* npx wdio run ./wdio.conf.js --environment=%Environment% --browser=%Browser% --suite %Suite%
