# OOP Labs 2023

> The main goal of this course is to give you some basic understanding of what the OOP paradigm is and how it’s applied in the real life.
> 

After finishing these 3 works you will have a working application which can be presented as your final project (work 4) for this course. It would be nice if you have your own ideas, discuss them with me and we will find a proper way to make it happen =)

Here are some examples of what you can do:

1. Managing tools, like [Trello](https://trello.com/en)
2. Bank system
3. Flash-card application, [Anki](https://apps.ankiweb.net)
4. Time-management app, [ToDoist](https://todoist.com)
5. Music or video players, [Spotify](https://www.spotify.com/by-ru/), [YouTube](https://www.youtube.com) 
6. Messangers, [Telegram](https://telegram.org), [FaceTime](https://support.apple.com/en-us/HT204380)
7. Any kind of a game with the rich environment.
8. Calendars, like [Google Calendar](https://calendar.google.com/calendar/u/0/r?pli=1)
9. Productivity app, [Forest](https://www.forestapp.cc)

NOTE: YOU CAN’T CHANGE YOUR TOPIC AFTER I ACCEPT IT!!!

## Work №1 "Design"

To accomplish this work you need to define functional requirements for the application you are going to develop. You should split your future system into logical components and provide a description for each item.

Acceptance criteria:

1. GitHub repo is required.
2. Read.me file is required with the following information:
    1. Description of ur project.
    2. **YOUR NAME AND GROUP NUMBER**
    3. Link, photo or attachment of your system’s class diagram (it could be clarified later, the main purpose of it to provide an overview how your system’s architecture).
    4. List of functions of your application. Each function should be described in details.
    5. Description of data models.

You can use apps like: [draw.io](https://app.diagrams.net), [miro](https://miro.com/login/) or just pen & a piece of paper to create diagrams and schemas.

## Work №2 "Application skeleton"

Starting from this moment the latest version of your application should be upload to git within corresponding [PR](https://about.gitlab.com/topics/version-control/what-is-git-workflow/).

To accomplish this work you need to bring your all your schemas and diagrams to life. For now you only need to implement the main functionality. You don’t need to implement deserialization/serialization. All data can bestored in local constants for now.

Acceptance criteria:

1. GitHub repo is required.
2. PR into the main branch is required. 
3. Frameworks (Django, Flask, ROR, etc) are **NOT** allowed.
4. Your code should have a module structure.
5. Layered architecture is required.
6. Theoretical knowledge of the basics OOP concepts: class, class entity, polymorphism, inheritance, encapsulation, composition etc.

## Work №3 "Deserialization&Serialization&Plugins"

It’s time to add some data independency to your application! For this work I’m asking you to integrate deserialization/serialization modules to your application.  

To accomplish this work you need to implement a serialization and deserialization for such formats as .json/.xml/bin/custom text (with custom parser) **(pick two)**. Serializator and deserializator should be developed as an independent plugin and be connected to your project as .dll (for C#), .jar (for Java), npm utility (for JS), pip utility (for Python) etc. The data could be stored in a local file for now.

Acceptance criteria:

1. 2 GitHub repos are required (one for lib and the other one for your project).
2. 2 PR into the main branches are required (one for lib and the other one for your project). 
3. Frameworks (Django, Flask, ROR, etc) are still **NOT** allowed.
4. Created libraries should be used in your project.

## Work №4 "AKA ur final project"

This work will be counted as your final project (course work) for the OOP module. Here we will add a lil’ good ol’ razzle-dazzle to your application – connect it to the storage. 

To accomplish this work you need to integrate your application with a NoSQL database or a cloud file storage (Firebase, AmazonS3, DynamoDB, MongoDB, Google Drive, Redis etc.). So from this moment all your data should be stored far away from your code, and can be dynamically uploaded and managed.

Acceptance criteria:

1. GitHub repo is required.
2. PR into the main branches is required. 
3. Guess what? Frameworks (Django, Flask, ROR, etc) are still **NOT** allowed.
4. Layered architecture is required.
5. Theoretical knowledge of the SOLID principals are required.
6. Report for the final work are required:
    1. Report should be formatted regarding the [Final Project’s requirements](https://www.bsuir.by/m/12_100229_1_122704.pdf).
