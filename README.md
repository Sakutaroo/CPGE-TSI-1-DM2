# CPGE-TSI-1-DM2

Personal project of CPGE TSi 1st year : DM2 Info

Objective : Decode a color image in ppm format defined by p lines and columns which contains a message encoded in ASCII.

Data : The message is read in ASCII from byte number n = 200 + p - c.
    Characters are spaced according to the sequence of Fibonacci so as not to change the originalimage too much.

Attachments (in file) :
    Hello.ppm : Test your program. The message is known : "Hello!"
    citation.ppm : Mystery file with a message to be decoded with your program which must adapt to everything image format.

Usage : ./pixel

Error : The program doesn't handle errors so make sure to use a correct file format (like the ones given) as an argument.