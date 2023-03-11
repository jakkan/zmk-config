# ZMK config

This is my personal config for a 34 key Cradio keyboard running ZMK firmware. It's based on manna-harbour's miryoku.

zmk: https://zmk.dev

cradio: https://github.com/davidphilipbarr/36keys/tree/master/34Keys/Cradio%20F

miryoku: https://github.com/manna-harbour/miryoku

## Design decisions

Compared with miryoku this layout prioritizes logical layout and similarity to ordinary keyboards at the expence of efficiency.

Here are the significant differences compared to miryoku:

- Shifted symbols are in the same position as their unshifted counterparts
  - To make it easier to switch to occational use on normal keyboards
  - To make learning and remembering the layout easier
- Only one way of doing things (no shortcut keys, no duplication in combos, not even a shifted symbols layer)
  - To train muscle memory on fewer things
- Numbers in 5x2 layot
  - Similar to an ordinary layout where a hand is responsible for five numbers on a row
- Only two thumb keys
  - Found pressing an extra layer buttom more comfortable than reaching for the third thumb key

## Layout

Default layer
```
╭──────────────────────────────────────────────┬──────────────────────────────────────────────╮
│                                              │                                              │
│ q        w        f        p        b        │ j        l        u        y        APOS     │
│                                              │                                              │
│ CTRL/a   ALT/r    GUI/s    SHFT/t   g        │ m        SHFT/n   GUI/e    ALT/i    CTRL/o   │
│                                              │                                              │
│ z        x        c        d        v        │ k        h        ,        .        /        │
│                                              │                                              │
╰──────────────────────╮     NAV/SPC  TAB      │ RET      NUM/BSPC     ╭──────────────────────╯
                       │                       │                       │
                       ╰───────────────────────┴───────────────────────╯
```

Numbers layer
```
╭──────────────────────────────────────────────┬──────────────────────────────────────────────╮
│                                              │                                              │
│ BSLH     MINUS    EQUAL    LBKT     RBKT     │                                              │
│                                              │                                              │
│ 6        7        8        9        0        │          SHFT     GUI      ALT      CTRL     │
│                                              │                                              │
│ 1        2        3        4        5        │                                              │
│                                              │                                              │
╰──────────────────────╮     FUN/SEMI GRAVE    │                       ╭──────────────────────╯
                       │                       │                       │
                       ╰───────────────────────┴───────────────────────╯
```

Navigation layer
```
╭──────────────────────────────────────────────┬──────────────────────────────────────────────╮
│                                              │                                              │
│                                              │                                              │
│                                              │                                              │
│ CTRL     ALT      GUI      SHFT              │          LEFT     DOWN     UP       RIGHT    │
│                                              │                                              │
│                                              │          HOME     PG_DN    PG_UP    END      │
│                                              │                                              │
╰──────────────────────╮                       │ DEL      FUN / ESC    ╭──────────────────────╯                               
                       │                       │                       │
                       ╰───────────────────────┴───────────────────────╯
```

Function layer
```
╭──────────────────────────────────────────────┬──────────────────────────────────────────────╮
│                                              │                                              │
│ F11      F12      F13      F14      F15      │                                              │
│                                              │                                              │
│ F6       F7       F8       F9       F10      │ BT_CLR   BT_SEL 0 BT_SEL 1 BT_SEL 2 BT_SEL 3 │
│                                              │                                              │
│ F1       F2       F3       F4       F5       │                                              │
│                                              │                                              │
╰──────────────────────╮                       │                       ╭──────────────────────╯                               
                       │                       │                       │
                       ╰───────────────────────┴───────────────────────╯
```
