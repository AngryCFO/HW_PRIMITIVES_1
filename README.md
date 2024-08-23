# Домашнее задание к занятию «Примитивные типы данных и условные операторы»

**Case1.java**
```java
public class Case1 {
  public static void main(String[] args) {
    // Объявляете переменные для входных данных и
    // параметров программы: одну для хранения 
    // стоимости билета, другую для хранения количества
    // рублей для одной бонусной мили
    int ticketPrice = 13676; // стоимость билета
    int rublesPerMile = 20; // количество рублей для одной бонусной мили
    
    // Рассчитываете количество бонусных миль, используя
    // значения заведённых переменных. Ответ сохраняете в
    // новую переменную и выводите на экран
    int bonusMiles = ticketPrice / rublesPerMile;
    System.out.println("Количество бонусных миль: " + bonusMiles);
  }
}
```

**Main.java**
```java
public class Main {
  public static void main(String[] args) {
    System.out.println("Бонусные мили:");
    Case1.main(args);
    System.out.println("\nБонус за пополнение:");
    Case2.main(args);
  }
}
```

**Результат**
```
Бонусные мили:
Количество бонусных миль: 683

```
## Файлы с кодом можно посмотреть в [папке](https://github.com/AngryCFO/HW_PRIMITIVES/tree/main/src)
