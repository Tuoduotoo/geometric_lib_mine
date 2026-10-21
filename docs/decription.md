# общее описание решения
Функции площади и периметра для круга, прямоугольника, квадрата, треугольника.
# описание каждой функции с примерами вызова
## круг 
### площадь
def area(r):
    Возращает площадь круга.
    Принимает r(радиус), возвращает произведение квадрата r и pi.
Пример:
area(0) = 0
area(2) = 12.566370614359172
area(-2) = 12.566370614359172

### периметр
def perimeter(r):
    Возращает периметр круга.
    Принимает r(радиус), возвращает удвоенное произведение r и pi.
Пример:
perimeter(0) = 0
perimeter(2) = 12.566370614359172
perimeter(-2) = -12.566370614359172

## треугольник 
### площадь
def area(a, h): 
    Возращает площадь треугольника.
    Принимает a(сторону), h(высоту), возвращает произведение a * h разделить на 2.
Пример:
area(0, 0) = 0
area(2, 2) = 2
area(2, 0) = 0

### периметр
def perimeter(a, b, c): 
    Возращает периметр треугольника.
    Принимает a, b, c(стороны), возвращает сумму a, b, c.
Пример:
perimeter(0, 0, 0) = 0
perimeter(1, 2, 3) = 6
perimeter(0, 1, 2) = 3

## прямоугольник
### площадь
def area(a, b): 
    Возращает площадь прямоугольника.
    Принимает a, b(длину и ширину), возвращает произведение a, b.
Пример:
area(0, 0) = 0
area(2, 2) = 4
area(2, 0) = 0

### периметр
def perimeter(a, b): 
    Возращает периметр прямоугольника.
    Принимает a, b(длину и ширину), возвращает удвоенную сумму a, b.
Пример:
perimeter(0, 0) = 0
perimeter(1, 2) = 6
perimeter(0, 1) = 2

## квадрат
### площадь
def area(a):
    Возращает площадь квадрата.
    Принимает a(сторону), возвращает квадрат a.
Пример:
area(0) = 0
area(2) = 4
area(-2) = 4

### периметр
def perimeter(a):
    Возращает периметр квадрата.
    Принимает a(сторону), возвращает произведение a, 4.
Пример:
perimeter(0) = 0
perimeter(2) = 8
perimeter(-2) = -8

# история изменения проекта с хешами комитов (кроме последней записи)

* 6753daa (HEAD -> new_features_408526) Decription added
* 74c81b8 All comments fixed
* 676bd99 Triangle commented
* 8ecb6f4 Square commented
* 4802754 Circle commented
* 214f175 Rectangle commented
* a72750e Triangle added and rectangle fixed
* a9529a9 Triangle added and rectangle fixed
* f3f9344 Rectangle added
| * 86edb1c (origin/release) L-05: Update Docs. Add user agreement info
| * 438b89a L-05: Add user agreement
| * 6adb962 L-03: Docs added
| | * 3049431 (origin/feature) L-04: Add rectangle.py
| |/  
|/|   
| | * b5b0fae (origin/develop) L-04: Update docs for calculate.py
| | * d76db2a L-04: Add calculate.py
| | * 51c40eb L-04: Doc updated for triangle
| | * d080c78 L-04: Triangle added
| |/  
|/|   
* | d078c8d (origin/main, origin/HEAD, main) L-03: Docs added
|/  
* 8ba9aeb L-03: Circle and square added