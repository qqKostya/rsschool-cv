# Konstantin Kazakov
---
# My Contact Info

* **Phone:** +7(999)212-89-12
* **E-mail:** [leap74rus@gmail.com](leap74rus@gmail.com)
* **LinkedIn:** [konstantin-kazakov](https://www.linkedin.com/in/konstantin-kazakov-277b3b231/)
* **GitHub:** [qqKostya](https://github.com/qqKostya)
* **Telegram:** [@kazakovqq](https://t.me/kazakovqq)
---
### About me 
Tell us about yourself. I have now quit my job to dedicate my full time to teaching. I study on my own, from time to time, consulting with a mentor.

I have taken many free courses, the full list can be found here: https://qqkostya.github.io/. Also, I implemented several of my own pet projects, they can be found on github: https://github.com/qqKostya

I chose Python as my main first stack, but now I decided to learn front-end.

In addition, I have experience with Docker and Docker Compose, deploying databases (PostgreSQL) and raising servers, deploying projects on Heroku and working with REST API.

Now I continue to actively develop in the field of web development. Every day I watch thematic YouTube channels, read portals and telegram channels, and of course, I take further courses.

---

## Skills
Hard skills:
- basic HTML;
- Vanilla CSS
- Vanilla JS
- GIT;
- Linux;
- Docker;
- Python (django, flask, fastapi, drf)
- Databases (MySQL, PostgreSQL).

Soft skills:
- experience of working in a team (was a Team Leader of the Buying Department in an advertising agency https://www.adskillgroup.com/;
- resistance to stress (constantly communicated with advertisers);
- communication skills (held a large number of rallies with leaders, subordinates and other departments);
- love for learning and learning new things (during training I tried and try different languages, on some I do mini pet-projects);
- viewing in IT (I constantly watch thematic Youtube channels, and also read portals and telegram channels);
- I try to bring everything to the end, if it is expedient.

---

## Code Example 
Burger menu script
```
(function () {
  const burgerItem = document.querySelector('.burger');
  const menu = document.querySelector('.header__nav');
  const menuCloseItem = document.querySelector('.header__nav-close');
	const menuLinks = document.querySelectorAll('.header__link');

  burgerItem.addEventListener('click', () => {
    menu.classList.add('header__nav_active');
  })
  menuCloseItem.addEventListener('click', () =>  {
    menu.classList.remove('header__nav_active');
  })

	if (window.innerWidth <= 767) {
		for (let i = 0; i < menuLinks.length; i++) {
			menuLinks[i].addEventListener('click', () => {
				menu.classList.remove('header__nav_active');
			})
		}
	}
  
}());
```

---

## Education 
- __College:__ Chelyabinsk Metallurgical College, operation and maintenance of electrical and electromechanical equipment
- __Institute:__ South Ural Institute of Management and Economics, manager in electrical engineering and energy
- __Courses:__
  - [Hexlet: Command Line Basics](https://ru.hexlet.io/u/qqkostya/courses)
  - [Hexlet "Introduction to Git"](https://ru.hexlet.io/u/qqkostya/courses)
  - [HTML Academy: HTML, CSS, JS trainers](https://htmlacademy.ru/profile/id2052549)
  - [Developer Resources, From Developers: HTML, CSS, JS, Django (Mozilla)](https://developer.mozilla.org/ru/docs/Learn)
  - [Hexlet "Python: Programming Fundamentals"](https://ru.hexlet.io/u/qqkostya/courses)
  - [Stepik: “Generation Python. Course for beginners»](https://stepik.org/cert/1533262)
  - [Stepik: “Generation Python. Advanced Course»](https://stepik.org/cert/1558650)
  - [Ruby course from RubyRush](https://rubyrush.ru/steps)
  - [Udemy "Python + Django: from scratch to commercial applications"](https://www.udemy.com/course/python-django-app/)
  - [Udemy "Django 3 - Full Stack Python Website Development"](https://www.udemy.com/course/django-3-full-stack-python/)
  - [CS50 (Harvard, Fundamentals of Programming, Fall 2015)](https://www.youtube.com/watch?v=fH92Dq7jO90&list=PLawfWYMUziZqyUL5QDLVbe3j5BKWj42E5&index=7&ab_channel=JavaRush)
  - RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)

---