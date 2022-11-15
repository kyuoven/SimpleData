2022-11-02

    Systematic program design:
        - What do we want the program to do?
        - How do we break down a problem?
    
        BSL = Beginning Student Languague
        Designed to have the core functionality of all other programming languages, but in a simple package that makes them easy to learn.

        Program design is something you learn by doing.
        Watch the videos actively, the pause button is your friend!

    Expressions

        primitives = +, -, /, *, ...
        expression = numbers

        To form an expression:
        (<primitive> <expression>...)

        Ignore line/Comment out:
        ;

        Square of number
        (sqr <number>)

        Square root number:
        (sqrt <number>)

2022-11-15

    > Strings

        (string-appens "Mystring" " " "Myotherstring")
            > "Mystring Myotherstring"
        
        (string-length "Mystring")
            > 8
        
        (substring "DifficultString" 2 6 ) ; take out all the characters from 2 to 4 and give us just those characters
            > ff

    0 based indexing:
        "012345678"
        (substring "012345678" 2 4) ; will take number 2 and 3, ending at 4 / we start with a 0
            > 23
        
        (substring "Caribou" 0 3) ; if you just want the first three letters! start at 0 again
            > Car
        
    > Images

        ; (require 2htdp/image) ; we want to use the image functions from the 2nd edition of how to design programs book

        (circle 10 "solid" "red" )
            > a red little circle

        (rectangle 30 60 "outline" "blue")
            > a blue rectangle



