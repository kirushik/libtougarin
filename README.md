libtougarin by Кирилл Пименов, <kirushik@gmail.com>

created at Чтв Авг 26 16:03:51 MSD 2010

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

### Общее описание
Данная библиотека реализует сохранение и загрузку диаграмм языка [ДРАКОН](http://ru.wikipedia.org/wiki/%D0%94%D0%A0%D0%90%D0%9A%D0%9E%D0%9D) в классы языка C++.

Для сохранения на диске классы сериализуются в формате [JSON]() с англоязычными заголовками элементов и полной поддержкой UTF-8 в их описаниях.

### Системные требования
Разработка ведётся под GNU/Linux с использованием компилятора g++.

При этом важной целью проекта является полная кросс-платформенная переносимость кода, поэтому для работы с JSON-форматом используется библиотека [QJson](http://qjson.sourceforge.net/).

### Дальнейшие планы
 * Разработать визуальный редактор диаграмм языка ДРАКОН с открытым под GNU/GPL исходным кодом. В разработе планируется использовать язык C++ и набор инструментов Qt.
 * Разработать принципы сборки блок-схем ДРАКОНА в исполняемые программы. *(Скорее всего, будет реализована сборка в llvm-байткод.)*

