Додаток керує списком контактів за допомогою наступних команд:

# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)
node index.js --action="list"

[link](https://monosnap.com/file/gQfuCSK9UFtntbnahyyASzCwV6WVWW)

# Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.
node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6

[link](https://monosnap.com/file/uOWylCXktjMDx4MpgPusi0WLKBszCU)

# Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту
node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22

[link](https://monosnap.com/file/R4Ti8NEOfM1QGCGszSPPdYbPDEckKp)

# Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.
node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH

[link](https://monosnap.com/file/jEmV3vLMCqvdjsOhYa6AAHfyl9Gvbb)
