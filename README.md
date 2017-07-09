# GoKbd

A mechanical keyboard version of Go. Because why not.

## v1

```
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · ·  · [BLACK PASS]
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · ·  [7seg: BLACK SCORE]
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · ·         [LED: Black Wins]
· · · · · · · · · · · · · · · · · · ·  · [START]
· · · · · · · · · · · · · · · · · · ·         [LED: White wins]
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · ·  [7seg: WHITE SCORE]
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · ·  · [WHITE PASS]
· · · · · · · · · · · · · · · · · · · 
```

## v2

```
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · ·  · [BLACK PASS]
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · ┌──────┐
· · · · · · · · · · · · · · · · · · · │ B/W  │  · [UP]
· · · · · · · · · · · · · · · · · · · │ Line │  · [SELECT] [BACK]
· · · · · · · · · · · · · · · · · · · │ LCD* │  · [DOWN]
· · · · · · · · · · · · · · · · · · · └──────┘
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · ·  · [WHITE PASS]
· · · · · · · · · · · · · · · · · · · 
```
\* Simple settings and score

## v3

```
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · ·  · [BLACK PASS]
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · ┌────────────┐
· · · · · · · · · · · · · · · · · · · │ LCD        │
· · · · · · · · · · · · · · · · · · · │ Touch      │
· · · · · · · · · · · · · · · · · · · │ Screen*    │
· · · · · · · · · · · · · · · · · · · └────────────┘
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · · 
· · · · · · · · · · · · · · · · · · ·  · [WHITE PASS]
· · · · · · · · · · · · · · · · · · · 
```

\* Settings:

```
Settings
  ├ Rules Variants
  │   ├ Scoring
  │   │   ├ * JP
  │   │   └ CN
  │   ├ Superko
  │   │   ├ * On
  │   │   └ Off
  │   └ Time limit: [choice; default: None]
  ├ Komi: [float by .5]
  ├ Board size: [int; default: 19x19]
  ├ Handicap
  │   ├ P1: [int]
  │   └ P2: [int]
  ├ Colors
  │   ├ P1: [choice; default: red; red blue green orange purple white]
  │   └ P2: [choice; default: blue; red blue green orange purple white]
  ├ Sounds
  │   ├ * On
  │   └ Off
  ├ Running Score
  │   ├ * On
  │   └ Off
  ├ Preview Liberties
  │   ├ On
  │   └ * Off
  ├ SGF Sharing
  │   ├ P1
  │   │   ├ Name
  │   │   └ Email
  │   └ P2
  │       ├ Name
  │       └ Email
  └ Admin [password via board, line next to screen]
      ├ Lock admin
      ├ Networking [On/off, settings, etc...]
      └ Game Info
          ├ Set up date
          ├ Place name
          └ Game name prefix
```
