# 🐱 Meow Intelligent Terminal

<p align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=matvey2222222222.meow-terminal&left_text=Views" alt="Views"/>
  <img src="https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D6?logo=windows&logoColor=white" alt="Platform"/>
  <img src="https://img.shields.io/badge/Status-Active%20Development-yellow" alt="Status"/>
  <img src="https://img.shields.io/badge/Installer-Portable-brightgreen" alt="Portable"/>
</p>

**Meow Intelligent Terminal** — умная замена `cmd.exe` для Windows. Понимает с полуслова, исправляет опечатки, подсказывает команды из истории и напоминает о важном.

---

## ✨ Возможности

- **🐾 Исправление опечаток** — ввёл `dri`? Терминал предложит `dir`. Распознаёт даже перестановку соседних букв.
- **🧠 Подсказки из истории** — если команда похожа на ту, что ты уже вводил, Meow предложит её использовать. Отклонённые подсказки больше не появляются.
- **🚀 Ghost-text** — серая подсказка прямо в строке ввода. Нажми `→`, чтобы принять.
- **📂 Встроенные команды** — `ls`, `cat`, `mkdir`, `rm`, `cp`, `mv`, `find`, `grep` и ещё 20+ работают на чистом Python и не требуют `cmd.exe`.
- **⏰ Напоминания** — абсолютное время, интервалы (`+5m`, `+2h`) и повторы (`daily`, `weekly`). Уведомления — нативные, в стиле Windows.
- **⚙️ Переключение shell** — `cmd` и `PowerShell` на лету одной командой. Пользовательские алиасы.

---

## 🚀 Скачать

**Python устанавливать не нужно** — всё упаковано внутрь `.exe`.

1. Открой раздел [**Releases**](../../releases)
2. Скачай последний `MeowTerminal.exe`
3. Положи в удобную папку, например `C:\MeowTerminal\`
4. Двойной клик — готово

**Требования:** Windows 10 / 11 (x64), ~30 МБ на диске.

---

## 📖 Как пользоваться

### Умные подсказки

| Действие | Что произойдёт |
| :--- | :--- |
| Ввести `dri` | 🐾 Предложит `dir`? |
| Нажать `Tab` | Автодополнение команды |
| Нажать `→` | Принять серую ghost-подсказку |

### Встроенные команды

| Группа | Команды |
| :--- | :--- |
| **Файлы** | `ls`, `dir`, `cd`, `pwd`, `cat`, `head`, `tail`, `wc`, `mkdir`, `rm`, `cp`, `mv`, `touch`, `tree`, `find`, `grep` |
| **Система** | `echo`, `whoami`, `hostname`, `date`, `time`, `cls`, `open` |
| **Управление** | `shell cmd`, `shell powershell` |

### Напоминания

```bash
meow remind 14:30 "Позвонить маме"       # абсолютное время
meow remind +5m "Проверить почту"        # через 5 минут
meow remind 9:00 "Стендап" daily         # каждый день
meow list                                # список всех
meow del <id>                            # удалить
