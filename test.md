html
<div class="tabs">
  <button class="tablink" onclick="openTab(event, 'Tab1')">Вкладка 1</button>
  <button class="tablink" onclick="openTab(event, 'Tab2')">Вкладка 2</button>
  
  <div id="Tab1" class="tabcontent">
    | Заголовок 1 | Заголовок 2 |
    |-------------|-------------|
    | Данные 1    | Данные 2    |
    | Данные 3    | Данные 4    |
  </div>
  
  <div id="Tab2" class="tabcontent">
    | Заголовок A | Заголовок B |
    |-------------|-------------|
    | Данные A    | Данные B    |
  </div>
</div>

<script>
function openTab(evt, tabName) {
  // Логика переключения вкладок
}
</script>
