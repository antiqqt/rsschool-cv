# Anton Pomogaev

## Contact information
* ***Phone:*** 8 (911) 812-00-69
* ***Email:*** antonpomogaev@gmail.com
* ***GitHub:*** [antiqqt](https://github.com/antiqqt)
* ***Telegram:*** [antiqqz](https://t.me/antiqqz)
* ***RS School discord:*** Anton Pomogaev (@antiqqt)

## Skills
* HTML/CSS
* Javascript
* Git
* Figma
* C, Python *(basic knowledge)*

## Education
* ***Saint Petersburg State University***
    * International Relations major
* ***Online Courses***
    * HTML/CSS/JS tutorials on [w3schools.com](https://www.w3schools.com/)
    * JS Manual on [javascript.info](https://javascript.info/)
    * CS50's Introduction to Computer Science on [edX](https://cs50.harvard.edu/x/2021/) (2021)

## Languages
* ***English*** - Upper-intermediate/Advanced (B2 Certificate)
* ***French*** - Intermediate
* ***Russian*** - Native

## Code example

The code below solves this interesting [kata](https://www.codewars.com/kata/559a28007caad2ac4e000083/javascrip)(problem) from [CodeWars](https://www.codewars.com/)

```
function perimeter(n) {
    return 4 * fib(n);
}
    
function fib(n) {
  let [a, b] = [0, 1];
  let temp = [];
  for (let i = 0; i < n + 1; i++) {
    b = a + b; 
    a = b - a;
    temp.push(a);
  }
  return temp.reduce((acc, v) => acc + v);
}
```