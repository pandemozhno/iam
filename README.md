# Tree Architecture Specification 

Во Имя Аллаха Милостевого Милосердного
version "Topol"

Hightload and/or Accessibility 

Any interface can simplify to resource value and has principles of accessibility.

Первичный пример.
Представим HTML DOM как Дерево, тогда
<code>
корни - ``<html></html>``
кора - ``<head></head>``
ствол - ``<body></body>``
ветвь - ``<component></component>``
лист - ``<basic-component></basic-component>``
</code>
Продолжая аллегорию дерева мы можем понять архитектуру. 
Так например кольца - это store.
Копиляры - context react

Connector - api list
  timeout checker - hightload detector or internet throughput.


Пример vuejs архитектуры 

- roots (api list to backend)
    - index.js
- copillars (store pinia/vuex)
- branches (components)
    - twigs (basic components)
- bark (pages)
- trunk (layouts)

Архитектурное естествознание систем помогает проведенной аналогией осознать взаимодействие подсистем в приложениях.
Не абстрактные слои, понятия, я органичная система в которой отраженно взаимодействие частей.




