
```
usage: ns [-h] [-a TIME] [-d TIME] [-D] [-s] [-u] FROM TO

positional arguments:
  FROM        origin station
  TO          destination station

optional arguments:
  -h, --help  show this help message and exit
  -a TIME     arrival time
  -d TIME     departure time
  -D          enable debugging
  -s          show all stops
  -u          use fancy unicode
```


```
$ ./ns vl rd

┄┄┄┄┄┄┄┄┄┄┤
IC  09:54 ⬤ Nijmegen               1a
    11:11 ⬤ Zwolle                 10
┄┄┄┄┄┄┄┄┄┄┤
IC  11:15 ⬤ Zwolle                  6
    12:12 ⬤ Groningen              3b
┄┄┄┄┄┄┄┄┄┄┤ Check-uit NS en check-in Arriva
TR  12:22 ⬤ Groningen              2a
    13:05 ⬤ Roodeschool             1
┄┄┄┄┄┄┄┄┄┄┤

ico@mdoos:~/sandbox/prjs/ns(master)$ ./ns vl rd -s
┄┄┄┄┄┄┄┄┄┄┤
IC  09:54 ⬤ Nijmegen               1a
    10:11 │ Arnhem Centraal
    10:23 │ Dieren
    10:33 │ Zutphen
    10:46 │ Deventer
    10:53 │ Olst
    10:59 │ Wijhe
    11:11 ⬤ Zwolle                 10
┄┄┄┄┄┄┄┄┄┄┤
IC  11:15 ⬤ Zwolle                  6
    11:55 │ Assen
    12:12 ⬤ Groningen              3b
┄┄┄┄┄┄┄┄┄┄┤ Check-uit NS en check-in Arriva
TR  12:22 ⬤ Groningen              2a
    12:26 │ Groningen Noord
    12:32 │ Sauwerd
    12:37 │ Winsum
    12:41 │ Baflo
    12:47 │ Warffum
    12:51 │ Usquert
    12:56 │ Uithuizen
    13:01 │ Uithuizermeeden
    13:05 ⬤ Roodeschool             1
┄┄┄┄┄┄┄┄┄┄┤

```
