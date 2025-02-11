# My_changes

```c

//replace RET with SPACE
                                              &lt_spc NAV 0 &lt FN SPACE,   SMART_NUM     MAGIC_SHIFT
// change numpad benford law

// ============== nav layer additional keys ==============
/* lassocopy, lower than, greater than */

// nav layer
    ___           ___           ___           LASSO_COPY    ___,   ___           &kp TAB       &kp LT         &kp GT     ___,


// ============== remove repaet if last key was an alpha key from the smart shift button ==============

/* ZMK_ADAPTIVE_KEY( */
/*     shift_repeat, bindings = <&sk LSHFT>; */
/*     repeat { */
/*       trigger-keys = <A B C D E F G H I J K L M N O P Q R S T U V W X Y Z>; */
/*       bindings = <&key_repeat>; */
/*       max-prior-idle-ms = <1200>; */
/*       strict-modifiers; */
/*     };) */
```

```config
// combos

ZMK_COMBO(cut,   &kp LG(X),    LB3 LB1,     DEF NAV NUM, COMBO_TERM_FAST, COMBO_IDLE_FAST)
ZMK_COMBO(copy,  &kp LG(C),  LB3 LB2,     DEF NAV NUM, COMBO_TERM_FAST, COMBO_IDLE_FAST)
ZMK_COMBO(paste, &kp LG(V),  LB2 LB1,     DEF NAV NUM, COMBO_TERM_FAST, COMBO_IDLE_FAST)

```
