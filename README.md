# advent-of-code-2022

An optimistic attempt to solve [Advent of Code 2022](https://adventofcode.com/2022) using an emulated BBC Micro Computer.

I'm using the [Owlet BBC BASIC editor](https://bbcmic.ro/) for now - although if the data grows by much for some of the later challenges I'll probably have to switch to something where I can provide a disk image.

For now, you can copy/paste the code for each solution into the Owlet editor, and hit the run button to see it working...

## Solutions

| Solution A | Solution B |
|-|-|
| ![Result 01A](2022-12-01/01A-screenshot.png "A BBC Micro showing the result: Elf 209, Cal: 74198")<br/>[01A-solution.basic](2022-12-01/01A-solution.basic) | ![Result 01B](2022-12-01/01B-screenshot.png "A BBC Micro showing the values for the 3 most burdened elves, and a total: 209914")<br/>[01B-solution.basic](2022-12-01/01B-solution.basic) |
| ![running 02A](2022-12-02/02A-running.png "A BBC Micro part way through solving the first part of problem 2. It has printed symbols to represent the outcomes from each round...")<br/>[02A-solution.basic](2022-12-02/02A-solution.basic), [video](2022-12-02/02A-running.mov) | ![result 02B](2022-12-02/02B-screenshot.png "A BBC Micro showing the outcomes from all the rounds as symbols, and a final score: 13071")<br/>[02B-solution.basic](2022-12-02/02B-solution.basic) |
| ![Result 03A](2022-12-03/03A-screenshot.png "A BBC Micro showing a character for each rucksack, and below it in green a total: 7967")<br/>[03A-solution.basic](2022-12-03/03A-solution.basic) | ![Result 03B](2022-12-03/03B-screenshot.png "A BBC Micro showing a character for each group of 3 rucksacks, and below it in yellow a total: 2716")<br/>[03B-solution.basic](2022-12-03/03B-solution.basic) |
| ![Result 04A](2022-12-04/04A-screenshot.png "A BBC Micro screen full of stars and dots. Below it, in cyan, it says: Contained: 503")<br/>[04A-solution.basic](2022-12-04/04A-solution.basic) | ![Result 04B](2022-12-04/04B-screenshot.png "A BBC Micro screen much more heavily full of stars than dots. Below it, it says: Overlaps: 827")<br/>[04B-solution.basic](2022-12-04/04B-solution.basic) |
| ![Result 05A](2022-12-05/05A-screenshot.png "A BBC Micro screen filled with dots to indicate that it has been busy calculating. Below it, the final arrangement of crates is shown in yellow as a series of lines with different numbers of characters in them. Below that, the tops of the stacks (the last letter of each line) are shown together in green.")<br/>[05A-solution.basic](2022-12-05/05A-solution.basic) | ![Result 05B](2022-12-05/05B-screenshot.png "A BBC Micro screen filled with dots to indicate that it has been busy calculating. Below it, the final arrangement of crates is shown in yellow as a series of lines with different numbers of characters in them. Below that, the tops of the stacks (the last letter of each line) are shown together in green.")<br/>[05B-solution.basic](2022-12-05/05B-solution.basic) |
| ![Result 06A](2022-12-06/06A-screenshot.png "A BBC Micro screen full of seemingly random characters, white on black. Right at the bottom, the solution (a position) is written in blue. It indicates that at this point, the last 4 characters on screen are all different.")<br/>[06A-solution.basic](2022-12-06/06A-solution.basic) | ![Result 06B](2022-12-06/06B-screenshot.png "A BBC Micro screen full of seemingly random characters, white on black. Right at the bottom, the solution (a position) is written in cyan. It indicates that at this point, the last 14 characters on screen are all different.")<br/>[06B-solution.basic](2022-12-06/06B-solution.basic) |
| ![Result 07A](2022-12-07/07A-screenshot.png "BBC Micro output showing a number of directories, and their sizes. Below, a number in pink indicates the result: 1517599")<br/>[07A-solution.basic](2022-12-07/07A-solution.basic) | ![Result 07B](2022-12-07/07B-screenshot.png "BBC Micro output showing a number of directories, and their sizes. Below, a number in red indicates the result: 2481982")<br/>[07B-solution.basic](2022-12-07/07B-solution.basic) |
| ![Result 08A](2022-12-08/08A-screenshot.png "BBC Micro graphics - the forest is rendered in a grid, and each visible tree is a bright white pixel. It creates a dotted effect, with a mark darker centre to the woods.")<br/>[08A-solution.basic](2022-12-08/08A-solution.basic) | ![Result 08B](2022-12-08/08B-screenshot.png "BBC Micro graphics - all green this time. A pixel for every tree in the forest, and some stats at the top showing that each tree has been examined.")<br/>[08B-solution.basic](2022-12-08/08B-solution.basic) |
| ![Result 09A](2022-12-09/09A-screenshot.png "BBC Micro graphics - the motion of the rope's tail is rendered in yellow. At the top of the screen, the outcome is printed: 5960")<br/>[09A-solution.basic](2022-12-09/09A-solution.basic) | ![Result 09B](2022-12-09/09B-screenshot.png "BBC Micro graphics - BBC Micro graphics - the motion of the rope's tail is rendered in yellow. Its form is much smoother than the first solution, and mostly diagonal. At the top of the screen, the outcome is printed: 2327")<br/>[09B-solution.basic](2022-12-09/09B-solution.basic)<br/>(runtime: ~90m) |
| ![Result 10A](2022-12-10/10A-screenshot.png "BBC Micro screen - coloured text on black - showing half a dozen numbers in cyan, and their sum in green: 15020")<br/>[10A-solution.basic](2022-12-10/10A-solution.basic) | ![Result 10B](2022-12-10/10B-screenshot.png "BBC Micro graphics - a small 40x6 dot display in the centre of the screen shows the letters: EFUGLPAP")<br/>[10B-solution.basic](2022-12-10/10B-solution.basic) |
| ![Result 11A](2022-12-11/11A-screenshot.png "BBC Micro screen - a few rows of comma separated numbers at the top, and then below there are 8 items listed stating how many inspections each monkey made.")<br/>[11A-solution.basic](2022-12-11/11A-solution.basic) | ![Result 11B](2022-12-11/11B-screenshot.png "A terminal shows a BBC Micro prompt with RUN. Below is a row of dots. Below that are 8 entries - one for each money, indicating how many inspections each monkey made.")<br/>[11B-solution.basic](2022-12-11/11B-with-bignum.basic)<br/>[bignum.v1.basic](bignums/bignum.v1.basic) |

## Beebjit

Beebjit is a super fast BBC Micro emulator. I've used it to crunch solutions for problems that would have taken an inordinate amount of time. So far, that's:

* **11B** - This required 10,000 iterations of a complex algorithm that makes use of the `bignum` library functions (which, in turn, are very slow).

## The Beeb

![BBC Micro](images/bbc-micro.jpg "A BBC Micro - black keyboard, a red row of function keys above, and creamy rectangular plastic casing")

The BBC Micro (affectionately known as the Beeb) is a computer first released by the BBC in 1981. Soon after, they appeared in every school. I was also released in 1981, and I have a bit of a soft spot for these old 8-bit machines.

My brother and I grew up writing little games and programs for them in BBC BASIC.
