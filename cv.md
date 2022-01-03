## [RSSchool-cv](https://rs.school/)
![photo](https://github.com/vados73/rsschool-cv/blob/gh-pages/img/Surin%20Vadim.jpg)
# **Surin Vadim**
***

### Contacts:
   - **Discord:** Vados73
   - **E-mail:** <vados73@yandex.ru>
   - **Phone:** +7(960)298-5342

### About myself:
I'm 49 years old. At the moment I work at a metallurgical plant.\
I want to master a new interesting profession of a frontend developer. 
I am also interested in the backend and databases.

### Code example:
```
//Программа для перевода десятичных чисел в двоичные.. (с)
var number = prompt('Введите любое целое десятичное число:', ''); //Вводим любое целое десятичное число

var residue = number; //переменная для записи остатка от деления в массив
var quotient = number; //переменная для записи частного от деления на 2

var result = []; //создаем пустой массив для записи результата вычисления
    if (quotient == 1) { //если введенное число равно 1
        document.write('0001') //выводим 1
       } else { //..иначе
        do { //цикл вычисления двоичного числа    
            quotient /= 2;
            quotient = (Math.floor(quotient));
            residue = quotient;
            residue %= 2;
            result.push(residue); //записываем результат целочисленного деления в конец массива
        } while (quotient !== 1);
    }
result.reverse();
    if (number %2 == 0) {
        result.push('0')    
    } else {
        result.push('1')
    }
a = result.join('');
document.write(a)
```

### Work experience:
I don't have work experience.

### Education and courses:
Middle school

### Languages:
   - **Russian** - native speaker
   - **English** - A1 (A2 in process...)


