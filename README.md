# PD-numpadfun
 Use your numepad to control your patches!  
 (This was made in Purr Data, tested in Pd Vanilla and seemingly everything works fine except that it keeps banging for as long as you press the key (big no-no))  
 (also in Purr Data you'll find that it was designed specifically so that the outlets match left and right of every symbol, this doesn't match the same way in Pd Vanilla)  
   
 This patch outputs bangs for every press and release, the outlets are ordered as follows:  
 1- Key 7 press, 2- Key 7 release  
 3- Key 8 press, 4- Key 8 release  
 5- Key 9 press, 6- Key 9 release  
 7- Key 4 press, 8- Key 4 release  
 9- Key 5 press, 10- Key 5 release  
 11- Key 6 press, 12- Key 6 release  
 13- Key 1 press, 14- Key 1 release  
 15- Key 2 press, 16- Key 2 release  
 17- Key 3 press, 18- Key 3 release  
 19- Key 0 press, 20- Key 0 release  
 21- Key . press, 22- Key . release  
 23- Key / press, 24- Key / release  
 25- Key * press, 26- Key * release  
 27- Key - press, 28- Key - release  
 29- Key + press, 30- Key + release  
 31- Key Enter press, 32- Key Enter release  
 33- Key Tab press, 34- Key Tab release  
   
 I know it seems like a lot, but the patch is designed so that the symbol names are found in between its respective outlets so there's no need remembering all of these numbers.
 I added the Tab key so that I could use it as a modifier (i.e. if key 7 is being pressed while tab, do something), esentially doubling the possibilities.
 
 I hope someone find this useful! I personally don't own any kind of midi controller nor anything similar so I always end up making silly stuff like this to test some of my patches.
