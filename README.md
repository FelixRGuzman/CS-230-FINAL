# CS-230 Module Eight Journal: The Gaming Room

# Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

To summarize, the client was The Gaming Room, and they wanted us to redesign their Android game "Draw It or Lose It" into a web-based application that could run on multiple platforms.The game is a drawing guessing game inspired by the TV Show Win, Lose or Draw, where players guess an image before time runs out. Essentially, we had to make an application that would fit their new requirements which included multiple teams and players, unique game and team names, all while prioritizing scalability and security.

# What did you do particularly well in developing this documentation?

I did a good job clearly listing the client’s requirements and explaining how the system would meet them. I organized everything from system architecture, operating system evaluations, memory, storage management and so on. 

# What about the process of working through a design document did you find helpful when developing the code?

The design document helped lay everything out ahead of time. It made it easier to structure the required systems and roles. Having the requirements, domain models, and system needs written down helped a lot when interacting with the corresponding classes, This is all because I already knew the rules the system had to follow.


# If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could revise anything, I would probably explain the application’s networking and instance management in more technical detail. I covered it briefly, but in the future, I would mention specific tools or strategies to show an even deeper understanding of how this application would actually scale in the real world.


# How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

I broke down the client’s needs (like unique names, timing rules, multiplayer teams) into specific technical requirements and built the classes and services around them. For example, the GameService Singleton enforced one game instance, and the authentication system made sure only the right users could access certain parts.

Focusing on user needs is paramount. If we do what we wish and end up missing what they actually want, we would just end up wasting time building features that are irrelevant, go unused, or worse, get you fired!

# How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I started by fully understanding the client’s business and technical needs, then made sure the design would directly meet them. I used UML diagrams ,operating system comparison, and properly analyzed the appropriate software development techniques to tackle this project. In the future, I would keep using this method but probably spend more time testing the application with testing methods and other people.

