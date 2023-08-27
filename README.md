### Содержание

| №   | Вопрос                                                                                                                                                                                                                                                                                                                 |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [Как работает специфичность в CSS?](#как-работает-специфичность-в-css)                                                                                                                                                                                                                                                 |
| 2   | [Что такое БЭМ (Block-Element-Modifier) методология и какие преимущества она предоставляет?](#что-такое-бэм-методология-и-какие-преимущества-она-предоставляет)                                                                                                                                                        |
| 3   | [Как работают псевдоэлементы `::before` и `::after`?](#как-работают-псевдоэлементы-before-и-after)                                                                                                                                                                                                                     |
| 4   | [Что такое Flexbox и какие основные свойства Flexbox контейнера и элементов?](#что-такое-flexbox-и-какие-основные-свойства-flexbox-контейнера-и-элементов)                                                                                                                                                             |
| 5   | [Как работает система сеток в CSS Grid?](#как-работает-система-сеток-в-css-grid)                                                                                                                                                                                                                                       |
| 6   | [Каким образом можно создать анимацию с использованием CSS?](#каким-образом-можно-создать-анимацию-с-использованием-css)                                                                                                                                                                                               |
| 7   | [Что такое CSS-переменные (кастомные свойства) и какие преимущества они предоставляют?](#что-такое-css-переменные-кастомные-свойства-и-какие-преимущества-они-предоставляют)                                                                                                                                           |
| 8   | [Какие различия между позиционированием `relative`, `absolute` и `fixed`?](#какие-различия-между-позиционированием-relative-absolute-и-fixed)                                                                                                                                                                          |
| 9   | [Что такое CSS-гриды и в каких случаях их следует использовать?](#что-такое-css-гриды-и-в-каких-случаях-их-следует-использовать)                                                                                                                                                                                       |
| 10  | [Как работает понятие "контроль переполнения" (overflow) и его свойства?](#как-работает-понятие-контроль-переполнения-overflow-и-его-свойства)                                                                                                                                                                         |
| 11  | [Что такое "резиновый" и "адаптивный" дизайн? В чем разница между ними?](#что-такое-резиновый-и-адаптивный-дизайн-в-чем-разница-между-ними)                                                                                                                                                                            |
| 12  | [Как работает свойство `z-index` и как управлять стеком z-индексов?](#как-работает-свойство-z-index-и-как-управлять-стеком-z-индексов)                                                                                                                                                                                 |
| 13  | [Что такое "рендеринговая цепочка" и как CSS влияет на процесс рендеринга в браузере?](#что-такое-рендеринговая-цепочка-и-как-css-влияет-на-процесс-рендеринга-в-браузере)                                                                                                                                             |
| 14  | [Какие преимущества и недостатки использования CSS-препроцессоров, таких как Sass или Less?](#какие-преимущества-и-недостатки-использования-css-препроцессоров-таких-как-sass-и-less)                                                                                                                                  |
| 15  | [Что такое "рефлов" и "рефлоу" в контексте CSS и как они влияют на производительность?](#что-такое-рефлов-и-рефлоу-в-контексте-css-и-как-они-влияют-на-производительность)                                                                                                                                             |
| 16  | [Какие различия между псевдоклассами `:nth-child` и `:nth-of-type`?](#какие-различия-между-псевдоклассами-nth-child-и-nth-of-type)                                                                                                                                                                                     |
| 17  | [Что такое "вендорные префиксы" в CSS и зачем они используются?](#что-такое-вендорные-префиксы-в-css-и-зачем-они-используются)                                                                                                                                                                                         |
| 18  | [Какие механизмы доступности (accessibility) следует учитывать при разработке с использованием CSS?](#какие-механизмы-доступности-accessibility-следует-учитывать-при-разработке-с-использованием-css)                                                                                                                 |
| 19  | [Что такое "критический путь рендеринга" и как CSS может влиять на него?](#что-такое-критический-путь-рендеринга-и-как-css-может-влиять-на-него)                                                                                                                                                                       |
| 20  | [Как работает механизм наследования в CSS? Какие свойства наследуются, а какие нет?](#как-работает-механизм-наследования-в-css-какие-свойства-наследуются-а-какие-нет)                                                                                                                                                 |
| 21  | [Что такое "кросс-браузерная совместимость" и какие стратегии существуют для обеспечения её в CSS?](#что-такое-кросс-браузерная-совместимость-и-какие-стратегии-существуют-для-обеспечения-её-в-css)                                                                                                                   |
| 22  | [Какие альтернативы `display: none` с точки зрения доступности?](#какие-альтернативы-display-none-с-точки-зрения-доступности)                                                                                                                                                                                          |
| 23  | [Что такое "флексибильность" и "эластичность" в контексте CSS? Какие свойства соответствуют этим понятиям?](#что-такое-флексибильность-и-эластичность-в-контексте-css-какие-свойства-соответствуют-этим-понятиям)                                                                                                      |
| 24  | [Какие методы оптимизации производительности CSS вы знаете?](#какие-методы-оптимизации-производительности-css-вы-знаете)                                                                                                                                                                                               |
| 25  | [Что такое "ретинизация" изображений и как связано с CSS?](#что-такое-ретинизация-изображений-и-как-связано-с-css)                                                                                                                                                                                                     |
| 26  | [Какие нововведения были введены в CSS3 по сравнению с CSS2?](#какие-нововведения-были-введены-в-css3-по-сравнению-с-css2)                                                                                                                                                                                             |
| 27  | [Что такое "крест-браузерное тестирование" (cross-browser testing) и как оно применяется к CSS?](#что-такое-крест-браузерное-тестирование-cross-browser-testing-и-как-оно-применяется-к-css)                                                                                                                           |
| 28  | [Каким образом CSS может влиять на SEO (оптимизацию для поисковых систем)?](#каким-образом-css-может-влиять-на-seo-оптимизацию-для-поисковых-систем)                                                                                                                                                                   |
| 29  | [Что такое "гибкая" (fluid) и "фиксированная" (fixed) верстка? Какие преимущества и недостатки каждого подхода?](#что-такое-гибкая-fluid-и-фиксированная-fixed-верстка-какие-преимущества-и-недостатки-каждого-подхода)                                                                                                |
| 30  | [Какие методы обеспечивают поддержку многоязычности и локализации с использованием CSS?](#какие-методы-обеспечивают-поддержку-многоязычности-и-локализации-с-использованием-css)                                                                                                                                       |
| 31  | [Какие преимущества имеет использование методологии CSS-in-JS по сравнению с обычными CSS файлами?](#какие-преимущества-имеет-использование-методологии-css-in-js-по-сравнению-с-обычными-css-файлами)                                                                                                                 |
| 32  | [Что такое "переполнение контейнера" (overflow) и как управлять им при разработке интерфейса?](#что-такое-переполнение-контейнера-overflow-и-как-управлять-им-при-разработке-интерфейса)                                                                                                                               |
| 33  | [Как работают CSS-градиенты и какие типы градиентов существуют?](#как-работают-css-градиенты-и-какие-типы-градиентов-существуют)                                                                                                                                                                                       |
| 34  | [Что такое "респонсивные изображения" и как обеспечить их корректную загрузку на разных устройствах?](#что-такое-респонсивные-изображения-и-как-обеспечить-их-корректную-загрузку-на-разных-устройствах)                                                                                                               |
| 35  | [Какие новые возможности по работе с текстом были добавлены в CSS3?](#какие-новые-возможности-по-работе-с-текстом-были-добавлены-в-css3)                                                                                                                                                                               |
| 36  | [Что такое "медиа-запросы" (media queries) и как они используются для создания адаптивного дизайна?](#что-такое-медиа-запросы-media-queries-и-как-они-используются-для-создания-адаптивного-дизайна)                                                                                                                   |
| 37  | [Какие способы вертикального выравнивания элементов в CSS вы знаете?](#какие-способы-вертикального-выравнивания-элементов-в-css-вы-знаете)                                                                                                                                                                             |
| 38  | [Что такое "плавающие элементы" (floats) в CSS и как они влияют на макет?](#что-такое-плавающие-элементы-floats-в-css-и-как-они-влияют-на-макет)                                                                                                                                                                       |
| 39  | [Какие преимущества и недостатки имеют иконочные шрифты по сравнению с SVG иконками?](#какие-преимущества-и-недостатки-имеют-иконочные-шрифты-по-сравнению-с-svg-иконками)                                                                                                                                             |
| 40  | [Что такое "сгенерированный контент" (generated content) и как он может использоваться в CSS?](#что-такое-сгенерированный-контент-generated-content-и-как-он-может-использоваться-в-css)                                                                                                                               |
| 41  | [Как работает система единиц измерения `rem` в CSS? В чем её преимущества перед `px` и `em`?](#как-работает-система-единиц-измерения-rem-в-css-в-чем-её-преимущества-перед-px-и-em)                                                                                                                                    |
| 42  | [Что такое "скользящий эффект" (parallax) в веб-дизайне и как его реализовать с помощью CSS?](#что-такое-скользящий-эффект-parallax-в-веб-дизайне-и-как-его-реализовать-с-помощью-css)                                                                                                                                 |
| 43  | [Как работают фильтры в CSS и какие виды фильтров существуют?](#как-работают-фильтры-в-css-и-какие-виды-фильтров-существуют)                                                                                                                                                                                           |
| 44  | [Что такое "каскадность" (cascading) в CSS и какие приоритеты применения стилей в селекторах?](#что-такое-каскадность-cascading-в-css-и-какие-приоритеты-применения-стилей-в-селекторах)                                                                                                                               |
| 45  | [Какие методы оптимизации загрузки CSS на веб-странице вы знаете?](#какие-методы-оптимизации-загрузки-css-на-веб-странице-вы-знаете)                                                                                                                                                                                   |
| 46  | [Что такое "доступность первого взгляда" (First Meaningful Paint) и как CSS может повлиять на этот показатель?](#что-такое-доступность-первого-взгляда-first-meaningful-paint-и-как-css-может-повлиять-на-этот-показатель)                                                                                             |
| 47  | [Как использовать псевдокласс `:not()` для выбора элементов, которые НЕ соответствуют определенному селектору?](#как-использовать-псевдокласс-not-для-выбора-элементов-которые-не-соответствуют-определенному-селектору)                                                                                               |
| 48  | [Что такое "градиентные переходы" (gradient transitions) в CSS и как их создать с помощью анимаций?](#что-такое-градиентные-переходы-gradient-transitions-в-css-и-как-их-создать-с-помощью-анимаций)                                                                                                                   |
| 49  | [Какие методы сглаживания шрифтов существуют в CSS и как они влияют на внешний вид текста?](#какие-методы-сглаживания-шрифтов-существуют-в-css-и-как-они-влияют-на-внешний-вид-текста)                                                                                                                                 |
| 50  | [Что такое "медиа-типы" (media types) в CSS и для чего они используются?](#что-такое-медиа-типы-media-types-в-css-и-для-чего-они-используются)                                                                                                                                                                         |
| 51  | [Как работает псевдоэлемент `::first-letter` и как его использовать для стилизации первой буквы абзаца?](#как-работает-псевдоэлемент-first-letter-и-как-его-использовать-для-стилизации-первой-буквы-абзаца)                                                                                                           |
| 52  | [Что такое "вложенные селекторы" (nested selectors) в CSS и как они используются?](#что-такое-вложенные-селекторы-nested-selectors-в-css-и-как-они-используются)                                                                                                                                                       |
| 53  | [Как можно реализовать эффект "скользящей шапки" (sticky header) с помощью CSS?](#как-можно-реализовать-эффект-скользящей-шапки-sticky-header-с-помощью-css)                                                                                                                                                           |
| 54  | [Что такое "CSS-перехватчики" (CSS Houdini) и какие API они предоставляют для расширения CSS?](#что-такое-css-перехватчики-css-houdini-и-какие-api-они-предоставляют-для-расширения-css)                                                                                                                               |
| 55  | [Какие свойства в CSS используются для управления текстовым оформлением?](#какие-свойства-в-css-используются-для-управления-текстовым-оформлением)                                                                                                                                                                     |
| 56  | [Что такое "псевдоэлемент `::marker`" и как он используется для стилизации маркеров списков?](#что-такое-псевдоэлемент-marker-и-как-он-используется-для-стилизации-маркеров-списков)                                                                                                                                   |
| 57  | [Как создать анимацию "плавное появление" (fade-in) элемента при загрузке страницы с помощью CSS?](#как-создать-анимацию-плавное-появление-fade-in-элемента-при-загрузке-страницы-с-помощью-css)                                                                                                                       |
| 58  | [Что такое "границы" (box sizing) в CSS и какие значения они могут иметь?](#что-такое-границы-box-sizing-в-css-и-какие-значения-они-могут-иметь)                                                                                                                                                                       |
| 59  | [Какие методы "обнуления стилей" (CSS resets) существуют и для чего они используются?](#какие-методы-обнуления-стилей-css-resets-существуют-и-для-чего-они-используются)                                                                                                                                               |
| 60  | [Что такое "селекторы состояний" (state selectors) в CSS и как они используются для стилизации интерактивных элементов?](#что-такое-селекторы-состояний-state-selectors-в-css-и-как-они-используются-для-стилизации-интерактивных-элементов)                                                                           |
| 61  | [Как работает свойство `will-change` и в каких случаях оно может быть полезным?](#как-работает-свойство-will-change-и-в-каких-случаях-оно-может-быть-полезным)                                                                                                                                                         |
| 62  | [Что такое "полифиллы" (polyfills) в контексте CSS и зачем они используются?](#что-такое-полифиллы-polyfills-в-контексте-css-и-зачем-они-используются)                                                                                                                                                                 |
| 63  | [Как работает свойство `clip-path` и как оно может быть использовано для создания необычных форм элементов?](#как-работает-свойство-clip-path-и-как-оно-может-быть-использовано-для-создания-необычных-форм-элементов)                                                                                                 |
| 64  | [Что такое "комбинаторы соседства" (adjacent sibling combinators) в CSS и как они применяются для стилизации элементов на одном уровне вложенности?](#что-такое-комбинаторы-соседства-adjacent-sibling-combinators-в-css-и-как-они-применяются-для-стилизации-элементов-на-одном-уровне-вложенности)                   |
| 65  | [Как создать анимацию с эффектом "параллакса" (parallax scrolling) с использованием CSS?](#как-создать-анимацию-с-эффектом-параллакса-parallax-scrolling-с-использованием-css)                                                                                                                                         |
| 66  | [Что такое "селекторы атрибутов" (attribute selectors) и как они используются для выбора элементов по атрибутам?](#что-такое-селекторы-атрибутов-attribute-selectors-и-как-они-используются-для-выбора-элементов-по-атрибутам)                                                                                         |
| 67  | [Какие методы подходят для создания анимации в CSS, помимо `@keyframes`?](#какие-методы-подходят-для-создания-анимации-в-css-помимо-keyframes)                                                                                                                                                                         |
| 68  | [Что такое "CSS Grid Layout" и какие особенности этой системы сеток?](#что-такое-css-grid-layout-и-какие-особенности-этой-системы-сеток)                                                                                                                                                                               |
| 69  | [Каким образом можно создать адаптивные иконки с использованием CSS?](#каким-образом-можно-создать-адаптивные-иконки-с-использованием-css)                                                                                                                                                                             |
| 70  | [Что такое "миксины" (mixins) в препроцессорах CSS и как они используются?](#что-такое-миксины-mixins-в-препроцессорах-css-и-как-они-используются)                                                                                                                                                                     |
| 71  | [Какие методы обеспечения безопасности (security) применяются к CSS?](#какие-методы-обеспечения-безопасности-security-применяются-к-css)                                                                                                                                                                               |
| 72  | [Что такое "контентные контроли" (content control) в CSS и как они могут использоваться для создания интерактивных элементов?](#что-такое-контентные-контроли-content-control-в-css-и-как-они-могут-использоваться-для-создания-интерактивных-элементов)                                                               |
| 73  | [Как можно создать горизонтальное меню навигации с использованием CSS?](#как-можно-создать-горизонтальное-меню-навигации-с-использованием-css)                                                                                                                                                                         |
| 74  | [Что такое "спрайты" (sprites) в CSS и как они используются для управления изображениями?](#что-такое-спрайты-sprites-в-css-и-как-они-используются-для-управления-изображениями)                                                                                                                                       |
| 75  | [Какие методы улучшения производительности CSS можно применить для снижения времени загрузки страницы?](#какие-методы-улучшения-производительности-css-можно-применить-для-снижения-времени-загрузки-страницы)                                                                                                         |
| 76  | [Что такое "семантическая верстка" (semantic markup) в CSS и как она влияет на поисковую оптимизацию (SEO)?](#что-такое-семантическая-верстка-semantic-markup-в-css-и-как-она-влияет-на-поисковую-оптимизацию-seo)                                                                                                     |
| 77  | [Как можно реализовать анимацию появления (fade-in) элементов при прокрутке страницы с помощью CSS и JavaScript?](#как-можно-реализовать-анимацию-появления-fade-in-элементов-при-прокрутке-страницы-с-помощью-css-и-javascript)                                                                                       |
| 78  | [Что такое "псевдокласс `:focus`" и как он используется для стилизации элементов при получении ими фокуса?](#что-такое-псевдокласс-focus-и-как-он-используется-для-стилизации-элементов-при-получении-ими-фокуса)                                                                                                      |
| 79  | [Как создать анимацию "пульсации" (pulse) элемента с помощью CSS?](#как-создать-анимацию-пульсации-pulse-элемента-с-помощью-css)                                                                                                                                                                                       |
| 80  | [Что такое "переменные окружения" (environment variables) в препроцессорах CSS и как они могут быть полезны для настройки стилей?](#что-такое-переменные-окружения-environment-variables-в-препроцессорах-css-и-как-они-могут-быть-полезны-для-настройки-стилей)                                                       |
| 81  | [Каким образом можно стилизовать формы (input, textarea, select) с использованием CSS?](#каким-образом-можно-стилизовать-формы-input-textarea-select-с-использованием-css)                                                                                                                                             |
| 82  | [Что такое "анимации ключевых кадров" (keyframe animations) в CSS и как они работают?](#что-такое-анимации-ключевых-кадров-keyframe-animations-в-css-и-как-они-работают)                                                                                                                                               |
| 83  | [Какие свойства CSS используются для управления внешними отступами и полями элементов?](#какие-свойства-css-используются-для-управления-внешними-отступами-и-полями-элементов)                                                                                                                                         |
| 84  | [Что такое "флекс-контейнер" (flex container) и "флекс-элементы" (flex items) в контексте CSS Flexbox?](#что-такое-флекс-контейнер-flex-container-и-флекс-элементы-flex-items-в-контексте-css-flexbox)                                                                                                                 |
| 85  | [Как можно выровнять элементы по вертикали с использованием CSS?](#как-можно-выровнять-элементы-по-вертикали-с-использованием-css)                                                                                                                                                                                     |
| 86  | [Что такое "гибридные сетки" (hybrid grids) в CSS и как они могут быть использованы для создания сложных макетов?](#что-такое-гибридные-сетки-hybrid-grids-в-css-и-как-они-могут-быть-использованы-для-создания-сложных-макетов)                                                                                       |
| 87  | [Как работает "вендорное префиксирование" (vendor prefixes) и зачем оно используется в CSS?](#как-работает-вендорное-префиксирование-vendor-prefixes-и-зачем-оно-используется-в-css)                                                                                                                                   |
| 88  | [Что такое "флекс-обёртка" (flex-wrap) в контексте CSS Flexbox и как оно влияет на макет?](#что-такое-флекс-обёртка-flex-wrap-в-контексте-css-flexbox-и-как-оно-влияет-на-макет)                                                                                                                                       |
| 89  | [Как создать адаптивную галерею изображений с использованием CSS?](#как-создать-адаптивную-галерею-изображений-с-использованием-css)                                                                                                                                                                                   |
| 90  | [Что такое "базовые стили" (normalize.css, reset.css) и какое их значение для веб-разработки?](#что-такое-базовые-стили-normalizecss-resetcss-и-какое-их-значение-для-веб-разработки)                                                                                                                                  |
| 91  | [Как работает "переполнение по контенту" (content overflow) и как его контролировать с помощью CSS?](#как-работает-переполнение-по-контенту-content-overflow-и-как-его-контролировать-с-помощью-css)                                                                                                                   |
| 92  | [Что такое "критический путь рендеринга" (Critical Rendering Path) и как CSS может влиять на него?](#что-такое-критический-путь-рендеринга-critical-rendering-path-и-как-css-может-влиять-на-него)                                                                                                                     |
| 93  | [Каким образом можно создать анимацию текста, меняющего цвет, размер и стиль с помощью CSS?](#каким-образом-можно-создать-анимацию-текста-меняющего-цвет-размер-и-стиль-с-помощью-css)                                                                                                                                 |
| 94  | [Что такое "переменные CSS" (CSS variables) и как они используются для упрощения стилизации?](#что-такое-переменные-css-css-variables-и-как-они-используются-для-упрощения-стилизации)                                                                                                                                 |
| 95  | [Как можно создать адаптивные таблицы с использованием CSS?](#как-можно-создать-адаптивные-таблицы-с-использованием-css)                                                                                                                                                                                               |
| 96  | [Что такое "затенение элементов" (element shadowing) в CSS и как оно может быть использовано для изменения стиля элементов в зависимости от их расположения?](#что-такое-затенение-элементов-element-shadowing-в-css-и-как-оно-может-быть-использовано-для-изменения-стиля-элементов-в-зависимости-от-их-расположения) |
| 97  | [Каким образом можно создать анимацию "мерцания" (flicker) элемента с использованием CSS?](#каким-образом-можно-создать-анимацию-мерцания-flicker-элемента-с-использованием-css)                                                                                                                                       |
| 98  | [Что такое "гибкие изображения" (fluid images) и как они могут быть реализованы с помощью CSS?](#что-такое-гибкие-изображения-fluid-images-и-как-они-могут-быть-реализованы-с-помощью-css)                                                                                                                             |
| 99  | [Как создать "слайдер" (slider) с переключением слайдов с использованием CSS?](#как-создать-слайдер-slider-с-переключением-слайдов-с-использованием-css)                                                                                                                                                               |
| 100 | [Что такое "горизонтальная прокрутка" (horizontal scrolling) и как её реализовать с помощью CSS?](#что-такое-горизонтальная-прокрутка-horizontal-scrolling-и-как-её-реализовать-с-помощью-css)                                                                                                                         |
