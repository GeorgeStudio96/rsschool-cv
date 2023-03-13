# George Ershov

## Junior Software Engineer


## Contact information:
**Phone:** +7-929-654-35-22  
**Email:** geo.erh96@gmail.com  
**Telegram:** @GeorgeEA


## About Myself:

I started my career in web development with a low-code platform - Webflow. This amazing technology showed me the wonderful world of frontend development on the World Wide Web. 
At first I worked as a freelancer, and then I got a job at Pinkman design studio, where I worked for a long time. 
At the moment I'm a Senior Webflow Developer and I managed to work with many big Russian companies, European startups and others. On my account I have more than 60 beautiful sites with great animation daily benefiting my clients. 

However, any low-code platform is used only for creating MVPs and is not suitable for scaling when the business needs it and has its own limitations in technology. That is why I decided to find my new way exactly in JavaScript development. 


## My skills: 

* Webflow, Figma
* Wordpress
* Directual
* HTML5, CSS3
* JavaScript Basic, Jquery Basic
* GSAP Animation
* Git, GitHub, VScode


## Code Example:

Task: if a string has one non-closing parenthesis, print false, if each opening parenthesis has a closing parenthesis, then print true

```
const string = "{[()]}"

const isValid = (str) => {

    // ищем скобки в стеке, если же стек пустой, то нет лишних скобок без своей пары

    const stack = []
    const obj = {
        '{': '}',
        '(': ')',
        '[': ']',
    }

    for (let i = 0; i < str.length; i++) {
        let bracket = str[i]

        if (bracket === '{' || bracket === '[' || bracket === '(') {
            stack.push(bracket);
        } else {
            const lastElem = stack.pop();
            if (obj[lastElem] !== bracket) {
                return false

            }
        }

    }

    return !stack.length
}

```


## My Work:

Total experience as a developer, more than 3.5 years
Due to the NDA contract I am not allowed to show many projects, however, I can show some. 

https://discovery.yachty.co

https://www.rentateam.ru/en

https://whitelabelpr.com


## Courses: 

Glo-academy: https://glo-academy.ru/jscript/


## Languages:

**Russian** — Native
**English** - A2 Pre-Intermediate