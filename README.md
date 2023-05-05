latex-homework-template
=======================

This LaTeX is a cleanup of jdavis' template here: https://github.com/jdavis/latex-homework-template

Nothing about this template has been changed except the structure. I have divided the structure up into a preamable, frontmatter and mainmatter to allow for a more organised
folder structure. I have also divided each problem up into its own .tex file to allow for better encapsulation of the folder. The overall goal was to lessen cognitive load and
the amount of chaos going on in a single file.

## Using
### Changing the title
You can change the title page in `preamable.sty`. At the top of the file is a list of `\newcommand`s
of which you can change the paramters to suit your needs.

### Adding new problems
Anytime you want to add a new problem just add the file `problemX.tex` to the `mainmatter` folder
and make sure to `\include` it in `homework.tex`. The pages are loaded sequentially, so the order
in which you `\include` things determines the order in which the page appears.

### Adding packages
Anytime you want to add a package you can do so in `preamble.sty`. For example to add a code
environment you can add the package `listings` to the preamble with `\usepackage{listings}` and
then we're immediately free to use the listing environment in any of our `.tex` files.

## Features

Here are just a few features of this homework template.

1. Title page.
2. Problem markers.
3. Configurable problem numbers (see the last 3 problems for an example).
4. Some commonly used math macros.


## License

This code is distributed under the MIT license. For more info, read the
[LICENSE](/LICENSE) file distributed with the source code.

[texshop]: http://pages.uoregon.edu/koch/texshop/
[credit]: http://www.latextemplates.com/template/programming-coding-assignment
[twitter]: https://twitter.com/jldavis
