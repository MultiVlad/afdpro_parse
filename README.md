# Мануал
1. Зайти в afdpro
2. Написать: tr on
3. Нажимая F1 дойти до выхода из проги
4. Написать: tr off
5. Написать: pt <начало>,<количество>,<имя файла>
6. Создать Excel файл
7. Запустить скрипт 
# Аргументы
1. trace_file_path (tfp) - путь к исходному файлу
2. excel_file_path (efp) - путь к excel файлу (если файла не существует, то скрипт его создаст)
3. sheet_name (sn) - имя листа
4. tab_top (tt) - отступ сверху
5. tab_left (tl) - отступ слева
# Примеры
1. python main.py trace_file_path=TRACE.TXT excel_file_path=books/trace1.xlsx sheet_name=trace tt=10 tl=0
2. python main.py (Аргументы по умолчанию: trace_file_path='trace.txt', excel_file_path='trace.xlsx', sheet_name='trace', tab_top=0, tab_left=0)