# rsschool-cv

---

## Sergey Lashin

---

### Contact Information

__Address:__ 23 Dobrolybova, Ust-Kamenogorsk, 070018
__Email:__ heavyra1n4222@gmail.com
__Phone:__ +7 707 6714360, +7 913 0876611

### Brief description:

Geomechanical engineer with 4 years of experience and a university degree in mining, who is looking for new challenges, and wants to try his hand in a new industry. Lived and worked in Kazakhstan and Russia.

Front-end development and web design interested me because I really like beautiful, well-made things, and I have several front-end developer friends who are very supportive of me. As a schoolboy I attended an art school in my hometown, so I have always had an interest in the visual side of things since I was a kid.

### Education:

__2016 - 2020__ *D. Serikbayev East Kazakhstan technical university*, bachelor's degree.

### Skills:

* HTML5, CSS3, Markdown basics;
* Bootstrap4 framework;
* JavaScript basics;
* Git, GitHub;
* VS Code.

### Code example:
__Training JS: methods of arrayObject---push(), pop(), shift() and unshift(). Kata from CODEWARS:__

Coding in function infiniteLoop. function accept 3 parameters. The 1st parameter is arr, it's a 2D array, it contains three 1D array. The 2nd parameter is d ，it's a string. The 3rd parameter is n, it's a number.

You can think of arr as a moat, the elements of arr like water constantly flow in. The direction of flow is controlled by the parameter d. The value of d can be "left" or "right". "left" means the "river" moves to the left. All elements in the 1D array are to the left moving n position, if beyond the bounds of the array and the element is moved to the tail on the left side of the array; if it exceeds the left boundary element would be moved to the tail of 3rd array(like a circle). Right is also similar to the operation, but it is moving to the right.

Finally, return arr.

__My solution:__
```
function infiniteLoop(arr, d, n) {
    for (let i = 0; i < n; i++) {
        if (d === "left") {
            let firstElement = arr[0].shift();
            
            arr[2].push(firstElement);
            
            firstElement = arr[1].shift();
            arr[0].push(firstElement);
            
            firstElement = arr[2].shift();
            arr[1].push(firstElement);
        } else if (d === "right") {
            let lastElement = arr[2].pop();
            
            arr[0].unshift(lastElement);
            
            lastElement = arr[1].pop();
            arr[2].unshift(lastElement);
            
            lastElement = arr[0].pop();
            arr[1].unshift(lastElement);
        }
    }
    return arr;
}
```

### Courses:

* HTML and CSS сourse for beginner Web Developers on [stepik](https://stepik.org/course/38218/syllabus "course on stepik").(completed - [certificate](https://stepik.org/cert/2557178?lang=en
));
* JavaScript Manual on [*learnjavascript.ru*](https://learn.javascript.ru/) (in progress)
* RS School Course «JavaScript/Front-end. Stage 1» (in progress)

### Work Experience.

I have two pages laid out as part of a course for beginner web developers on [stepik](https://stepik.org/course/38218/syllabus "course on stepik"):

* [Pied-Piper project](https://github.com/Sergey-Lashin/Pied-Piper-project.git);
* [Bootstrap project](https://github.com/Sergey-Lashin/Bootstrap-project.git).

### Languages:

* Russian - Native;
* English - A2 (pre-intermediate, took English courses while studying at the University.);
* Kazakh - A2;