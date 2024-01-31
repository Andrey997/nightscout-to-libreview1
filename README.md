# Передача данных из Nightscout в LibreView
Перенесите свои данные о диабете из Nighscout в Librewiev

## Требования
- Установить git https://github.com/git-for-windows/git/releases/download/v2.43.0.windows.1/Git-2.43.0-64-bit.exe
- Установить nodejs https://nodejs.org/dist/v20.11.0/node-v20.11.0-x64.msi

## Первое использование

Открыть командную строку (Меню Пуск>Node.js> Node.js command prompt):
```
git clone https://github.com/Andrey997/nightscout-to-libreview1
cd nightscout-to-libreview1
npm install
npm start
```

## Будущие использования

Открыть командную строку (Меню Пуск>Node.js> Node.js command prompt):
```
cd nightscout-to-libreview1
npm start
```

## Todo
- many many testing!
- better error handling
- clean up entry point
- clean up user input
- add frequent unscheduledContinuousGlucoseEntries
- add notes from libreview
- add basal insulin?!?
- different libreview api endpoints
