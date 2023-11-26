# Soul project

Laravel, Vite, Inertia.js, Vue 3, Laravel Data и других.

Гайд по проекту: [https://youtu.be/OqacdH3K8OY](https://youtu.be/OqacdH3K8OY)

## Установка

```bash
$ cp .env.example .env
$ composer install
$ ./vendor/bin/sail up -d
$ ./vendor/bin/sail artisan key:generate
$ ./vendor/bin/sail npm i
$ ./vendor/bin/sail artisan migrate --seed
```

## Запуск

```bash
$ ./vendor/bin/sail npm run dev
```

Приложение будет доступно по адресу [http://localhost](http://localhost)
