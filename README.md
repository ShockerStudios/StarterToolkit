# Starter Toolkit
A set of standard event scripts and useful links

# How to install
[Download the latest release of this package.](https://github.com/ShockerStudios/StarterToolkit/archive/1.0.zip)

Unzip the file and import the packages into your Unity project.

# How to Use Scripts

Counter Event

![Counter Event](https://github.com/ShockerStudios/StarterToolkit/blob/master/Info/CounterEvent.png)

When the 'Current Count' varible is equal to or greater than the 'Needed Amount', the counter event onComplete will be called. To add progress, call the 'Add' function in this script and fill in the amount you wish to add in the parameters field.

Delayed Event

![Delayed Event](https://github.com/ShockerStudios/StarterToolkit/blob/master/Info/DelayedEvent.png)

The onDelayedEvent is called after a set amount of time. This can be called in two ways. You can set the 'Start Event On Play' to immeditaely call the delayed event when this object begins its instance. Set the 'Default Delay Time' to the time you wish to wait. Or you may call the 'StartDelayEvent' and put a float variable in its parameters.

Game Event

![Game Event](https://github.com/ShockerStudios/StarterToolkit/blob/master/Info/GameEvent.png)

The Game Event is a go between asset between an object that will call the event and the listeners that are waiting for the event to be raised. Set the name of the Game Event to a description of the event. Something like "PlayerDied"

Game Event Listener

![Game Event Listener](https://github.com/ShockerStudios/StarterToolkit/blob/master/Info/GameEventListener.png)

The listener is a component that waits for a specific Game Event to be raised (called).

Initialize Events

![Initialize Events](https://github.com/ShockerStudios/StarterToolkit/blob/master/Info/InitEvents.png)

These events are the three that begin at the start of an objects life. On Awake is the first event that is called before any Start or Update function. Use this one to set first settings.

On Start is called after this.

On Enabled is called anytime an objects is set to active.

Trigger Event 2D

![Trigger Event 2D](https://github.com/ShockerStudios/StarterToolkit/blob/master/Info/Trigger2D.png)

Trigger Event 3D

![Trigger Event 3D](https://github.com/ShockerStudios/StarterToolkit/blob/master/Info/Trigger3D.png)



# Where to look for ideas
[Ludum Dare Games](http://ldjam.com/games)

[Past Itch.io Game Jams](https://itch.io/jams/past)

# General Free Assets
[Kenney - Assets](https://www.kenney.nl/assets)

# 2D Game Templates/Resources
[Platformer Assets](https://assetstore.unity.com/?q=platformer&orderBy=0)

[Platformer Micro Game](https://assetstore.unity.com/packages/templates/platformer-microgame-151055)

[Ninja Controller](https://assetstore.unity.com/packages/tools/physics/ninja-controller-64976)

[Prime 31 2D Controller](https://github.com/prime31/CharacterController2D)

# 3D Game Template/Resources
[Super Character Controller](https://github.com/IronWarrior/SuperCharacterController)

[3D Game Kit](https://assetstore.unity.com/packages/templates/tutorials/3d-game-kit-lite-135162)

[First Person All In One](https://assetstore.unity.com/packages/templates/systems/first-person-all-in-one-135316)
