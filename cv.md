## Manzura Jabbarova

##### Junior Frontend Developer

---

##### Contact information:

**Phone number**: +998886005558

**E-mail**: manzura_jabborova@mail.ru

**Telegram**: @maria

**[LinkedIn](http://linkedin.com/in/manzura-jabbarova-19066712a)**

---

### Briefly about myself:

Having started my career as a frontend developer with minimum skills, I became passioned in coding.
My keen interest in learning new technologies led me to learn and
posses some skills in IT learning center to create a new career path for myself in IT world where I continued self-learning, examining the process of creating websites and their designs and others.
I’m interested in Web Development because this occupation provides endless possibilities for professional growth,
besides there’s a huge amount of free high quality resources for self-education and a large community of developers.
I believe, that my ability to learn and to gain new skills will lead me through this path of becoming a proficient Frontend Developer.
Nowadays I am attending in an Internship in one of the IT startup company in my hometown

#### **Skills and Proficiency:**

- HTML5, CSS3, SASS, SCSS

- JavaScript Basics

- React js

- Next js

- Git, GitHub

- VS Code

#### **Code example:**

> There is a given array with objects in it with id and parent number, we should first open new children key in an object with empty array and if object parent number matches other object's id, that should be nested in children array of that matched object
>
    const sortMenu = (arr) => {
    arr.sort((a, b) => a.parent - b.parent);
    let newArr = [];
    for (let i = 0; i < arr.length; i++) {
    let parent = arr[i];
    if (newArr.length === 0) {
    newArr.push({ ...parent, children: [] });
    } else {
    let length = newArr.length;
    let index = -1;
    for (let j = 0; j < length; j++) {
    if (newArr[j].id === parent.parent) {
    index = j;
    }
    }
      index === -1
        ? newArr.push({ ...parent, children: [] })
        : newArr[index].children.push(parent);
    } }
    return newArr;
    };

***

#### **Experience**
I have not got enough experience yet as I am still learning and gaining experience as a frontend developer attending in internship. Below is some examples of my projects

***[my-first-work](https://radiant-torrone-e4a082.netlify.app)***

***[tejamkor](https://tejamkor-manzura94.vercel.app/)***

***[codebrain](https://codebrain-front.vercel.app/)***


#### **Education**

* Management Development Institute in Tashkent, Business and Economics faculty

* Data Learning Center in Xorezm, Frontend developer faculty

* University of Messina in Italy, Master degree at Business Consulting and Management

#### **English**
IELTS 6.5

Besides Ielts, I have graduated my bachelor degree in english language and taking my master degree in english as well.