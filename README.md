Курсовой проект. Тема проекта: Создание программы с использованием СУБД PostgreSQL.

Для работы с проектом необходимо: Создать файл с названием database.ini, который заполняется следующим образом: [postgresql] host=YourHost user=YourUser password=YourPassword port=YourPort

Работа программы: Программа взаимодействует с пользователем, предварительно получая данные с сайта hh.ru по самым востребованным работодателям(get_hh_json). Далее создаётся БД(create_db), данные сохраняются в БД(save_data_to_db). Класс DBManager в свою очередь обрабатывает данные из БД для вывода пользователю.