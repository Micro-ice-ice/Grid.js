<h1>Геометрические примитивы</h1>

<p>
    Данная директория содержит в себе реализацию геометрических примитивов (точка, линия, тетраэдр, куб)
<p>

<p>
    Все геометрические примитивы описываются набором вершин и граней. 
    Поэтому для создания нового, достаточко описать эти наборы. 
    Грани можно задавать с помощью индексов вершин, тогда для каждого экземпляра примитива он будет одинаковый. 
</p>

<p>
    Класс Cell описывает общий вид примитива. На его основе реализованы все примитивы.
</p>

<p>
    В классе описано свойство ThreeObject. Данное свойство содержит описание экземпляра примитива как объекта сцены Three.js, что позволяет его рендерить.
</p>

<p>
    cell_types экспортирует все примитивы
</p>
