#Introduction

Snake.pl is a small perl script that emulates the classic "pipes" screensaver
in a terminal window.

#Usage

Snake.pl ought to run on perl 5.8 and beyond with no prerequisites.

To get help, run `snake.pl -h` to see the following output:

    Usage:
        snake.pl [OPTIONS]

        Options:

            -p, --pipes=N   Number of pipes.                  (Default: 1  )
            -f, --fps=N     Frames per second.                (Default: 75 )
            -a, --ascii     ASCII mode.                       (Default: no )
            -l, --length=N  Minimum length of pipe.           (Default: 2  )
            -r, --prob=N    Probability of chaning direction. (Default: 0.1)
            -h, --help      This help message.

    Arguments:
        -p, --pipes=*integer*
            Number of pipes. A large number of pipes will probably slow things
            down a bit. Default 1.

        -f, --fps=*integer*
            Frames per second. This will be kept to as well as possible. Default
            75.

        -a, --ascii
            Use ASCII rather than unicode. This'll probably look pretty bad.

        -l, --length=*integer*
            Minimum length of a pipe, measured in characters.

        -r, --prob=*float*
            Probability of a pipe changing direction per time step.

        -h, --help
            Display this help message.


#Bugs

Please report any bugs using the Github issue tracker.
