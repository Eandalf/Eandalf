# Eandalf

## Hi There 👋 About Me 👋 Open to Work

Hi, I am Ching-Yu Lin. You could call me Jim. I am a software developer mainly working on JS/TS stack in Taiwan. I develop frontend and backend software, from interfaces for user interactions to API for data retrieval and authentication/authorization, which complies with RESTful design guidelines. I started my journey of coding with JavaScipt. After that, I coded with C, C++, Java, C#, Python, PHP, and JavaScript during my studies at The Hong Kong University of Science and Technology for courses and projects. In my first internship at TECO Electric & Machinery Co., Ltd., I mainly worked on an API service built upon Express.js, which acted as a layer between AGV robots and other services, such as a frontend control panel and third-party services. In my second internship at MVP Fastlane, initially, I worked with a team to help an online hotel booking service from a minimal viable product (MVP) exit the beta phase for a more mature system to accommodate more hotel providers and more users. The service was successfully launched, and its business model proved sustainable and profitable. During a tourism event, the service could scale up for a high volume of incoming requests. Our team monitored the system to ensure the traffic was being properly handled during the event. After releasing the project, I was appointed to develop a chatting app and maintain a tool utility app. The chatting app used SMS OTP for authentication, and the messages were transmitted by using WebSocket with the help of the Socket.IO package. On the other hand, the tool utility app had the login function integrated with the client's Wix-based website for seamless transferring between devices and platforms. Those apps both reached the goal of MVP for the demo and further phases of development. Currently, I am seeking junior positions spanning from frontend to backend development in Taiwan. I am also looking forward to opportunities in other fields of software development, which is not restrained to web-based or app-based developments. Any needed changes in programming language are welcome as long as the company accommodates some time for me to catch on. I developed with PHP and vanilla JS before my second internship. However, the company I worked for during my second internship was using React.js and transforming to a TypeScript-based tech stack. I spent one month being familiar with the environments and toolings and started to keep up with the pace of the team. After three months, I was able to contribute proactively and cover any job that the team needed. I am looking forward to coming back to the software development industry again.

I am currently working on a desktop app, which is called "YouTube Clip Player". The project aims to solve the missing functionality of YouTube to collect clips of videos, curate playlists of clips, and a player dedicated to playing video clips. The project was built with Electron for cross-platform support and to demonstrate my skills in crafting a React.js-based app.

<!--
**Eandalf/Eandalf** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

## Languages and Tools

- JavaScript
- TypeScript
- React.js (Class-based Component & Functional Component)
- Next.js
- NestJS
- React Native
- Electron JS
- Redux.js
- Redux Thunk
- RESTful API
- Socket.io
- WebSocket
- ESLint
- Jest
- Cypress
- CI/CD (using GitHub Actions)
- AWS
  - S3
  - EC2
  - ALB
  - Lambda

## Experience

### Software Engineer

At MVP Fastlane. (Hsinchu, Taiwan. On-site.)

