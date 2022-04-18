## Рецепт 

Ваша задача  проанализировать программу рассчёта распределения ингредиентов на порцию. Программе на вход даётся рецепт со всеми граммовками каждого ингредиента, а также количество человек, которые будут в одинаковых порциях его есть. На выходе программа указывает, какое точное количество (без округлений) каждого ингредиента пришлось на одну порцию еды.

```java
public class Main {
    public static void main(String[] args) {

        int eaters = 5; // сколько людей будут есть

        int water = 3000; // миллилитров воды
        int potatoes = 5; // картофелин
        int chicken = 6; // куриных бёдер
        int spices = 10; // ложек специй

        System.out.println("Сварили суп. На одного человека вышло:");
        System.out.println((water / eaters) + " миллилитров воды");
        System.out.println((potatoes / eaters) + " картофелин(а)");
        System.out.println((chicken / eaters) + " куриных(ое) бёдер(ро)");
        System.out.println((spices / eaters) + " ложек(ка) специй");

    }
}
```

Для анализа этой программы:

1. [Установите](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md) бесплатную версию идеи (Community version) с [официальной страницы](https://www.jetbrains.com/idea/download) (можно без установки Toolbox что в инструкции, можно просто скачать по второй ссылке этого пункта и установить напрямую).
2. Создайте пустой проект на основе Java 11 (идея её может скачать сама, если вы в меню выбора  Java выберите `Download JDK`).
3. Создайте класс Main с содержимым из кода выше.
4. Нажмите на кнопку запуска программы. Она должна запуститься, вывести информацию на экран и завершиться.
5. Закоммитьте и запушьте ваш проект в публичный репозиторий на гитхабе.
6. Проанализируйте код и вывод программы. Найдите в них дефект(ы). Менять код программы не нужно.
7. Оформите баг-репорт с помощью Github Issues, описывающий найденный дефект по шаблону из [примера](https://github.com/netology-code/javaqa2-homeworks/issues/2).

### Формат оформления баг-репорта
Наша цель получить такой [баг-репорт](https://github.com/netology-code/javaqa2-homeworks/issues/2):

![image](https://user-images.githubusercontent.com/53707586/161832746-1c6c42d0-4d64-4d1d-9b05-47b80a3f4a25.png)

Это можно сделать написав следующее:

![image](https://user-images.githubusercontent.com/53707586/145558346-22631529-597a-4332-951f-ec1cf550c701.png)

Комментарии к формату:
* И в .md-файлах, и внутри описания баг-репортов используется [формат Markdown](https://www.markdownguide.org/basic-syntax/).
* Исходный код Issue специально вставлен картинкой, чтобы вы вчитывались и перепечатывали, а не копировали.
* Чтобы красиво сослаться на нужное место в коде, нажмите на номер (или номера, удерживая `Shift`) соответствующей строки и рядом слева нажмите на троеточие, в выпавшем меню нажмите `Copy permalink`; в буфер обмена скопируется прямая ссылка на эту строку этого коммита. Теперь вы её можете просто вставить в текст Issue как в шаблоне:

![image](https://user-images.githubusercontent.com/53707586/145559373-0173b0af-f0dc-455e-ac0a-f7b6da85ae8a.png)

* Для загрузки изображений вы можете воспользоваться кнопкой, находящейся сразу под полем редактирования текста; также возможна автозагрузка скриншотов прямо из буфера обмена через `Ctrl+V` с автовставкой в место нахождения курсора:

![image](https://user-images.githubusercontent.com/53707586/145559790-cf4b1254-ceb8-4931-92dd-031575450583.png)

Какой баг-репорт получится из шаблона выше можно посмотреть [здесь](https://github.com/netology-code/javaqa2-homeworks/issues/2).

### Результат
При отправке решения в личном кабинете прикрепите ссылку на ваш публичный гитхаб-репозиторий.
