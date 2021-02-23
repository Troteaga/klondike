# HELP

```
[?] Help:
Write movement as:
"D" to flip card on top of the deck
"W" to select card on top of the waste
"FN" to select card on top of foundry N
"PNM" to select M card from pile N


Write destination card as:
"F" to move card to foundry
"PN" to move card to pile N

"H" Hint will perform a random legal movement
"R" Restart game
"E" Exit game
```

# START GAME

```
[D]: #, [W]: 8♠ 7♦ 4♥

[F]oundries:| _♥ | _♦ | _♣ | _♠ |
            |  1 |  2 |  3 |  4 |
          
[P]iles:  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 |  10 |  11 |
      7:  #.|  # |  # |  # |  #.|  # | 12♥
      6:  #.|  # |  # |  # |  #.| 10♠
      5:  #.|  # |  # |  # | 11♥
      4:  #.|  # |  # | 8♣
      3:  # |  # | 5♦
      2:  # | 3♠ |
      1: 2♥ 

[? for help, H for Hint]
Movement: 
```

# PLAYING

```
[D]: #, [W]: 8♠

[F]oundries:| 1♥ | 3♦ | 4♣ | 2♠ |
            |  1 |  2 |  3 |  4 |
          
[P]iles:  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 |  10 |  11 |
      7:  #.|  # |  # |  # |  #.|  # | 12♥| 11♠
      6:  #.|  # |  # |  # |  #.| 10♠|  9♥
      5:  #.|  # |  # |  # | 11♥
      4:  #.|  # |  8♣
      3:  # |  5♦
      2:  # |  3♠ 
      1:  2♥ 

[? for help, H for Hint]
Movement:
```

# MOVE

```
[D]: #, [W]: 8♠

[F]oundries:| 1♥ | 3♦ | 4♣ | 2♠ |
            |  1 |  2 |  3 |  4 |
          
[P]iles:  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 |  10 |  11 |
      7:  #.|  # |  # |  # |  #.|  # | 12♥| 11♠
      6:  #.|  # |  # |  # |  #.| 10♠|  9♥
      5:  #.|  # |  # |  # | 11♥
      4:  #.|  # |  8♣
      3:  # |  5♦
      2:  # |  3♠ 
      1:  2♥ 

[? for help, H for Hint]
Movement:    P11
Destination: P22

[D]: #, [W]: 8♠

[F]oundries:| 1♥ | 3♦ | 4♣ | 2♠ |
            |  1 |  2 |  3 |  4 |
          
[P]iles:  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 |  10 |  11 |
      7:  #.|  # |  # |  # |  #.|  # | 12♥| 11♠
      6:  #.|  # |  # |  # |  #.| 10♠|  9♥
      5:  #.|  # |  # |  # | 11♥
      4:  #.|  # |  8♣
      3:  # |  5♦
      2:  # |  3♠|  2♥
      1:  

[? for help, H for Hint]
Movement:
```

# Invalid MOVE

```
[D]: #, [W]: 8♠

[F]oundries:| 1♥ | 3♦ | 4♣ | 2♠ |
            |  1 |  2 |  3 |  4 |
          
[P]iles:  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 |  10 |  11 |
      7:  #.|  # |  # |  # |  #.|  # | 12♥| 11♠
      6:  #.|  # |  # |  # |  #.| 10♠|  9♥
      5:  #.|  # |  # |  # | 11♥
      4:  #.|  # |  8♣
      3:  # |  5♦
      2:  # |  3♠ 
      1:  2♥ 

[? for help, H for Hint]
Movement:    P21
Invalid Movement!
Movement:
```

# Invalid DEST

```
[D]: #, [W]: 8♠

[F]oundries:| 1♥ | 3♦ | 4♣ | 2♠ |
            |  1 |  2 |  3 |  4 |
          
[P]iles:  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 |  10 |  11 |
      7:  #.|  # |  # |  # |  #.|  # | 12♥| 11♠
      6:  #.|  # |  # |  # |  #.| 10♠|  9♥
      5:  #.|  # |  # |  # | 11♥
      4:  #.|  # |  8♣
      3:  # |  5♦
      2:  # |  3♠ 
      1:  2♥ 

[? for help, H for Hint]
Movement:    P11
Destination: F2
Invalid Destination !
Destination:
```

# WIN

```
[D]: _, [W]: _

[F]oundries:| 12♥| 12♦| 12♣| 12♠|
            |  1 |  2 |  3 |  4 |
          
[P]iles:  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 |  10 |  11 |
      7:  _
      6:  _
      5:  _
      4:  _
      3:  _
      2:  _
      1:  _

YOU WIN 😀 [R, E]
```

# LOST

```
[D]: _, [W]: _

[F]oundries:|  9♥| 12♦| 12♣| 12♠|
            |  1 |  2 |  3 |  4 |
          
[P]iles:  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 |  10 |  11 |
      7:  # |  # | 11♥
      6:  _
      5:  _
      4:  _
      3:  _
      2:  _
      1:  _

YOU LOST 😟 [R, E]
```
