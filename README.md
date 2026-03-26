# pz8
EX1  

    #include <iostream>
    using namespace std;

    int main() {
    // Настройка корректного отображения русского языка в консоли
    setlocale(LC_ALL, "Russian");

    int number; // Объявляем переменную для хранения числа
    cin >> number; // Считываем число с клавиатуры

    // Проверяем, больше ли число нуля, и выводим «Положительное», если условие выполняется
    if (number > 0) {
        cout << "Положительное";
    }

    return 0;
    }

  EX2
  ```
  #include <iostream>

    using namespace std;
    int main() {
    int number; // Объявляем переменную для хранения числа
    cin >> number; // Считываем число с клавиатуры

    if (number == 10)
        cout << "Число равно 10";
    else 
        cout << "Число не равно 10";



    return 0; // Завершаем программу
}
```
EX3
```
#include <iostream>

using namespace std;
int main() {
    int number;
    cin >> number;
    
    if (number < 0)
        cout << "Число отрицательное";
    else
        cout << "Число не отрицательное";

    // Ваш код




    return 0;
}
```
EX4
```
#include <iostream>

using namespace std;

int main() {
    int a, b; // Объявляем две переменные
    cin >> a >> b; // Считываем два числа сразу
    if (a > b)
    
       cout << "Большее число: "<< a;
    
    else if (a < b)
        cout << "Большее число: " << b;
    else 
        cout << "Числа равны";
    
    // Ваш код:



    return 0;
}
```
EX5
```
#include <iostream>

using namespace std;

int main() {
    int number;
    cin >> number;
    if (1 <= number && number <= 10){
        cout << "Число принадлежит диапазону";
    } else {
        cout << "Число не принадлежит диапазону";
    }


    



    return 0;
}
```
EX6
```
#include <iostream>

using namespace std;

int main() {
    int number;
    cin >> number;
    if (1 <= number && number <= 5)
        cout << "Число принадлежит одному из диапазонов";
    else if (10 <= number && number <= 15)
        cout << "Число принадлежит одному из диапазонов";
    else 
        cout << "Число не принадлежит указанным диапазонам";
    


    



    return 0;
}
```
EX7
```
#include <iostream>

using namespace std;

int main() {
    int number;
    cin >> number;

    if (number > 0 && number % 2 == 0 && number < 100) {
        cout << "Подходит";
    }
    else {
        cout << "Не подходит";
    }

    return 0;
}

```
