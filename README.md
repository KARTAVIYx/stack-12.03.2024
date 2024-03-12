# stack-12.03.2024
#include <iostream> 
#include <fstream> 
#include <string>   
#include <vector> 
#include <cstdlib>
#include <cmath>
#include <algorithm>
#include <iterator>
#include <list>
#include <random>
#include <stack>
using namespace std;



int main() {
    setlocale(LC_ALL, "ru");
 
    stack<int> numbers;
    //добавление элементов в стек
    numbers.push(1);
    numbers.push(2);
    numbers.push(3);
    

    //показывает верхний значение  добавлении элементов в стек
    cout << "Верхняя часть стека: " << numbers.top()  << endl;

    //удаление верхнего элемента
    numbers.pop();
    
    //вывод верхнего элемента после удаления
    cout << numbers.top() << '\n';
    
    //проверка на пустой стек
    if (!numbers.empty()) {
        cout << "Стек не пуст" << endl;
    }
    else {
        cout << "стек пуст" << endl;
    }
    
    

    return 0;
}
