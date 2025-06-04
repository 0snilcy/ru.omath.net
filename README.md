<p align="center" style="text-align: center;">
    <img src="https://raw.githubusercontent.com/open-math/shared/main/assets/omath.svg" width="100px" />
</p>

<h1 align="center">Открытая Математика</h1>

<p align="center">
    <strong>Современный учебник по математике — понятный, интересный, открытый.</strong><br>
    Репозиторий материалов учебника на русском языке.
</p>

<p align="center">
🌐 <a href="https://omath.ru">Сайт</a>
✍🏻 <a href="https://github.com/open-math/ru.omath.net/blob/main/pages/how-to-improve.md">Внести вклад</a>
🎮 <a href="https://stackblitz.com/github/open-math/ru.omath.net">Песочница</a>
</p>

<p align="center">▨</p>

## Разработка локально

Для внесения большого количества правок или даже разработки новых материалов рекомендуется установить локальную копию учебника на компьютер.
Чтобы это сделать, выполните следующие шаги:

1. Установите [Node.js](https://nodejs.org/en/download)
2. Установите [Bun](https://bun.sh/)
3. Подготовьте папку на компьтере и скопируйте в нее этот репозиторий.<br>
   Сделать это можно, например, командой в терминале:

    ```bash
    git clone https://github.com/open-math/ru.omath.net.git ru.omath.net
    ```

4. Установите все необходимые пакеты:

    ```bash
    bun install
    ```

Все готово!
Теперь вы можете добавлять новые материалы в учебник или изменять любые существующие!
Чтобы удобно и быстро видеть результат внесенных правок в реальном времени, включите режим разработчика:

```bash
bun dev
```

Локальная копия учебника будет доступна по адресу: http://localhost:3000

## Используемые технологии

Учебник работает на системе управления контентом [Erudit](https://github.com/erudit-js/erudit).
Все образовательные материалы записываются с использованием языка разметки [Bitran](https://github.com/bitran-js/bitran) в файлах с расширением `.bi`.
