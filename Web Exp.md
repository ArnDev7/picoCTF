## caas

As guided, i opened `https://caas.mars.picoctf.net/cowsay/{message}`
\
downloaded the attached file and opened to find out that the user input gets processed and executed in the page.
\
`ls -l`
(to list out all the files)


`cat falg.txt`
\
to get the final flag



flag: **picoCTF{moooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo0o}**

---

## Forbidden path

Opened the website link and typed 'flag.txt' and result was 'not authorized'. After several tries...
 
Referred [this](https://hackmd.io/@nataliepjlin/Sk6M16mhn) and got to know about `../` which is used to navigate in the directory 

then entered `../../../../flag.txt`, to get through the filter and as there were three files, i typed it 4 times to get to the file.

flag: **picoCTF{7h3_p47h_70_5ucc355_6db46514}**



