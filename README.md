# Icon Pack 

Моя мини-коллекция иконок для приложений

![Cover 1](cover-pic/Cover(1).png)
Obsidian icon | IDE icon | Firefox icon | VS code icon | Settings (ide) icon | Kitty terminal icon

![Cover](cover-pic/Cover.png)
IDE icon | Firefox icon | Obsidian icon | VS code icon | Notepad icon

![Cover 2](cover-pic/Cover(2).png)
Notepad icon | Firefox icon | IDE icon | Obsidian icon | VS code icon | Settings (ide) icon | Kitty terminal icon

## Содержимое

Коллекция включает два пака иконок:

### Gray Pack (`gray-pack/`)
Монохромный серый пак с иконками для:
- Code - редактор кода
- Firefox - веб-браузер, Firefox icon
- IDE - интегрированная среда разработки, ide icon
- Kitty - терминал, kitty icon
- Note - заметки, notepad icon
- Obsidian - система управления знаниями, obsidian icon

### White Pack (`white-pack/`)
Белый пак с иконками для:
- Code - редактор кода
- Firefox - веб-браузер
- IDE - интегрированная среда разработки
- Notes - заметки
- Obsidian - система управления знаниями

Форматы:
- `.png` 
- `.svg` 

## Установка

### Linux (GNOME)

1. Скопируйте иконки в папку `~/.local/share/icons/`:
```bash
mkdir -p ~/.local/share/icons/icon-pack
cp -r gray-pack/* ~/.local/share/icons/icon-pack/
```

2. Используйте шаблон `template.desktop` из папки `linux-desktop-files/` для создания собственных ярлыков:
```bash
# Отредактируйте template.desktop и установите:
desktop-file-install --dir=~/.local/share/applications linux-desktop-files/template.desktop
```

3. Обновите кэш иконок:
```bash
gtk-update-icon-cache -f ~/.local/share/icons/icon-pack
```

### macOS

Для замены иконок в macOS:
1. Откройте приложение в Finder
2. Выберите "Свойства" (Get Info) или нажмите `Cmd+I`
3. Скопируйте иконку из папки и вставьте в окно свойств приложения

