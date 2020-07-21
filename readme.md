Play here : https://nehahirve.github.io/platformgame/

A simple platform game based on Dark Blue by Thomas Palef. 
Created as an exercise to practice DOM manipulation and game mechanics. From Eloquent JS.

Coded this based on textbook exercise, took apart the code, understood it, and then reconstructed it on my own. Would like to now add customisation and more features.

Customisations so far: 

    skew player when moving

Goals:

    Collect all coins to complete level
    Avoid lava or level will be reset

Control:
    
    Player can move left or right with arrow keys, and can jump up with UP arrow key. 
    Player can jump several times height, can change direction mid-jump. 

Graphics:

    Moving parts can move in fractions of the grid to allow for smooth motion. 
    static background grid: solid wall, lava, empty
    moving parts          : lava bits, coins, player


Technology: 

    Static background displayed as a table
    Moving elements can be absolutely positioned
    I don't use the traditional canvas in this game


Encapsulation

    The only module that is encapsulated is the drawing module as it feels like an appropriate cutting point. encapsulating must be done if there are clear cutting points in the programme, keep the interfaces simple. 'Plug and Play'. The rest of the parts of the programme are very tied to each other and encapsulation would make for complicated interfaces.

New things learnt:

    async / await, asynchronous programming, promises
    game design, using classes
    writing a module that's designed to be swapped out, encapsulating
        