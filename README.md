# **_Третья проектная работа "Сложно сосредоточиться"_**

[Ссылка на репозиторий](https://github.com/Shakhov-Aleksandr/slozhno-sosredotochitsya-fd "Last chance")

## **_Проблема с отрисовкой декоративного текста темной темы при светлом режиме ОС_**

* В фале light.css для медиазапроса добавился класс, делающий блок декоративного элемента видимым для темной темы:

```css
@media (prefers-color-scheme: light) {
    
    ...

    .theme-dark .decorated-zone__docorated-text {
    visibility: visible;
  }
}
'''
