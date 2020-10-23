# 100 Days Of Code - Log

### День 1:  20 октября, 2020

**Что сделал**: 13/52 упражнений секции Applied Visual Design курса FreeCodeCamp.

**Мысли:** Нового пока ничего не узнал, зато повторил старое (особенно про порядок параметров в box-shadow);

<!--**Link to work:** [Calculator App](http://www.example.com)-->

### День 2:  21 октября, 2020

**Что сделал**: 32/52 упражнений секции Applied Visual Design курса FreeCodeCamp.

**Мысли:** Повторил знания о box-model, position (relative, absolute, fixed, sticky) и потоке (flow) документа. 
Узнал новое про теорию цветов (RGB и complementary-цвета). Узнал полезную информацию про hsl(hue - saturate - lightness).
Hue - по факту цвет, saturate - количество серого, lightness - наличие белого/черного. Получил полезную информацию по работе с градиентами, особенно
repeating-linear-gradient().  

### День 3:  22 октября, 2020

**Что сделал**: 52/52 упражнений секции Applied Visual Design курса FreeCodeCamp.

**Мысли:** Повторял работу с анимациями (animation-name, animation-duration, @keyframes). Детально разобрал
animation-timig-function:

    ease - медленно начинается, потом ускоряется, в конце снова замедляется
    ease-out - быстро начинается, потом замедляется
    ease-in - медленно начинается, потом ускоряется
    linear - одинаковая скорость на протяжении всей анимации
    cubic-bezier - оси X и Y, функция всегда начинается с p0 (0,0) и заканчивается на p3 (1,1)
    значения x (x, y, x, y) не могут быть больше 1, а значения y - могут.

По animation-timing-function: cubic-bezier() - нужно еще более детально разобраться (посмотреть видео и почитать материалы).

### День 4:  23 октября, 2020

**Что сделал**: Изучил более детально работу с анимациями, конкретно с animation-timing-function: cubic-bezier(), посмотрел и 
попрактиковался, как это можно применять во Vue-приложениях.

**Мысли:** Очень интересная штука, Vue-transitions открылись с новой стороны. Нашел сайт cubic-bezier.com,
который позволяет генерировать параметры для анимации. Написал небольшую анимацию для router-view transitions.

**Link to work:** [GitHub](https://github.com/atogz/cubic-bezier-vue)
                  [Demo](https://practical-mclean-59ebf8.netlify.app/)
