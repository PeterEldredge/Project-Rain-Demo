# Project-Rain-Demo
Summary:
This is a short 2 minute demo showing off some of the features in the newest game I've been working on, Project Rain (working title because we are bad at naming things). Currently there is me two other team members on the project. I am the Lead Developer and
Project Manager, we also have a Lead Writer and Level Designer, and a Composer. We are hoping to bring on a few artist and maybe another programmer once the game is in a better state.

My Contributions:
I have contributed fair bit to the Story and Design of the game, however most of my time is spent programming and now trying to figure out ways to optimize the game. We are using 2 asset packs that have done some of the underlying work for us so far. The first is a First Person Controller, this only required a few minor tweaks and we were able to get the player moving like we wanted, even supporting gamepads. The second was our dialogue system. This asset makes it very easy for our writer to add and edit new dialogue.

Other then those two, I have added everything gameplay wise. I made an event system that is used throughout most of the code which has has removed a lot of the tight coupling that has plagued my other projects. This is the base of many of the other systems that I added, which include:

Inventory System

Save System

Document Interaction

Terminals

Keypads

Dynamic Lighting Effects (Fire and Flickering)

All of these systems have been made much more carefully than before. It is now very easy to make a terminal and populate it with emails or other content with data objects. The level designer can easy tweak the lighting with different parameters. Items are also made by just dropping a data object on them. I have made sure to put a lot of care into making the developement process easier for everybody.

Issues / What I would like to fix:
The biggest problem with the game now is that it does not run very well. There is an insane amount of draw calls every frame. The good news is that we can fix it, it is just going to take some time. Meshes will need to be combined based on where they are and what light is hitting them. Lights also need to be baked as opposed to all running in realtime. In addition to these, currently we have one big scene. The plan is to break this up into many smaller scenes, then implement an addative loading solution to ensure the only scenes loaded are the ones currenly relevant to the player.

Additionally, we are planning to get artists once the game is running a little better and we can live demo it, as a lot of the art is not finalized. In particular the Terminals, Keypad, and Documents. This still is a very early on work in progress.

How to play it:
We don't have a playable demo yet, but if you click the link at the top of the page or right under this it should take you to a video showing off some features in the game.

Demo Video: https://1drv.ms/v/s!AsFPPxUmmu-T2mCOuDGQJr8lBlDF




