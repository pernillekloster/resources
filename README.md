![Ironhack Logo](https://i.imgur.com/uYvaMH6.png)

# Bootcamp Resources

## Goal

The goal of this page is to share good resources with the class.

## Ironhack links

### Course links
- [Learn Platform](http://learn.ironhack.com)
- [Ironhack Berlin 2018 October Full-Time GitHub page](https://github.com/orgs/ironhack-berlin-2018-october-ft/): To find all the repositories
- [Morning challenges](https://repl.it/@MaxenceBouret/morning-challenge-october)


### Projects
- Project 1 rule (in construction)
- Project 1 list (in construction)
- Project 2 rule (in construction)
- Project 2 list (in construction)
- Project 3 rule (in construction)
- Project 3 list (in construction)


### Survey
- **Weekly Survey**: To fill every week (coming soon)
<!-- - [Anonymous Survey](https://sayat.me/mc100s)  -->


## External resources

### To learn
- [regex101.com](https://regex101.com/): Website to test and understand Regular expressions
- [A guide to flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/): The Flexbox Bible
- [getbootstrap.com](http://getbootstrap.com): The Bootstrap documentation
- [W3schools CSS Selectors ](https://www.w3schools.com/cssref/css_selectors.asp): Cheatsheet for CSS selectors

### Software
- [Photopea](https://photopea.com): Online Free Photoshop

### Content
- [Unsplash](http://unsplash.com): Website with free good pictures (with an API)
- [Flaticon](http://flaticon.com): Website to find nice icons


## Berlin Extra Curriculum

### General
- [Visual Studio Tips](./visualstudio.md)


### Week 1

#### Day 2
- Exercise: [CSS Positioning](./exercises/css-positioning/README.md)
- Exercise: [Flexbox Froggy](https://flexboxfroggy.com)

#### Day 3
- Exercise: [CSS Transitions](https://codepen.io/maxencebouret/pen/NOjKga?editors=1100)

#### Day 4
- Exercise: [Flexbox exercise](https://codepen.io/maxencebouret/pen/QZgvdp?editors=1100)


## FAQ

### How to kill a server (for example on PORT 5500)?

First you need to run the following command, that will give you the list of process using the port.
```sh
$ lsof -wni tcp:5500
# Answer 
# COMMAND     PID          USER   FD   TYPE             DEVICE SIZE/OFF NODE NAME
# Code\x20H 28289 maxencebouret   45u  IPv4 0xa9b05c1a28ae649b      0t0  TCP *:fcp-addr-srvr1 (LISTEN)
```

Then you you need to find the **PID** (here it's `28289`) and launch the following command:
```sh
$ kill -9 28289
```


