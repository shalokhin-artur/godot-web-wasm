# godot-web-wasm

Стоковый движок Godot для веб-экспорта (`web_nothreads_release`), байт-в-байт файл из официальных
шаблонов экспорта. Раздаётся через GitHub Pages (jsDelivr режет файлы больше 20 МБ), чтобы не класть 38 МБ в хостинг с лимитом на размер файла:

    https://shalokhin-artur.github.io/godot-web-wasm/index.wasm

В шелле Godot: `"executable":"https://shalokhin-artur.github.io/godot-web-wasm/index","mainPack":"index.pck"`.
