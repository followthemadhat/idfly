<h4>Приложение управления входящими заявками (AngularJS)</h4>

Структура создана генетатором Gulp-Angular, для сборки использовался Gulp.

Удалось сделать каркас проекта, а также внедрить базовую функциональность.

Главная страница является одновременно страницей добавления заявки. Количество проектов для удобства ограничено 4-мя.

Кнопка "Оставить заявку" в хедере не работает! По замыслу, она должна вызывать модальное окно добавления заявки. В текущей структуре дублируется и оставлена для наглядности.

При нажатии на кнопку "Отправить заявку" форма сабмитится и сбрасывается. Другого подтверждения отправки формы нет! После отправки, заявка появляется в общей таблице.

Второй экран - список всех заявок. Сортировка (по убыванию/возрастанию) реализована по клику на заголовок столбца.

Выпадающий список снизу - выбор проекта для фильтрации. При выборе проекта (1-4) показываются только заявки этого проекта.

TODO: выделение заявок цветом в таблице в зависимости от важности (исходя из использованных цветов)
