Ferris Sweep Keyboard
![IMG_9232](https://github.com/greedysnakeDRV/zmk-configV2/assets/161101617/4de14911-66ff-4c94-ab6c-a84ff53c6cac)

Welcome to greedysnake's Ferris Sweep Keyboard repository! This README serves as your guide to understanding and using the Ferris Sweep Keyboard, a customizable and ergonomic mechanical keyboard designed for enthusiasts and professionals alike, the best part you can build it yourself just like I did with no prior experience needed (just some curiosity and tinkering)

Overview
The Ferris Sweep Keyboard is a unique ergonomic keyboard that prioritizes comfort, functionality, and aesthetic appeal. Named after its distinctive curved design reminiscent of a ferris wheel, this keyboard aims to revolutionize your typing experience.


Motivation for Transitioning to a Ferris Sweep Layout

The decision to transition to a Ferris Sweep layout is driven by a convergence of ergonomic, functional, and aesthetic considerations, all aimed at enhancing the user's typing experience. Below are some key motivations for making the switch:

  Ergonomic Benefits:
    1. Comfort: Traditional keyboard layouts often force users into unnatural hand positions, leading to discomfort and potential long-term health issues such as repetitive strain injuries (RSIs). The sweeping curvature of the Ferris Sweep layout promotes a more relaxed hand and wrist posture, reducing strain and fatigue during extended typing sessions.
    2. Improved Reach: The ergonomic design of the Ferris Sweep layout ensures that keys are easily accessible, minimizing the need for excessive stretching or awkward finger movements. This promotes a more fluid and efficient typing experience while reducing the risk of muscle strain. 34 key layout was to only have one key movement per thumb to ease train muscle memory, alternatives include the Corne CRKBD 36 or 42key variant
    3. Customization: The Ferris Sweep layout allows for greater customization and adaptability to individual preferences and typing habits. Users can adjust key placements and angles to suit their unique ergonomic needs, optimizing comfort and productivity.
     
  Functional Advantages:
    1. Seamless Navigation: Integrating mouse buttons directly into the keyboard layout eliminates the need to switch between keyboard and mouse frequently, streamlining navigation and enhancing workflow efficiency.
    2. Mac and Windows Compatibility: Effortlessly map all keyboard functions for both Mac and Windows operating systems, ensuring compatibility and optimal performance across platforms.
    3. Enhanced Productivity: Customizable key mappings enable users to assign functions and shortcuts based on their specific workflow requirements. This facilitates faster access to frequently used commands and enhances overall productivity.
    4. Cross-Platform Compatibility: The ability to map all keyboard functions for both Mac and Windows operating systems ensures a consistent and seamless typing experience across different platforms, catering to diverse user preferences and requirements.
  
  Aesthetic Appeal:
    1. Unique Design: The distinctive curved shape of the Ferris Sweep layout sets it apart from traditional rectangular keyboards, making a bold statement on any workspace. Its sleek and modern aesthetic adds a touch of sophistication to the user's setup, enhancing both visual appeal and functionality.

In summary, the transition to a Ferris Sweep layout is motivated by a desire to prioritize user comfort, optimize functionality, and elevate the overall typing experience. By embracing ergonomic design principles, functional versatility, and aesthetic innovation, the Ferris Sweep layout offers a compelling solution for users seeking to enhance their productivity and well-being in the digital age.

References and key guides that were helpful during the build
https://www.youtube.com/@BenVallack
https://www.youtube.com/@KyekOfficial
https://www.youtube.com/@SethusBuilds

Sourcing parts:
https://typeractive.xyz
https://keebmaker.com

if you are just here for the keymap, here you go

Keyboard Layout file  - ZMK Ferris Sweep

Mac Alpha Layer
* 	          &kp Q      &kp W      &kp E      &kp R               &kp T                      &kp Y              &kp U              &kp I           &kp O      &kp P
*             &kp A      HRML(S,          D,            F)          &kp G                      &kp H           HRMR(J,                  K,            L)      &kp BSPC
*             &kp Z      &kp X       &kp C      &kp V               &kp B                      &kp N              &kp M             &kp COMMA      &kp DOT    &kp ENTER
*                                                 &lt LEF TAB     &sk LSHIFT                    &kp SPACE      &lt RIG TAB
    


Windows Alpha Layer
*             &kp Q      &kp W       &kp E      &kp R         &kp T                   &kp Y             &kp U                  &kp I           &kp O         &kp P
*             &kp A    WHRML(S,          D,            F)     &kp G                  &kp H      WHRMR(J,                       K,                  L)         &kp BSPC
*             &kp Z      &kp X        &kp C      &kp V         &kp B                  &kp N              &kp M             &kp COMMA           &kp DOT        &kp ENTER
*                                                 &lt LEF TAB     &sk LSHIFT        &kp SPACE      &lt RIG TAB


Navigation/Numbers
*            &mwh DOT        &mkp RCLK           &mmv MOVE_UP     &mkp LCLK              &mwh SCROLL_UP       &kp PG_UP      &kp HOME     &kp UP        &kp END     &kp BSPC  
*            &kp PRCNT         &mmv MOVE_LEFT    &mmv MOVE_DOWN   &mmv MOVE_RIGHT       &mwh SCROLL_DOWN       &kp PG_DN     &kp LEFT     &kp DOWN   &kp RIGHT      &kp ENTER      
*            &kp N1            &kp N2            &kp N3         &kp N4               &kp N5             &kp N6         &kp N7      &kp N8         &kp N9      &kp N0   
*                                                               &trans               &trans              &trans       &trans

        
Symbols
*             &kp EXCL   &kp AT         &kp HASH    &kp DLLR   &kp PRCNT     &kp CARET      &kp AMPS     &kp ASTRK   &kp GRAVE   &kp TILDE
*             &kp LBKT   &kp LBRC    &kp LPAR.    &kp DQT     &kp FSLH        &kp MINUS      &kp EQUAL  &kp COLON   &kp SEMI       &kp BSPC
*             &kp RBKT   &kp RBRC    &kp RPAR     &kp SQT    &kp BSLH        &kp UNDER     &kp PLUS     &kp PIPE         &kp QMARK  &kp ENTER
*                                                      &trans           &trans         &trans            &trans
    


Function/Media
*             &kp F1      &kp F2     &kp F3      &kp F4      &bt BT_SEL 0     &bt BT_SEL 2         &out OUT_TOG        &kp C_NEXT       &kp C_MUTE            &tog WIN
*             &kp F5     &kp F6      &kp F7     &kp F8       &bt BT_SEL 1     &bt BT_SEL 3         &kp C_BRI_UP          &kp C_PP           &kp C_VOL_UP         &none
*             &kp F9     &kp F10    &kp F11    &kp F12     &bt BT_CLR        &bt BT_SEL 4         &kp C_BRI_DEC       &kp C_PREV      &kp C_VOL_DN         &none
*                                                                 &trans        &trans                &trans                     &trans
