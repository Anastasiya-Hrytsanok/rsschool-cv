## [rsschool-cv](https://github.com/Anastasiya-Hrytsanok/rsschool-cv/)<br>
# Anastasiya Hrytsanok
### Junior Frontend Developer
<hr>

#### Contact information:
**Phone:** +48789714403<br>
**E-mail:** nastyagritsenok@gmail.com<br>
**Telegram:** @levkart<br>
**[LinkedIn](https://www.linkedin.com/in/anastasiya-hrytsanok-092801221/)**
<hr>

#### My goal:
To gain the necessary experience to hopefully become Front-end Developer.
<hr>

#### Education:
**Faculty of Economics and Management (economist-manager)**<br>
*Belarus State Economic University / Minsk, Belarus<br>
2019*<br><br>
**"Software Testing Introduction" course**<br>
*EPAM Systems Inc. / Minsk, Belarus<br>
2021*<br><br>
**"Front-end (JS + React)" course**<br>
*IT Shatle / Minsk, Belarus<br>
2022*<br>
<hr>

#### Skills:
- HTML5
- CSS3
- SASS
- JavaScript
- React
- Git
- npm
- TypeScript
<hr>

#### Code example:
```let printNumbers = (from, to) => {
    if (from === to) {
        console.log(from);
    } else if (from < to) {
        let plus = () => {
            console.log(from);
            if (from !== to) {
                from = from + 1;
            }
        }
        let timer = setInterval(plus, 1000);
        setTimeout(() => clearInterval(timer), (to - from + 1) * 1000);
    } else if (from > to) {
        let minus = () => {
            console.log(from);
            if (from !== to) {
                from = from - 1;
            }
        }
        let timer = setInterval(minus, 1000);
        setTimeout(() => clearInterval(timer), (from - to + 1) * 1000);
    }
}

printNumbers(2, -10);
```
<hr>