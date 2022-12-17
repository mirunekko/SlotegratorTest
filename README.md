# SlotegratorTest
При разработке скрипта использовалась версия JMeter 5.4.1.

Тест запускается стандартными средствами JMeter. Через GUI-режим нажать на кнопку Start, через cmd выполнить команду jmeter -n -t test.jmx -l log.jtl.

Для успешного запуска файлы Logins.csv и test.jmx должны лежать в одной папке.

Для успешного запуска теста в JMeter должны быть также установлены плагины Custom Thread Groups и Throughput Shaping Timer.
