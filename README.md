# Simplelogica: The Game

![Simplelogica: The game](assets/images/backgrounds/title.png)

## About

This is an example of a game developed in Ruby using the [Gosu](https://www.libgosu.org/) library. All the resources of the game (images, music and audio effects) are some mine and some extracted from [http://opengameart.org/](http://opengameart.org/).

## Install dependencies

Here are the pre-requisites to play this game (or be able to use Gosu):

* Mac OS X: [Getting Started on OS X](https://github.com/gosu/gosu/wiki/Getting-Started-on-OS-X#prerequisites)
* Linux: [Getting Started on Linux](https://github.com/gosu/gosu/wiki/Getting-Started-on-Linux#getting-started-on-linux)
* Windows: [Getting Started on Windows](https://github.com/gosu/gosu/wiki/Getting-Started-on-Windows#getting-started-on-windows)

## Getting Started

To start playing this game, you only have to:

* Install Ruby (using [RVM](https://github.com/rvm/rvm) or [RBenv](https://github.com/sstephenson/rbenv) or whatever).

* Clone the repo and execute ***bundle install***:

```sh
sudo apt-get install libopenal1 libopenal-dev
sudo apt-get install libsdl2-dev
bundle install
```
## Usage

You can build the gem and install thr result to have the game available to execute whenever you want by executing:

```sh
gem build simplelogica_the_game.gemspec
gem install simplelogica_the_game-0.2.0.gem
```

Once you have done this, you can start the game by executing the binary:

```sh
simplelogica_the_game
```

Then follow the screen instructions, and have fun! 😊

----------------------------

This project was developed by [dreamingechoes](https://github.com/dreamingechoes).
It adheres to its [code of conduct](https://github.com/dreamingechoes/base/blob/master/files/CODE_OF_CONDUCT.md) and
[contributing guidelines](https://github.com/dreamingechoes/base/blob/master/files/CONTRIBUTING.md), and uses an equivalent [license](https://github.com/dreamingechoes/base/blob/master/files/LICENSE).

author : https://github.com/dreamingechoes/simplelogica_the_game