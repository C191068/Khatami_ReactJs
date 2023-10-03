# Khatami_ReactJs(learning from freecodecamp)

### Introduction

![image](https://github.com/C191068/Khatami_ReactJs/assets/89090776/7f49f8fe-e422-4d1a-94c3-874dcc507e92)

We are going to develop our application using the above IDE Replit <br>

Replit is a popular collaborative in browser IDE where we are able to code in 50+ languages <br>

withot spending much time in setup <br>

to begin we need to setup a free account with replit <br>

![image](https://github.com/C191068/Khatami_ReactJs/assets/89090776/d2dee03f-44d4-47ff-a5cf-2208bba48482)

we wil sign up with google 


React is a front end javascript framework and is a javascript library created by Facebook <br>

react is a tool for building UI user interface components <br>

REACT creates a virtual DOM( Document Object Model) in memeory <br>

REACT is very fast , REACT finds what changes have been made <br>
and changes only what needed to be changed <br>


Now we will create a REPL for our REACT application <br>

![n10](https://github.com/C191068/Khatami_ReactJs/assets/89090776/1d3ede2e-1aaf-4e13-9d99-d046def607ec)

for that we need to click here <br>

![n11](https://github.com/C191068/Khatami_ReactJs/assets/89090776/ef26566c-bd66-4514-822e-1dc43490819a)

here we can see a number of programming languages and developer platform we can choose from <br>

![n12](https://github.com/C191068/Khatami_ReactJs/assets/89090776/3aa95e1f-182b-4152-80fa-b40675bad4fa)

here we gonna select the above <br>


![n13](https://github.com/C191068/Khatami_ReactJs/assets/89090776/eed08498-112d-4f3a-a0c2-47cd9f1e7353)

then we will click ```Create Repl``` button <br>

![n14](https://github.com/C191068/Khatami_ReactJs/assets/89090776/038832c8-4658-4f76-9b83-2081aeae77bc)

we will click the above run button <br>


```

import './App.css'

export default function App() {
  return (
    <main>
      Assalamualikum World !!!
    </main>
  )
}


```



the above code gives the following output <br>

![n15](https://github.com/C191068/Khatami_ReactJs/assets/89090776/8dee34c3-e392-4002-ba1f-aa878f6e1f9c)

![n16](https://github.com/C191068/Khatami_ReactJs/assets/89090776/4a20e4da-b531-4773-9334-bc60e24552ac)

here in the above we will click the icon shown with white arrrow <br>


![image](https://github.com/C191068/Khatami_ReactJs/assets/89090776/b008c937-5770-4d89-bbcc-a34e9a51b6f9)

then tha above fullscreen will appear <br>

We also gonna use bootstrap 5 for layout and styling purposes <br>

![n17](https://github.com/C191068/Khatami_ReactJs/assets/89090776/9107e4de-962f-4dc5-b5f9-638d7e73f708)

we have changed the css like the baove <br>


Now we will create three UI components using REACT <br>

These UI components are expessed in jsx files <br>


![n18](https://github.com/C191068/Khatami_ReactJs/assets/89090776/76940101-819f-4a14-a3fa-07700f9330b7)

we have created a new jsx file <br>


![n20](https://github.com/C191068/Khatami_ReactJs/assets/89090776/bfe8873a-cd12-491f-835d-3e1787104e2a)

we have created another jsx file <br>

![n21](https://github.com/C191068/Khatami_ReactJs/assets/89090776/ea64d641-5b5d-42fa-ace3-be42144938b7)

another jsx file we also created <br>

the react application that gonna be developed will use functional components rather than class components <br>

source : https://legacy.reactjs.org/docs/components-and-props.html



We will represent our functional components using javscript arrow function <br>

javascript arrow function : https://www.freecodecamp.org/news/javascripts-arrow-functions-explained-by-going-down-a-slide-2eb8ee3c45e/

```
const Header = () => {
  return(
    <header>
      <h1>TeamName</h1>
    </header>
  )
}
export default Header

```


the above is the code for header <br>

we are now able to reference the header component in our application declaratively <br>

by appropriately including header elemnt at App.jsx file <br>

```
import * as React from 'react';
import './App.css';
import Header from './Header';

export default function App() {
  return (
    <div>
     <Header />
    </div>
  )
}


```


the above code will give the following output <br>


![image](https://github.com/C191068/Khatami_ReactJs/assets/89090776/96a450fa-84bf-40a0-8521-28b8afdb6585)


![n22](https://github.com/C191068/Khatami_ReactJs/assets/89090776/5a537361-16f2-4734-adc7-af9fd119afb7)
In our index.html we have div element with id equal to root <br>


![n23](https://github.com/C191068/Khatami_ReactJs/assets/89090776/bd8bf17e-05fc-409a-a393-957a2e8bc886)

we also have references to index.html file <br>

![n25](https://github.com/C191068/Khatami_ReactJs/assets/89090776/bed48c0c-e579-43c4-8bef-87df33a5dda5)


at index.jsx file here it is referencing to the root element <br>

![n26](https://github.com/C191068/Khatami_ReactJs/assets/89090776/bab3b01b-69c1-4c8f-b83c-f443ea2ed546)

here we can see that render function is being called to render the app component within the root element <br>
























