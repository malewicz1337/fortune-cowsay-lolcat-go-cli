# Fortune Cowsay Lolcat Go CLI

This repository hosts a bundle of clones that are implemented in Go. These clones are inspired by the project described in Flavio Copes' [Go tutorial on building a Fortune clone](https://flaviocopes.com/go-tutorial-fortune/).

## Overview

This project combines the quirky outputs of `fortune`, `cowsay`, and `lolcat` into a single command-line interface (CLI) application, recreating the fun and colorful terminal outputs that have entertained developers for decades. Each component is built using Go, showcasing how to implement these classic Unix utilities in a modern programming language.

## Components

- **Fortune**: Displays pseudo-random messages from a predefined set of quotations. Perfect for adding a bit of wisdom or humor to your terminal.
- **Cowsay**: Generates an ASCII picture of a cow with a message. It can be combined with the output of `fortune` to create speaking cows.
- **Lolcat**: Adds rainbow coloring to text output in the terminal, making any output visually striking.

## Installation

To set up the Fortune Cowsay Lolcat CLI on your local machine, follow these steps:

1. Clone this repository:
```bash
git clone https://github.com/malewicz1337/fortune-cowsay-lolcat-go-cli.git
```

2. Navigate into the repository directory:
```bash
cd fortune-cowsay-lolcat-go-cli
cd [folder]
```

3. Build the application:
```bash
go build
go install
```

## Usage

Run the application with:
```bash
gofortune | gocowsay | gololcat
```
This command will produce a colorful, random fortune wrapped in an ASCII cow.

## License
This project is open source and available under the [MIT License](LICENSE).