1. Working with the team to migrate the existing code base from JavaScript to TypeScript.
2. Transferring existing functionalities and implementing newly requested features from a React.js SPAstructure to a Next.js SSR structure, to improve loading speed, SEO, and further scalability.
    - Helping [Curators of Travel™](https://curatorstravel.com/) go through phase 2 to phase 3 development.
3. Migrating a backend API from PHP Laravel to NestJS with improved authentication and authorizationmechanisms, under RESTful guidelines.
4. Migrating a CRM system from PHP Laravel based to Next.js based.
5. Setting DNS and CDN.
6. Setting up pipelines for continuous integration and continuous deployment using GitHub Action.
7. Configuring S3, CloudFront, ALB, EC2, and Lambda on AWS.
8. Integrating a Wix-based website with a NestJS-based backend (API).
9. Maintaining existing code base and implementing new features of a mobile app based on ReactNative.
10. Creating a MVP (minimum viable product) with SMS OTP authentication and Socket.IO(WebSocket) using React Native.

### Robot Webpage Art Editor & Database Operation Engineer

At TECO Electric & Machinery Co., Ltd. (Taipei, Taiwan. On-site.)

1. Webpage Interface Design and Development
2. AGV Network Backend Database Setup
    - Based on the existing frontend control panel, implemented the new generation of frontend pages.(Node.js, socket, HTTP request, ES7, jQuery).
    - Built the web API for the backend server (Node.js, Express).
    - Helped organize the documentation for the system.

## Education

### The Hong Kong University of Science and Technology

- Bachelor of Engineering
- Computer Science
- Aug. 2017 ~ May 2021

### Michigan State University

- Exchange Program (Spring 2020)
- Computer Science
- Jan. 2020 ~ May 2020

## Projects

### Curators of Travel™

Jan. 2021 ~ Jun. 2021

WIP...

For more details: [Curators of Travel™](./docs/projects/curators-of-travel/README.md).

### Programming Game (2020-21 FYP YIKE2)

Sep. 2020 ~ Apr. 2021

This project aimed to build a programming game to help teenagers and advanced learners learn Python more interestingly and competitively. We built the game by using Unity and .Net Core 5. For implementing Python language features, we did not take the text recognition approach, which would be specific to each challenge and could not scale well. Instead, we implemented a mini Python interpreter upon C# running on .Net Core 5. It recognized the tokens using Pegasus with the lexical analysis approach. After recognition, the interpreter built the abstract syntax tree (AST) using the information obtained from the tokens, with scoping, data types, and built-in functions taken into consideration and transformed into Node classes in C# to append to the AST. After the interpreter finished creating the AST for the whole code file, the interpreter used its evaluator to go through the tree and execute the statements. Apart from the interpreter, we created challenges and levels to guide the players from the basics of Python, basic data types, and operators, all the way to common built-in functions. To integrate the interpreter with the game built upon Unity, we lowered the .Net version to .Net Framework 3.x for compatibility reasons. To prevent players' buggy code, such as infinite loops, from blocking the main thread of the game, we isolated the interpreter to another thread, while passing the commands to and from the main thread using the producer-consumer pattern. The game created an interesting approach to learning Python with a real interpreter while conquering game levels and challenges.

For more details: [Programming Game](./docs/projects/programming-game/README.md).

### Pixel Inspector

Dec. 2020 ~ Dec. 2020

The project aimed to read the RGB or RGBA pixel values of the images locally. GUI was built with Tkinter. Matplotlib was used to load images. Numpy was used to manipulate arrays of pixel values. After setting up this project, we no longer needed to upload pictures to online services to inspect pixel values, which was commonly used in scientific research.

[Repo](https://github.com/Eandalf/pixel-inspector)

### 2048 Game

Nov. 2020 ~ Nov. 2020

WIP...

[Repo](https://github.com/Eandalf/2048_game)

### Genetic Programming for a Binary Classification Problem

Nov. 2020 ~ Nov. 2020

This piece of work was originally created for COMP3211 Fundamentals of Artificial Intelligence Assignment1 Problem3 at HKUST in 2020 Fall. The script demonstrated how to set up a training based on the genetic programming paradigm. To perform the binary classification, the perceptron structure was set up to have weights to be tuned to fit the data. Basically, the population of this GP, genetic programming, consists of 1000 instances of perceptrons (weight vectors).

[Repo](https://github.com/Eandalf/gp_bc)

### COVID-19 Named Entity Recognition

Oct. 2020 ~ Dec. 2020

This was a course project from COMP4901K Machine Learning for Natural Language Processing at HKUST. It aimed to find and train a model to perform the NER labeling task for a COVID-19 related corpus. After testing with simple NNs and several kinds of RNNs, a bi-directional GRU network with a preceding embedding layer, which had a relatively huge dimension, was chosen to conduct the NER task. The resulting accuracy on the validation set was around 0.9049.

For more details: [COVID-19 Named Entity Recognition](./docs//projects/covid19-named-entity-recognition/README.md).

### Who Murdered My Grade? II

Mar. 2020 ~ Apr. 2020

This was a course project from CSE477 Web Application Development at MSU, and it was the extension of the previous project "Who Murdered My Grade? I". The work devoted to it was to enable the system to handle multiple players to play in a game with their own devices, which were connected to the remote server, and to handle multiple rooms to have multiple groups of players playing the game at the same time. We built the login control to have users create their own account, verify it, and log in to the account. We also built the game-room system to provide users with the lobby, waiting room, and gaming room. Furthermore, we adopted Ratchet for having WebSockets to push notifications to players in the same room after any changes made.

For more details: [Who Murdered My Grade? II](./docs/projects/who-murdered-my-grade-ii/README.md).

### Who Murdered My Grade? I

Feb. 2020 ~ Mar. 2020

This was a course project from CSE477 Web Application Development at MSU. We utilized PHP7.0 for building this single page board game, which could be played by multiple players on a rotating basis. MVC (Model-View-Controller) pattern was used to reduce the complexity of the program and help distribute the workload to team members. And, PHPUnit was used for unit testing. The project was developed under scrum project management.

For more details: [Who Murdered My Grade? I](./docs/projects/who-murdered-my-grade-i/README.md).

### Array Database and Security (UROP 2019 Fall)

Feb. 2019 ~ Dec. 2019

This project aimed to research and analyze existing array databases, security issues among DBMS, and possible implementations for a secured array database. Spark, SciSpark, SparkArray, H5Spark, SparkSQL, and Opaque (a database based on SparkSQL with the protection of oblivious data operations) were surveyed in this project. After observing these existing systems, a secured array database was proposed in the report of this UROP (Undergraduate Research Opportunity Program) project. The proposed secured array database would be based on SciSpark with the tile as the basic storage unit. At the same time, queries would be processed by the secured enclave (Intel SGX) and oblivious operations supported in Opaque. Although the overhead to perform these secured computations was considerably huge, the secured array database still provided extraordinary protection to the data. If there was a scenario that huge array-like data required strong protection, the high overhead might be acceptable.

For more details: [Array Database and Security](./docs/projects/array-database-and-security/README.md).

### Tower Defense

Sep. 2019 ~ Dec. 2019

This was a course project from COMP3111H Honors Software Engineering at HKUST. We built an interesting window game called Tower Defense which reproduced the popular game genre as it was named. It was built with Java, and we utilized JavaFX for GUI, Timer class (java.util.Timer) for defining and changing the time frame of the game flow, Hibernate for persistence (JPA, data storage) toward MySQL database, and Spring Boot for the remote server service. We also utilized JUnit for unit testing.

For more details: [Tower Defense](./docs/projects/tower-defense/README.md).

## Stats

![Profile views](https://komarev.com/ghpvc/?username=Eandalf)

[![GitHub Streak](https://streak-stats.demolab.com/?user=Eandalf)](https://git.io/streak-stats)

![Eandalf's github stats](https://github-readme-stats.vercel.app/api?username=Eandalf&count_private=true&show_icons=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Eandalf&langs_count=10&layout=compact)
