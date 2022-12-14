# Nick Sidorenko

### Front-End Developer

---

## Contact

- **Location:** [Krasnodar, Krasnodar Region, Russia](https://goo.gl/maps/Q5URPwZ4SCZVZhuN7)
- **Phone:** [+7 (928) 271-60-94](tel:+79282716094)
- **E-mail:** [gsidnick@gmail.com](mailto:gsidnick@gmail.com)
- **Discord:** [gsidnick#8382](https://discordapp.com/users/910837119314952202/)
- **Telegram** [@gsidnick](https://t.me/gsidnick)

## About Me

I am a passionate Front-End developer from Krasnodar, Russia. I like to develop
useful, convenient and attractive web applications for people.

I am interested in a wide range of knowledge, ranging from UX/UI to frontend
and backend. I am also developing my design skills to create harmonious and
modern user interfaces. Thus, I am interested in creating an application at all
stages of its development - creating a design project in Figma, developing
a layout using HTML and CSS (including the SCSS pre-processor), implementing
frontend functionality in JavaScript, developing a backend on Node.JS .
In addition, I use Webpack for production builds of the project, as well as
the Git version control system. At the moment, I am undergoing TypeScript
training in order to further migrate my projects to this strictly typed
programming language.

Using JavaScript as an elegant language for client-side and server-side
development, I'm getting deeper and deeper into the programming process.
Therefore, I am proud to say that the level of my knowledge at the moment
is the result of my many years of self-education from scratch.

## Education

### Front-End Developer

December, 2022 - Present

**Rolling Scopes School, JS/FE Pre-School 2022Q4**

### Specialist of Computer Scientist & Economist

September, 2010 - February, 2014

**Armavir State Pedagogical University (ASPU), Armavir, Russia**

### Operator of Electronic Computing and Computing Machines

September, 2006 - April, 2010

**Armavir Engineering College (AEC), Armavir, Russia**

## Experience

### Electronics Engineer

August, 2012 - Present

**Gazprom UGS LLC**

### Leading Specialist Programmer

February, 2011 - August, 2012

**Rural Government**

## Skills

- **Hard Skills**
    - HTML (100%)
    - CSS / SCSS / BEM (90%)
    - JavaScript (85%)
    - TypeScript (50%)
    - Node.JS (50%)
    - Git (70%)
    - Adobe Photoshop (80%)
    - Adobe Illustrator (80%)
    - Figma (80%)
    - Webpack (60%)
    - Russian (Native)
    - English (A2)
- **Soft Skills**
    - Responsibility
    - Dependability
    - Adaptability
    - Learnability
    - Creativity
    - Teamwork
    - Communication
    - Problem-solving

## Code

### Kata Description

[Take a Ten Minutes Walk](https://www.codewars.com/kata/54da539698b8a2ad76000228)

### Kata Solution
```javascript
function isValidWalk(walk) {
  let sum = 0;

  if (walk.length !== 10) return false;

  let n = walk.filter((elem) => elem === 'n').length;
  let w = walk.filter((elem) => elem === 'w').length;
  let s = walk.filter((elem) => elem === 's').length;
  let e = walk.filter((elem) => elem === 'e').length;

  if (n !== s || w !== e) return false;

  walk.forEach((elem) => {
    (elem === 'n' || elem === 'w') ? sum += 1 : sum -= 1;
  });

  if (sum === 0) return true;

  return false;
}
```