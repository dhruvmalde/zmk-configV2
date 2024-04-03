> **Ferris Sweep Keyboard**
![IMG_9232](https://github.com/greedysnakeDRV/zmk-configV2/assets/161101617/4de14911-66ff-4c94-ab6c-a84ff53c6cac)

Welcome to greedysnake's Ferris Sweep Keyboard repository! This README serves as your guide to understanding and using the Ferris Sweep Keyboard, a customizable and ergonomic mechanical keyboard designed for enthusiasts and professionals alike, the best part you can build it yourself just like I did with no prior experience needed (just some curiosity and tinkering)

**Overview**
The Ferris Sweep Keyboard is a unique ergonomic keyboard that prioritizes comfort, functionality, and aesthetic appeal. Named after its distinctive curved design reminiscent of a ferris wheel, this keyboard aims to revolutionize your typing experience.

Motivation for Transitioning to a Ferris Sweep Layout : Transitioning to a Ferris Sweep layout is driven by a desire to prioritize user comfort, enhance functionality, and elevate the typing experience:
    
**Ergonomics:** The sweeping curvature reduces strain, promoting a relaxed posture and minimizing the risk of repetitive strain injuries. Customization options cater to individual ergonomic needs.
    
**Functionality:** Integrated mouse buttons streamline navigation, while customizable key mappings optimize productivity. Compatibility with both Mac and Windows ensures a seamless experience across platforms.
    
**Aesthetic Appeal:** The unique curved design adds sophistication to any workspace, setting the Ferris Sweep layout apart from traditional keyboards.

In summary, the transition to a Ferris Sweep layout is motivated by a desire to prioritize user comfort, optimize functionality, and elevate the overall typing experience. By embracing ergonomic design principles, functional versatility, and aesthetic innovation, the Ferris Sweep layout offers a compelling solution for users seeking to enhance their productivity and well-being in the digital age.

References and key guides that were helpful during the build
https://www.youtube.com/@BenVallack
https://www.youtube.com/@KyekOfficial
https://www.youtube.com/@SethusBuilds
https://www.youtube.com/@joe_scotto
https://www.youtube.com/@joseanmartinez

Sourcing parts:
https://typeractive.xyz
https://keebmaker.com

if you are just here for the keymap, here you go


Combos : (Alpha Layers only) Copy, Paste, Select All and Undo ; (All layers) Escape, Cap Word, Delete and Backspace 
Behaviors : Backspace Delete (Mod Morph)

Keyboard Layout file  - ZMK Ferris Sweep

Mac Alpha Layer
* 	          &kp Q      &kp W      &kp E      &kp R                &kp T                      &kp Y              &kp U              &kp I           &kp O    &kp P
*             &kp A      HRML(S,          D,            F)          &kp G                      &kp H           HRMR(J,                  K,            L)      &mm_bspc_del
*             &kp Z      &kp X       &kp C      &kp V               &kp B                      &kp N              &kp M             &kp COMMA      &kp DOT    &kp ENTER
*                                                 &lt LEF TAB     &sk LSHIFT                    &kp SPACE      &lt RIG TAB
    


Windows Alpha Layer
*             &kp Q      &kp W       &kp E      &kp R         &kp T                   &kp Y             &kp U                  &kp I           &kp O          &kp P
*             &kp A    WHRML(S,          D,            F)     &kp G                  &kp H      WHRMR(J,                       K,                  L)         &mm_bspc_del
*             &kp Z      &kp X        &kp C      &kp V         &kp B                  &kp N              &kp M             &kp COMMA           &kp DOT        &kp ENTER
*                                                 &lt LEF TAB     &sk LSHIFT        &kp SPACE      &lt RIG TAB


Navigation/Numbers
*            &mwh DOT        &mkp RCLK           &mmv MOVE_UP     &mkp LCLK              &mwh SCROLL_UP       &kp PG_UP      &kp HOME     &kp UP      &kp END       &kp ENTER
*            &kp PRCNT         &mmv MOVE_LEFT    &mmv MOVE_DOWN   &mmv MOVE_RIGHT       &mwh SCROLL_DOWN      &kp PG_DN     &kp LEFT     &kp DOWN     &kp RIGHT     &mm_bspc_del    
*            &kp N1            &kp N2            &kp N3           &kp N4                &kp N5               &kp N6         &kp N7      &kp N8        &kp N9        &kp N0   
*                                                                 &trans                &trans              &trans          &trans

        
Symbols
*             &kp EXCL   &kp AT         &kp HASH    &kp DLLR   &kp PRCNT     &kp CARET      &kp AMPS     &kp ASTRK   &kp GRAVE       &kp TILDE
*             &kp LBKT   &kp LBRC    &kp LPAR.    &kp DQT     &kp FSLH        &kp MINUS      &kp EQUAL  &kp COLON     &kp SEMI       &mm_bspc_del
*             &kp RBKT   &kp RBRC    &kp RPAR     &kp SQT    &kp BSLH        &kp UNDER     &kp PLUS     &kp PIPE      &kp QMARK     &kp ENTER
*                                                      &trans           &trans         &trans            &trans
    


Function/Media
*             &kp F1      &kp F2     &kp F3      &kp F4      &bt BT_SEL 0     &bt BT_SEL 2         &out OUT_TOG        &kp C_NEXT         &kp C_MUTE           &tog WIN
*             &kp F5     &kp F6      &kp F7     &kp F8       &bt BT_SEL 1     &bt BT_SEL 3         &kp C_BRI_UP        &kp C_PP           &kp C_VOL_UP         &none
*             &kp F9     &kp F10    &kp F11    &kp F12     &bt BT_CLR        &bt BT_SEL 4         &kp C_BRI_DEC       &kp C_PREV          &kp C_VOL_DN         &none
*                                                                 &trans        &trans                &trans           &trans
