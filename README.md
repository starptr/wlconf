# wlconf

The Original Anonbot. Do not use. See https://github.com/MatthewStanciu/Anonbotv2 for a better and superior implementation in Node.js.

# About
A hacky setup that allowed users to submit text to a site with a php backend (see /server) that would append the text to the end of a file. Then a computer would run the batch script /manager/old_python2/repeat_uq.bat (don't try using the content in /manager outside of /old_python2, everything breaks) and would read the file on the server to see if any new text was appended. If so, an image containing the submitted text would be uploaded on the instagram account https://www.instagram.com/anonbot.wl/ for public viewing. Essentially, this was a bot that would let users post stuff essentially anonymously. (Saving IPs were added only a couple of days before V2 came out since someone decided to abuse the system, and I deleted the logs frequently even before that.) As you can see, this is ridiculously hacky and only gets the job done. It is not portable, requires a windows computer for proper function (idk how to handle exceptions in python lol), and frankly terribly written. (To be fair, I wrote it in an afternoon cause I felt like it, not because I thought I could do it.) I uploaded it here only for "historical" reasons.
