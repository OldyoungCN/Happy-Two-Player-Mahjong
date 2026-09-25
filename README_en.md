<p align="center">
  <a href="./README.md">
    <img src="https://img.shields.io/badge/中文版本-README-blue?style=for-the-badge" alt="中文版本">
  </a>
  &nbsp;&nbsp;
  <a href="./README_en.md">
    <img src="https://img.shields.io/badge/English%20Version-README-green?style=for-the-badge" alt="English Version">
  </a>
</p>

# Happy Two-Player Mahjong

**Happy Two-Player Mahjong**

Happy Two-Player Mahjong is a Chinese Mahjong game designed specifically around two-player matches.

The reason I made it is pretty simple: sometimes I want to play Mahjong, but I don't always have four people around.

Rather than simply squeezing traditional four-player Mahjong into a two-player format, I designed the game around two players from the beginning, including the tile wall, game pace, computer opponents, and overall controls.

The game is built with **Godot** and currently runs on Windows.

## Current Features

The game currently includes:

* Single-player against computer opponents
* AI difficulty levels 1–8
* Two-player LAN matches on Windows
* 64-tile wall
* Characters, Dots, and Bamboo suits
* East, South, West, North, Red Dragon, Green Dragon, and White Dragon
* Drawing tiles
* Discarding tiles
* Chi
* Pong
* Exposed Kong
* Concealed Kong
* Added Kong
* Robbing a Kong
* Ready hand / Tenpai detection
* Winning hands
* Self-drawn wins
* Beginner hints
* Basic tutorial
* Draw and action prompts
* Chinese / English interface
* Multiple table themes
* Background music
* Sound effects
* Separate music and sound-effect volume controls
* Detailed match results

## Why Two-Player Mahjong?

Traditional Mahjong usually needs four players.

But in real life, "I want to play Mahjong" and "I have exactly four people available" don't always happen at the same time.

I wanted to make something that lets me sit down and play a few rounds without having to gather four people or join an online table with strangers.

So Happy Two-Player Mahjong was designed around two players from the beginning rather than forcing four-player Mahjong into a smaller format.

You can play against the computer, or play against another person on the same Windows LAN.

## Computer Opponents

Single-player mode currently includes **8 AI difficulty levels**.

I didn't want "higher difficulty" to simply mean giving the computer unfair advantages, so I've spent quite a bit of time adjusting how the AI evaluates situations, chooses discards, and behaves differently across difficulty levels.

This is still one of the areas I'm continuing to test and tune.

Sometimes Level 8 makes me wonder who is actually testing whom.

## LAN Multiplayer

The game supports two-player LAN matches on Windows.

If two computers are connected to the same local network, one player can host a match and the other can join.

At the moment, this is **LAN multiplayer**, not Internet matchmaking.

## Built with Godot

The entire game is built with **Godot Engine**.

As a solo developer, I also use this repository to document some of the things I run into while developing the game, including:

* Mahjong game logic
* Computer player decision-making
* Godot UI
* Windows exports
* GL Compatibility
* LAN networking
* Performance issues
* Bugs and how I fixed them

Some of these things may be small, but if one of them happens to help another developer working with Godot, then it's worth writing down.

## About This Repository

This repository is mainly used for sharing:

* Game information
* Screenshots
* GIFs / gameplay footage
* Version updates
* Development notes
* Known issues
* Things I've learned while developing the game

**The game's source code is not published in this repository.**

This is a public project showcase and development log, not a source-code repository.

## Screenshots

More screenshots and gameplay GIFs will be added over time.

![Gameplay](01_gameplay_english.png)
![Gameplay](01_start_screen.png)
![Gameplay](03_ready_hand_hint.png)
![Gameplay](05_victory_result.png)

## itch.io

https://oldyoungcn.itch.io/

## Steam / Demo

Happy Two-Player Mahjong is currently being prepared for:

* Steam full release
* Steam Demo
* Steam Early Access

Steam Store ：[https://store.steampowered.com/app/5245710/_/?beta=1](https://store.steampowered.com/app/5245710/_/)

## Android Store Closed Beta Application URL: 

https://play.google.com/apps/testing/com.oldyoung.mahjong2p

## About Gambling

Happy Two-Player Mahjong is a Mahjong video game and does **not** involve real-money gambling.

The game does not include:

* Real-money betting
* Cash withdrawals
* Paid gambling chips
* Real-world rewards tied to wins or losses

## Developer

**OldYoung**

Solo indie game developer.

I mainly work with Godot, and I also like experimenting with AI-assisted development and other slightly unconventional ways of making games.

I enjoy making small games based on ideas that seem interesting to me.

Some projects may stay small, and some may never make much money. I still enjoy taking an idea that started in my head, slowly turning it into something playable, and eventually actually shipping it.

## Feedback

If you try the game, I'd genuinely like to know things such as:

* Which controls or actions were confusing
* Whether any AI difficulty level feels unreasonable
* Whether you think a Mahjong rule is implemented incorrectly
* Which parts of the UI are awkward to use
* Any bugs you run into
* Which hints aren't actually helpful for beginners

That kind of feedback is usually much more useful to me than simply hearing "looks good."

Thanks for playing.
