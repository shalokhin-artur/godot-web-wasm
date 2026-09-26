# godot-web-wasm

Стоковый движок Godot для веб-экспорта (`web_nothreads_release`), байт-в-байт файл из официальных
шаблонов экспорта. Раздаётся через jsDelivr, чтобы не класть 38 МБ в хостинг с лимитом на размер файла:

    https://cdn.jsdelivr.net/gh/artfullstackdev/godot-web-wasm@v4.7.1/index.wasm

В шелле Godot: `"executable":"https://cdn.jsdelivr.net/gh/artfullstackdev/godot-web-wasm@v4.7.1/index","mainPack":"index.pck"`.
