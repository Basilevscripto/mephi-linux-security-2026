| Раздел | Описание | Файлы |
|--------|----------|-------|
| 1 | Создание user1 (UID 1234, группа students, смена пароля каждые 90) | passwd.out, shadow.out, group.out |
| 2 | Мониторинг set-UID файлов и процессов с euid-0 | suid_files.out, proc_monitor.out |
| 3 | set-UID на копии cat для чтения /etc/shadow | stat.out |
| 4 | Capabilities (cap_chown) на копии chown | stat.out, getcap.out |
| 5 | sudo для user1: timedatectl set-time | sudoers.out, sudoers_user1.out |
| 6 | Скриншот и история команд | mephi-screenshot.png, history.out |
ОС: РЕД ОС, SELinux переведенив режим permissive для выполнения пунктов 3 и 4.
# mephi-linux-security-2026-
