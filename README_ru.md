# Безопасность Linux для DevSecOps

**Языки:** [English](README.md) · [简体中文](README_zh.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/ru/courses/linux-security-for-devsecops">
    <img src="https://course-cover.labex.io/linux-security-for-devsecops.png?lang=ru" alt="Безопасность Linux для DevSecOps">
  </a>
</p>

Практический курс по безопасности Linux для специалистов DevSecOps, охватывающий вопросы доступности сервисов, защиты веб-приложений, прав доступа к файлам, настройки sudo, управления секретами и автоматизации задач от имени суперпользователя. Вы научитесь анализировать состояние хоста, применять целевые исправления и проверять работоспособность систем после их защиты.

[Начать курс на LabEx](https://labex.io/ru/courses/linux-security-for-devsecops)

## Упражнения

|   Индекс | Название                                              | Сложность   | Практика                                                                                                                                                       |
|----------|-------------------------------------------------------|-------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
|       01 | Аудит прослушиваемых сервисов                         | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/linux-audit-listening-services-662167?course=linux-security-for-devsecops'>Начать испытание</a>              |
|       02 | Ограничение доступа к интерфейсу администратора че... | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/linux-restrict-admin-interface-to-localhost-662317?course=linux-security-for-devsecops'>Начать испытание</a> |
|       03 | Удаление ненужного публичного порта                   | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/linux-remove-unnecessary-public-port-662316?course=linux-security-for-devsecops'>Начать испытание</a>        |
|       04 | Отключение листинга веб-каталогов                     | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/linux-disable-web-directory-listing-662309?course=linux-security-for-devsecops'>Начать испытание</a>         |
|       05 | Удаление открытого архива резервной копии             | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/linux-remove-exposed-backup-archive-662313?course=linux-security-for-devsecops'>Начать испытание</a>         |
|       06 | Исправление небезопасных прав доступа к файлу с се... | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/linux-fix-unsafe-secret-file-permissions-662310?course=linux-security-for-devsecops'>Начать испытание</a>    |
|       07 | Исправление прав доступа к веб-директории с доступ... | Начинающий  | <a target='_blank' href='https://labex.io/ru/labs/linux-fix-world-writable-web-directory-662311?course=linux-security-for-devsecops'>Начать испытание</a>      |
|       08 | Удаление избыточных прав sudo                         | Средний     | <a target='_blank' href='https://labex.io/ru/labs/linux-remove-over-permissive-sudo-rule-662315?course=linux-security-for-devsecops'>Начать испытание</a>      |
|       09 | Удаление жестко закодированных учетных данных         | Средний     | <a target='_blank' href='https://labex.io/ru/labs/linux-remove-hardcoded-credentials-662314?course=linux-security-for-devsecops'>Начать испытание</a>          |
|       10 | Укрепление безопасности задания cron, выполняемого... | Средний     | <a target='_blank' href='https://labex.io/ru/labs/linux-harden-root-run-cron-job-662312?course=linux-security-for-devsecops'>Начать испытание</a>              |
|       11 | Управление секретами в переменных окружения процес... | Средний     | <a target='_blank' href='https://labex.io/ru/labs/process-env-secret-662282?course=linux-security-for-devsecops'>Начать испытание</a>                          |
|       12 | Выделенный пользователь службы                        | Средний     | <a target='_blank' href='https://labex.io/ru/labs/dedicated-service-user-662278?course=linux-security-for-devsecops'>Начать испытание</a>                      |
|       13 | Ограничение прав доступа к логам                      | Средний     | <a target='_blank' href='https://labex.io/ru/labs/log-write-boundary-662281?course=linux-security-for-devsecops'>Начать испытание</a>                          |
|       14 | Очистка режима отладки                                | Средний     | <a target='_blank' href='https://labex.io/ru/labs/debug-mode-cleanup-662277?course=linux-security-for-devsecops'>Начать испытание</a>                          |
|       15 | Блокировка политики доступа к приложению              | Средний     | <a target='_blank' href='https://labex.io/ru/labs/app-policy-lockdown-662275?course=linux-security-for-devsecops'>Начать испытание</a>                         |
|       16 | Файл окружения службы                                 | Средний     | <a target='_blank' href='https://labex.io/ru/labs/service-env-file-662284?course=linux-security-for-devsecops'>Начать испытание</a>                            |
|       17 | Безопасный путь (PATH) для скрипта                    | Средний     | <a target='_blank' href='https://labex.io/ru/labs/safe-script-path-662283?course=linux-security-for-devsecops'>Начать испытание</a>                            |
|       18 | Ограничение пути резервного копирования               | Средний     | <a target='_blank' href='https://labex.io/ru/labs/backup-path-boundary-662276?course=linux-security-for-devsecops'>Начать испытание</a>                        |
|       19 | Диагностическая конечная точка                        | Средний     | <a target='_blank' href='https://labex.io/ru/labs/diagnostic-endpoint-662279?course=linux-security-for-devsecops'>Начать испытание</a>                         |
|       20 | Очистка после обхода инцидента                        | Продвинутый | <a target='_blank' href='https://labex.io/ru/labs/incident-bypass-cleanup-662280?course=linux-security-for-devsecops'>Начать испытание</a>                     |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>

