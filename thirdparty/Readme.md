# ThirdParty

Субмодули из других репозиториев. Используется джентельменский набор: SDL2 + imgui. Там есть всё что нужно разработчику эмуляторов.

## Добавление субмодулей в подпапку

https://stackoverflow.com/questions/9035895/how-do-i-add-git-submodule-to-a-sub-directory

Использовались такие команды:

```
git submodule add https://github.com/ocornut/imgui thirdparty/imgui
git submodule add -b SDL2 https://github.com/libsdl-org/SDL.git thirdparty/SDL2
```

Для SDL2 надо брать ветку SDL2 :-) Причём эти пиздюки нигде не пишут, что в их основной репе по дефолту уже SDL3. Я пока додумался где брать SDL2 - часа 2 прошло.. Оказалось-то вон оно чё.
