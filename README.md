# Discover Godot

## Overview

> Godot and React JS are great at doing their own things. Together, can they deliver the Killer Casino App?  

[discover-godot.web.app](https://discover-godot.web.app)

## Install & Use

You'll need node but just to manage the development environment, really

## Objectives

1. Games to be deployed as webapps. This means a single directory containing only static assets, usually with an `index.html` at the root level which (hopefully) references it's dependent files properly so that it deploys and runs any where on any server, from apache to the most sophisticated cloud architecture. 

Godot export presets are found here `./games/HelloWorld/export_presets.cfg`

2. To be informed of poor performance in good time, we should have a configurable debugger in the game which can show us dev info like FPS. That way, when developing the game, it will be obvious if you do something which makes the framerate drop to, say, 5fps. If that happens, there are serious problems in the code.

## Project Structure

The project is split into 3 JavaScript apps; Games (Godot), Frontend (React), Backend (Node) 

1. [Games](./games) 

Games are developed in Godot; a Free and open source 2D and 3D game engine. React is quite good too. Together can they deliver a Killer Casino App? 

- [Pingpong](./games/Pingpong)
- [SlotMachine](./games/SlotMachine)

2. [React](./react-app)
3. [Node](./node-app)

#### Docs

- [Godot](./docs/godot.md) 
- [Devops](./docs/devops.md)
- [Graphics](./docs/graphics.md)
- [Create React App](./docs/create-react-app.md)

_vs 1.0.8_
