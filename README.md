## Lordofpomelo

Lordofpomelo is a browser-based MMORPG(massively multiplayer online role-playing game). 
The backend is written in node.js based on [pomelo](https://github.com/NetEase/pomelo/wiki/Introduction-to-pomelo),
which is a fast, scalable, distributed game server framework for node.js. The frontend uses the HTML5 Canvas to draw 
the map and renders the animations by colorbox, which is a client side game engine written in JavaScript based on HTML5.
In this game, the client communicates via websockets with the server. 

## How to install

You can install lordofpomelo with the guiding of the document 
[Installation guide of lordofpomelo](https://github.com/NetEase/pomelo/wiki/Installation-guide-of-lordofpomelo).
This document provides details on how to install and configure lordofpomelo quickly. Also you can find solutions
for some problem like port conflicts.

## How to play

Like other MMORPG, you should clone a hero with the given username. All of the heros will clone hp, mp, attack and
defense etc from the hero ontology. There are three scenes in the game, where you can roam casually, kill monsters for experiences,
treasures and equipments. If one monster is killed, more monsters will be cloned, which forces you to improve the hero
level and get more powerful equipments. For a better understanding of the game plot, you should visit npc and
communicate with it. Task system is very important, which will let you get more equipments and enjoy the game enough.

## Requirements

* [nodejs](http://nodejs.org/)
* Linux or Mac os
* MySQL

## Open source projects

Lordofpomelo requires the following npm libraries:

* pomelo(http://pomelo.netease.com/)
* colorbox
* express(http://expressjs.com/)
* socket.io(http://socket.io/)

.................

#### pomelo

Pomelo is made by our team. It is a fast, scalable, distributed game server framework for node.js. It provides the basic
development framework and a lot of related components, including libraries and tools. Pomelo is also suitable for realtime
web application, its distributed architecture makes pomelo scales better than other realtime web framework.

####colorbox
Colorbox is our team's another open source project. It is a client side game engine written in JavaScript based on HTML5 and 
soon to be open source. 

## Viewing

 * Visit the [lordofpomelo](http://nodejs.netease.com/lordofpomelo)
 * or you can visit [github:lordofpomelo](http://github.com/node-pomelo/lordofpomelo)to download the source and install it on your local machine.

## Screenshot

![scene three](http://pomelo.netease.com/image/demo4.png)

This is a screenshot in scene three. There are many monsters and one hero named Traxex who is killing the monster for experiences, treasures and equipments.


## License

(The MIT License)

Copyright (c) 2012 Netease, Inc. and other contributors

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
