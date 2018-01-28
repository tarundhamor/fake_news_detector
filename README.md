# Skillenza-Hackathon-18

The following C++ program takes the input as a text file and checks that weather the news given inside
that file is true news or fake news.
We have got 4 other files which contains of keywords. The first file has names of countries and cities as
keywords and the others have similar set of actions like the keyword2.txt has killed, died etc. the file
keyword3.txt has kidnapped, abducted etc. and the last one has numbers.
We also have a real news file which is an already created database of several authentic news collected
from reliable sources. In our program we compare our input file with this file.


PROGRAM DESCRIPTION:

It is a C++ program that opens a file source.txt and takes its first line as input as in any news the first line
would be the headline and by seeing it only one can tell if the news is real or fake. Afterwards each word
of the line is separated and then compared with the keywords text files to sort out the various keyword
in the headline. Then we open the real news file and input it line by line followed by breaking the line
into words then comparing them with the keyword of headline, when we get a 100% match (assuming
that killed and died would be the same and counted as true news) we output as true news. If there is
something wrong with the presented numerical data then it is exaggerated news otherwise true news.
