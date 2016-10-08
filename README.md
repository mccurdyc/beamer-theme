# mccurdyc-beamer-theme

This repository contains the LaTeX source code and additional resources for the custom Beamer theme that I
that I, [Colton J. McCurdy](http://coltonmccurdy.com/) use. The presentation's source code uses a wide variety
of LaTeX packages, such as `beamer` and `pgftikz`, in order to create each slide. I have developed a custom
theme for the display of the slides and the use of progressive revealing of technical diagrams.

You are welcome to use these slides as inspiration for your own presentation. If you find this example useful, could I
trouble you to star this repository and then acknowledge it in your own presentation slides?

You can type the following command if you want to clone this repository:

```shell
git clone https://github.com/mccurdyc/beamer-theme.git
```

Then, if you want to compile the presentation to a PDF, you should type the following commands.
_Note: Since this is just the necessary source code for the custom beamer theme, when the source code
is compiled, it will only create a title slide._

```shell
cd beamer-theme
pdflatex mccurdyc-beamer-theme.tex
pdflatex mccurdyc-beamer-theme.tex
```

## Developement Environment

Please note that this has been tested on an Arch Linux 4.7.6 workstation running a very recent version of LaTeX
(pdfTeX 3.14159265-2.6-1.40.17 TeX Live 2016/Arch Linux) that was installed using the [pacman package manager](https://wiki.archlinux.org/index.php/pacman)
It is worth noting that you can also compile the paper using other LaTeX development tools, such as `latexmk`.
Additionally, you may find that the placement of certain `pgftikz` diagrams requires manual adjustment depending
on your LaTeX development environment and other settings. If you are unable to compile the presentation with your
development tools and your execution environment, then please open a new issue and I will attempt to resolve your concerns.
