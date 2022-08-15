
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
$ ./ns rd vdl -s

TR  09:27 ○ Roodeschool                       1
    09:31 │ Uithuizermeeden
    09:35 │ Uithuizen
    09:41 │ Usquert
    09:46 │ Warffum
    09:52 │ Baflo
    09:56 │ Winsum
    10:02 │ Sauwerd
    10:08 │ Groningen Noord
    10:13 ○ Groningen                        2a

IC  10:18 ○ Groningen                         7
    10:34 │ Assen
    11:15 ○ Zwolle                            5

IC  11:20 ○ Zwolle                           10
    11:29 │ Wijhe
    11:36 │ Olst
    11:45 │ Deventer
    11:58 │ Zutphen
    12:07 │ Dieren
    12:23 │ Arnhem Centraal
    12:36 ○ Nijmegen                         4b

TR  13:08 ○ Nijmegen                         1b
    13:11 │ Nijmegen Heyendaal
    13:17 │ Mook-Molenhoek
    13:23 │ Cuijk
    13:31 │ Boxmeer
    13:38 │ Vierlingsbeek
    13:45 │ Venray
    13:58 │ Blerick
    14:03 │ Venlo
    14:08 │ Tegelen
    14:15 │ Reuver
    14:20 │ Swalmen
    14:25 ○ Roermond                         3b

IC  14:30 ○ Roermond                          1
    14:45 ○ Sittard                          3a

IC  14:56 ○ Sittard                          20
    15:11 ○ Heerlen                           5

TR  15:23 ○ Heerlen                           1
    15:26 │ Heerlen Woonboulevard
    15:29 ○ Voerendaal                        2
```
