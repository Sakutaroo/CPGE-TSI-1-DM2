# CPGE-TSI-1-DM2

CPGE TSi 1st year : DM2 Info

Objective :<br />
    Decode a color image in ppm format defined by p lines and columns which contains a message encoded in ASCII.

Data :<br />
    The message is read in ASCII from byte number n = 200 + p - c.<br />
    Characters are spaced according to the sequence of Fibonacci so as not to change the originalimage too much.

Attachments (in file) :<br />
    Hello.ppm : Test your program. The message is known : "Hello!"<br />
    citation.ppm : Mystery file with a message to be decoded with your program which must adapt to everything image format.

Usage : ./pixel

Error : The program doesn't handle errors so make sure to use a correct file format (like the ones given) as an argument.
