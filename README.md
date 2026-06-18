### Статус проекта:
[![check.yml](https://github.com/Kromian1/php-project-45/actions/workflows/check.yml/badge.svg)](https://github.com/Kromian1/php-project-45/actions/workflows/check.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=Kromian1_php-project-45&metric=alert_status&token=f6987d8085321cfb7a7481fcbd9191619e5631bc)](https://sonarcloud.io/summary/new_code?id=Kromian1_php-project-45)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=Kromian1_php-project-45&metric=bugs&token=f6987d8085321cfb7a7481fcbd9191619e5631bc)](https://sonarcloud.io/summary/new_code?id=Kromian1_php-project-45)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=Kromian1_php-project-45&metric=code_smells&token=f6987d8085321cfb7a7481fcbd9191619e5631bc)](https://sonarcloud.io/summary/new_code?id=Kromian1_php-project-45)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=Kromian1_php-project-45&metric=duplicated_lines_density&token=f6987d8085321cfb7a7481fcbd9191619e5631bc)](https://sonarcloud.io/summary/new_code?id=Kromian1_php-project-45)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=Kromian1_php-project-45&metric=ncloc&token=f6987d8085321cfb7a7481fcbd9191619e5631bc)](https://sonarcloud.io/summary/new_code?id=Kromian1_php-project-45)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=Kromian1_php-project-45&metric=reliability_rating&token=f6987d8085321cfb7a7481fcbd9191619e5631bc)](https://sonarcloud.io/summary/new_code?id=Kromian1_php-project-45)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=Kromian1_php-project-45&metric=security_rating&token=f6987d8085321cfb7a7481fcbd9191619e5631bc)](https://sonarcloud.io/summary/new_code?id=Kromian1_php-project-45)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=Kromian1_php-project-45&metric=sqale_index&token=f6987d8085321cfb7a7481fcbd9191619e5631bc)](https://sonarcloud.io/summary/new_code?id=Kromian1_php-project-45)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=Kromian1_php-project-45&metric=sqale_rating&token=f6987d8085321cfb7a7481fcbd9191619e5631bc)](https://sonarcloud.io/summary/new_code?id=Kromian1_php-project-45)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=Kromian1_php-project-45&metric=vulnerabilities&token=f6987d8085321cfb7a7481fcbd9191619e5631bc)](https://sonarcloud.io/summary/new_code?id=Kromian1_php-project-45)
# Brain Games

Brain Games — консольное приложение на PHP, содержащее набор математических игр. Каждая игра генерирует случайные вопросы и проверяет ответы пользователя.

## Доступные игры:

1. **Brain Even** - Определение четности числа
2. **Brain Calc** - Арифметические выражения
3. **Brain GCD** - Наибольший общий делитель
4. **Brain Prime** - Проверка числа на простоту
5. **Brain Progression** - Поиск пропущенного числа в прогрессии

##  Установка:

```bash
git clone https://github.com/Kromian1/php-project-45.git
cd php-project-45
make install
```

## Запуск:

**Меню выбора игры:**

```bash
make launcher
```

**Запуск игр:**

| Команда | Игра |
|----------|-------|
| `make even` | Проверка на чётность |
| `make calc` | Калькулятор |
| `make gcd` | НОД |
| `make prime` | Простое число |
| `make progression` | Прогрессия |

## Структура проекта:

| Каталог / Файл | Назначение |
|---------------|------------|
| `bin/` | Исполняемые файлы для запуска игр |
| `src/Cli.php` | Работа с пользовательским вводом и выводом |
| `src/Engine.php` | Общая игровая логика и цикл выполнения игр |
| `src/Games/` | Реализации игровых сценариев: Even, Calc, Gcd, Progression, Prime и Launcher |


## Требования:
- PHP 8.0+
- Composer

## Пример сессии игры (Asciinema):

- **Brain Even**: https://asciinema.org/a/NlLBXyOl7idgoTrTIYKJRDlIf

- **Brain Calc**: https://asciinema.org/a/5UReAlDy3kAVsV2xKYYxgk5sE

- **Brain GCD**: https://asciinema.org/a/vRpXBcn4DlrZvvNkECB5FKdeC

- **Brain Prime**: https://asciinema.org/a/Tu3k9dyN6oHV6k04cSVUTEf4F

- **Brain Progression**: https://asciinema.org/a/siSPvVCGaMzJoNsLuwXEL4Cjd
