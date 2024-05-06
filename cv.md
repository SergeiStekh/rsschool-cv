## Sergey Stekh

## Frontend developer

## Contact information:

**Phone:** *+48 512 964 497*

**Email:** *sergei.stekh@gmail.com*

**Telegram:** *@Sergei_Stekh*

---

## Briefly About Myself:

I'm a frontend engineer with 5 years experience.

My journey commenced with the creation of an educational SaaS from scratch, where I served as both a product owner and a front-end developer. I was responsible for designing the application's architecture and business logic. I executed various user flows, such as authentication, authorization, and front-end interactions with APIs, including third-party payment services and social network chatbots. This project successfully launched and has positively impacted hundreds of individuals.

Furthermore, I engaged in freelance work as a front-end developer, contributing my expertise to diverse projects, spanning e-commerce and startups.

Presently, I am a software engineer on a project centered around Salesforce Commerce and JavaScript. This project caters to the needs of the UK's largest retailer of motoring and cycling products and services.

During my leisure time, I take on the role of a front-end mentor. In this capacity, I motivate, inspire, and provide support to individuals who are learning JavaScript and React.

For me, coding is a way of life that embodies continuous learning and self-development. I am perpetually in pursuit of methods to enhance code readability, efficiency, and clarity. I adhere to best practices in accessibility, semantic markup, and content separation.

The emergence of web applications from abstract ideas is a remarkable source of inspiration. I aspire to persist in crafting valuable and practical web applications that contribute to simplifying people's lives.

---

## Skills:

- HTML5; 
- CSS3;
- Bootstrap;
- JavaScript;
- React, Redux;
- Computer science fundamentals;
- Communication Protocols;
- Git;
- Webpack basics, GULP;
- Basic PHP;
- Vs Code;
- Figma.

## Soft Skills: 

- Able to work effectively under supervision;
- Ability to read, understand and clarify (if needed) task requirements;
- Able to explain thoughts in English;
- Able to present results of work to teammates;
- Understands when advice is needed, able to involve other team members in case of problems;
- Able to plan work time (Self-management, Time-management).

---

## Code example: 

```
import React from "react"
import "./ModulesList.css"

export default function ModulesList({state, modules, setState}) {
  
  function changeModule(e, newModule) {
    e.preventDefault();
    setState((prevState) => {
        return {
            ...prevState,
            previousModule: prevState.currentModule,
            currentModule: newModule[0],
            currentModuleName: newModule[1],
            currentSubModule: "All questions",
            data: {
              ...prevState.data,
              currentQuestionId: null,
              isQuestionOpen: false,
              questionData: null,
              questionsToShow: 15
            },
            search: {
              ...prevState.search,
              isSearching: false,
              searchString: "",
              foundQuestions: null
            },
            showCategories: false,
            testState: {
              isShowingTest: false
            }
        }
    })
  }

  return (
    <>
    <h2 className="modules-wrapper">Topics:</h2>
    <div className="modules-list">
      {modules.map((module, idx, arr) => {
        const active = module[0] === state.currentModule;

        return <div key={idx} className={active ? "single-module active" : "single-module"} onClick={(e) => changeModule(e, module)}>{module[1]}</div>
      })}
    </div>
    </>
  )
}
```

---

## Experience

- [Polish language school (HTML, CSS, JS, React, PHP)](https://polaka.pl); [Language test example](https://polaka.pl/polaka-free/?render=test&lessonId=1); [Grammar test example](https://polaka.pl/polaka-free/?render=grammar&lessonId=2); [Drag&Drop Example](https://polaka.pl/polaka-free?render=spriazenie&lessonId=2); [Learning words example](https://polaka.pl/polaka-free?render=new_words&lessonId=3);

- [SongBird Game (HTML, CSS, React + Redux)](https://song-bird-portfolio.netlify.app/); [Source code](https://github.com/SergeyCodeJs/song-bird-portfolio);

- [Quiz for KiwiTaxi international service (HTML + CSS)](https://kiwitaxiquiz.netlify.app/); [Source code](https://github.com/SergeyCodeJs/kiwitaxiQuiz);
- [Expo Forum (HTML, CSS)](https://expoforum.netlify.app/);

---

## Education:

- **June 2019 - September 2019** - HTMLAcademy HTML and CSS course;

- **October 2019 - November 2019** - Codecademy: learn HTML; learn CSS; learn JavaScript; building interactive JavaScript sites.

- **September 2019 - April 2020** - Rolling scopes school (RS 2019 Q3);

- **February 2020 - April 2020** - Udemy, "React JS – from beginner to professional";

- **April 2020 - June 2020** - Udemy, "Practical JavaScript (advanced level)";

- **June 2020 - August 2020** - Udemy, "React + Redux – Professional development".

---

## Languages:

- English - Intermediate/Upper-intermediate;

- Polish.
