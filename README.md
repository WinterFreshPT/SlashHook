![banner](http://b.hitlers.kz/cdakof.png)

## Dectected?

Marc the "Founder" of basicly all these hotpatcher forks got his account banned which he said that he ONLY injected using hotpatcher, Take this as a disclaimer as i could not care less if you get your fucking account banned lmao

## WARNING!
If you're down right braindead please refrain from using this and linux all togheter.

## Compiling

**Note:** _Do NOT download or compile as the root user_

#### Download the dependencies required to build TheNewNew:

__Ubuntu-Based / Debian:__
```bash
sudo apt-get install cmake g++ gdb git libsdl2-dev zlib1g-dev
```

If you're having problems compiling make sure you've got the latest version of `g++`.

[How to update g++](https://github.com/AimTuxOfficial/AimTux/wiki/Updating-your-compiler)

##

__Arch:__
```bash
sudo pacman -S base-devel cmake gdb git sdl2
```
__Fedora:__
```bash
sudo dnf install cmake gcc-c++ gdb git libstdc++-static mesa-libGL-devel SDL2-devel zlib-devel
```

__Gentoo:__
```bash
sudo emerge cmake dev-vcs/git gdb libsdl2 mesa
```

##

#### Download TheNewNew:

```bash
git clone --recursive https://github.com/DankPaster/TheNewNew
```

```bash
cd TheNewNew
```

##

#### How to Download and Compile hotpatcher for injection.

Fast Install : ``` git clone https://github.com/vikasnkumar/hotpatch && cd hotpatch-master && make && sudo make install```
^ You can copy the entire line and paste it into terminal for a quick and automated install
#### "Manual Install"

```bash
git clone https://github.com/vikasnkumar/hotpatch
cd hotpatch-master
make
sudo make install
```
##

#### Generate a makefile

```bash
cmake .
```

#### Compile with make

**Note:** _The `4` in the command below specifies the amount of cpu "threads" or "cores" you wish to compile with (more = faster)._

```bash
make -j 4
```

## Injecting

First of all, make sure CSGO is open, it doesn't matter whether you're in game or not.

Navigate to the directory where Supreme was built if you haven't ready.

```bash
cd TheNewNew
```

Now, you can inject the hack with the `load` script

```bash
./load
```
Yes this is using Hotpatcher, I'm not giving you my injector sauce. And don't ask to buy it.
You might be prompted to enter in your password, this is because the injection script requires root access.

You should see a lot of text being printed out, most of which is not important,

If the injection was successfull you'll see a message at the bottom saying `Successfully injected!`, however, if the message says `Injection failed`, then you've most likely done something wrong.

Now, go back into csgo, if you're in the main menu of the game you should see a banner in the top left like so:

![this](http://aimtux.net/images/screenshot4.png)

## Using the hack

Now that xd has been injected into the game, press <kbd>Insert</kbd> on your keyboard to open the hack menu (<kbd>ALT</kbd>+<kbd>I</kbd> if you're using a laptop).

If you want to change skins, create and load configs or open the player list, you can find those buttons at the top of the screen.

## Unloading the hack

If you wish to unload the hack from the game, you can do so by entering the command:

```bash
./uload
```

## Updating TheNewNew

We add and improve and fix things almost every 9 - 20 years with xd. We don't have a fixed release schedule, we just add things to it when i'm really fucking bored. Because of this, TheNewNew will need to be at the mercy of some idiot on his computer.

If you don't update once a day then we recommend at LEAST update once a week, and ALWAYS update after a CSGO update, just to make sure we fix anything that's broken.

We provide a script included in the TheNewNew folder that updates xd for you. To use it, just run:

```
./update
```

And it will download and compile without any effort. Once it's done, happy hacking!

## Main Configs

Configs are stored in a hidden directory in your home folder. Specifically 

```
~/.config/TheNewNew/Main
```

Each `config.json` is stored in a seperately named folder (The name you see in-game, in the config window). 
 
To add a config, create a folder inside of the `~/.config/TheNewNew/Main` folder with a name of your choice, and paste the `config.json` inside of that folder.

To see hidden folders inside your home folder, press <kbd>CTRL</kbd>+<kbd>H</kbd> when using a file manager.

## Grenade Configs

```
~/.config/TheNewNew/Misc
```

Each `config.json` is stored in the folder named after them map name.

To add a config, copy the folder containing it to `~/.config/TheNewNew/Misc`

## Contributing to TheNewNew

If you wish to contribute code to this opensource project, please keep some things mind before creating a *pull request*:
 - Make sure you're using the correct [code style](https://github.com/AimTuxOfficial/AimTux/wiki/Code-Style).
 - Make sure your commits are clean and straight forward ( no junk commits )
 - Explain what you've done in your pull request.
 - Let's be honest, We all paste. I don't care if you pasted it, If it works and you want it added make a pull request.

## Screenshots

![menu](http://aimtux.net/images/screenshot1.png)
![skins](http://aimtux.net/images/screenshot2.png)
![esp_chams](http://aimtux.net/images/screenshot3.jpeg)

## Credits
Special thanks to [@aixxe](http://www.github.com/aixxe/) ([aixxe.net](http://www.aixxe.net)) for the skin changer and with the initial project, as well as helping this project with source code (Available on [@aixxe's](http://www.github.com/aixxe/) github page.)

## More Credits

Credits to BlastWorld for the creation of the fork i based my fork on, Credits to the founders of linux, Credits to the founders of the AimTux Project.

This project was also originally based upon Atex's [Linux Basehook](http://unknowncheats.me/forum/counterstrike-global-offensive/181878-linux-basehook.html).

## PSA for all.
If you encounter anyone selling a pInjector they use and is undetected 89% of the time it's a scam. Example: GreenByteScamware

HMU if you want to add some changes... Or you know just make a pull req.
