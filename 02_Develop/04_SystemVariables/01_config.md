###Системные настройки

array config

Содержит информацию о системных настройках в виде ассоциативного массива. Использовать напрямую его не рекомендуется и для получения информации существует метод API - getConfig

####Пример
    <?php  echo $modx->config['modx_charset'];  ?>