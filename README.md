

Originally posted to gist:
https://gist.github.com/snekman33/688ccd558a4065521c13d0a8934ef974

This test rates you on 4 dimentions. Socially, economically, progressively and on a conviction scale.

Aided by anonymous discord user to shorten the code from 1500 lines


functions: 
  a5xanswer() Vs e5xanswer():
  a5xanswer() is for when "a" (strongly agree) increases your x value
  e5xanswer() is for when "a" (strongly agree) decreases your x value

same goes for a5yanswer(), e5yanswer(), p5answer and p0answer

xqnum = 'x' question number. Counts number of x/economic axis questions
add " xqnum += 1 " after adding a new question rating on the economic axis.

yqnum = 'y' question number. Counts number of y/social axis questions
add " yqnum += 1 " after adding a new question rating on the social axis.

pqnum = same as above but is for the progressive axis.


xqtpc = 500/xqnum
'x' question to pixel converter

yqtpc = 500/yqnum
'y' question to pixel converter

pqtpc = 500/pqnum
'p' question to pixel converter

