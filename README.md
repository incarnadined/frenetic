# Frenetic
## Table of Contents

* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
  * [Installation](#installation)
* [Usage](#usage)
* [License](#license)


## About The Project

![frenetic][frenetic-logo]

## Getting Started

### Installation
 
1. Clone the repo
```sh
git clone https://github.com/incarnadined/frenetic.git
```

## Usage

This project can be used when playing the board game [Frenetic](https://freneticgame.com). The game involves trying to create words based on the chemical symbols of a limited number of elements. This app allows you to enter a word and be given the chemical makeup of the word. For example, the word back will be returned as BAcK using the elements Boron, Actinium and Potassium. If more than one way of making the word exists, only one will be displayed. If the word cannot be made, a string will still be returned, despite it obviously not being correct.

When a word is correct you score points based on the sum of the atomic numbers for the elements used to create the word. This app also provides points for the words it returns

![BaNaNa][banana]

## License

Distributed under the GNU General Public License v3.0. See `LICENSE` for more information.

[frenetic-logo]: images/logo.png
[banana]: images/banana.png
