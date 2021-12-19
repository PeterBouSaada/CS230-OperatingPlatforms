# The Gaming Room

The Gaming Room is a client who would like to create a game called draw it or lose it. It is similar in concept to the 1980s television game "Win, Lose or Draw".

Teams will compete to guess what is being drawn over a specific amount of time.

## Design requirements

Draw it or Lose it will be supported on multiple operating platforms, including Windows, Linux, MacOS, and mobile (Android, IPhone).

## What did i do well?
Naturally the first thought that comes to mind is that multiple clients will need to be able to interact. In order to get this setup, we need to standardize communication between clients. This can be done using a RESTful API to standardize interactions between all the different clients.

I did a good job of identifying the strengths and weaknesses of every operating system we can use to develop the server and client, and selecting a specific operating system and architecture for the server (Windows, as it is easy to use, and just as viable as Linux).

## How did making the design document help me when developing the code?
Identifying the relationships between the Singleton model and the different classes like Game, Team, and Player made it a lot easier to write the code that connects everything together.

## What would I revise?
I think I did a good job on the entire document, The professor disagreed with me on the final server choice. My choice was Windows, professor suggested Linux. I still stand by Windows as it is easier to setup. I would not make any changes.

## How did you interpret the users needs and why is considering the user's needs so important?
The user is the person who will be utilizing the application the most. If the user does not enjoy using the application, or finds it difficult and unappealing the will stop using it or find a competitor. The user needs to be able to easily play the game and have fun with as little load time as possible.

## How did you approach designing software ? What techniques or strategies would you use in the future to analyze and design a similar software application?
Designing software is a big part of the development process. Poorly designed software will never see the light of day, and if it does, it will be extremely difficult to maintain. I think the biggest thing you can do is research the platforms that your software will run on. Make sure you understand the ins and outs of each platform you need to support. In the future before I work on designing any software I will research common design patterns used in similar software, and apply the patterns that I think would benefit me the most.
