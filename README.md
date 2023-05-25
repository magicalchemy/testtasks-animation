# Тестовое задание: анимация

Создайте React-проект демонстрирующий анимацию как в ![видео](./animation.mp4).
В `README.md` опишите инструкцию по сборке *(обязательно)*
и инструкцию по запуску dev-сервера *(опционально)*.
Отправтье ссылку на Git-репозиторий с реализацией.

Оптимизируейте изображения.
При разработки старайтесь обойтись минимальными средствами:
избегайте тяжёлых и необоснованных зависимостей, избегайте использование canvas.
Соблюдайте баланс между лёгкостью и красотой:
сайт должен быть доступен пользователям с маломощными девайсами и плохим коннектом.

Соблюдение такого баланса -- творческая задача.
Реализуйте её на свой вкус, не пытайтесь угадать наш, но будье готовы обосновать свой выбор.

Нет задачи повторить анимацию как в видео.
Главное, чтобы анимация на сайте была похожа на неё или, даже, отдалённо похожа.
Рассмотрите вариант реализации эффектов при помощи спрайтов и их изменения средствами CSS.
Или же используйте canvas, если считаете это лучшим решением.

Доступны в высоком разрешении необрезанные спрайты эффекта магической стрелы:
используйте, оптимизируйте, обрезайте и видоизменяйте на своё усмотрение.


## Механика игры

Назначьте на своё усмотрение трём картам из макета роль "лечащих" карт,
остальным -- роль карт "урона".
Очки восстановления и урона назначьте также самостоятельно.

Восстанавливаться (расти) должа башня игрока,
а урон наноситься башни противника (должна уменьшаться).

Бар и значение `YOR TURN`/`OPPONENTS TURN` должны изменяться соответсвенно.

При нажатии на крестик в правом верхнем углу состояние игры должно сбрасываться.

Остальные элементы интерфейса нефункциональны: просто отображаются.
Противник нефункционален и не делает никаких ходов.


## Дополнительная задача

Определяйте положение устройства, и сообщайте пользователю
*(например, белой надписью на чётном фоне по центру экрана)*,
что игра доступна только в landscape.


## Ассеты

Шрифты находятся в директории [assets](./assets).

Макет -- в [Figma](https://www.figma.com/file/Ga0JPD3c5jXJvUmcxFKKuv/testtask-animation).

Неоптимизированные спрайты для эффекта магической стрелы
-- в директории [magic arrow](./assets/magic-arrow).

К сожалению, ассеты эффета вспышки карты пока недоступны -- найдите что-нибудь похожее в Интернете :)
