# Anna Mandrik

![My photo](https://avatars.githubusercontent.com/u/112107622)

## Frontend Developer

---
## Contact info:

* E-mail: ya@amandrik.ru
* Phone: +7(906)266-41-67
* LinkedIn: Anna Mandrik
* Telegram: @AnnaMandrik
* Discord: anna_mandrik
* GitHab: [AnnaMandrik](https://github.com/AnnaMandrik)

---
## About me:

I have worked for a long time as an analyst in various fields and as an import logistician. Until three years ago I began to study website layout and programming in js - and since then I have been engaged only in programming. A lot of courses, work as an intern (for more than a year), custom projects and test projects - gives a lot of practice. I can't turn off this road and continue to delve into various aspects of website and application programming.

---
## Courses:

* HTML & CSS. Adaptive layout and automation html academy (interactive online courses)
	Mart - May 2022
	[Certificate](https://assets.htmlacademy.ru/certificates/intensive/265/95434.pdf)

* React Developer Profession html academy (interactive online courses)
  April - November 2021
	[Certificate](https://assets.htmlacademy.ru/certificates/profession/29/95434.pdf)

---
## Skills:

* HTML5 
* CSS3 
* JavaScript 
* React/Redux 
* TypeScript
* Template processor (Pug) 
* Preprocessing (Sass, Less, Scss) 
* BEM 
* Responsive Web Design 
* Git
* Gulp, Webpack 

---
## Projects:

* [Big trip](https://github.com/AnnaMandrik/95434-big-trip-15)
* [Six Cities](https://github.com/AnnaMandrik/95434-six-cities-8)
* [Guitar shop](https://github.com/AnnaMandrik/accelerator-react-starter-pack)
* [Cat Energy](https://github.com/AnnaMandrik/95434-cat-energy-25)
* [LOGO](https://github.com/AnnMandrik/LOGO)

## Code example:

First function for returning a random integer from a given range.
The second function is to return an array of values of random length and the values should not be repeated.
These functions were used to generate mocks data in one of the projects.

```
function getRandomIntInclusive (firstNumber, secondNumber) {
  firstNumber = Math.ceil(firstNumber);
  secondNumber = Math.floor(secondNumber);
  if (firstNumber >= 0 && secondNumber >= 0) {
    return Math.floor(Math.random() * (secondNumber - firstNumber + 1)) + firstNumber;
  } else if (secondNumber <= firstNumber) {
    return Math.floor(Math.random() * (firstNumber - secondNumber + 1)) + secondNumber;
  }
}

function findElems(anyNamedArray, counter) {
  const newArray = [];
  for (let index = 0; index < counter; index++) {
    // find random number
    const newElemIndex = getRandomIntInclusive(0, anyNamedArray.length - 1);

    // find element by this ordinal number
    const newElem = anyNamedArray[newElemIndex];

    // compare with yourself
    let povtoryBykv = [];

    // fill array all found repeats
    povtoryBykv = newArray.filter((item) => {
      if (item === newElem) {
        return item = newElem;
      }
    });

    // check the number of repetitions (no repetitions is 0)
    const thisElemExist = povtoryBykv.length;

    if (!thisElemExist) {
      newArray.push(newElem);
    }
  }
  return newArray;
}

```

## Languages:

* Russian: native
* English: intermediate