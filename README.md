> **Ferris Sweep Keyboard**
![IMG_9232](https://github.com/greedysnakeDRV/zmk-configV2/assets/161101617/ae871a76-006a-4d10-94b6-84b6902707ed)


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


Combos : (Alpha Layers only) Copy, Paste and Undo ; (All layers) Escape, Enter, Delete and Backspace 
Behaviors : Backspace Delete (Mod Morph)

Keyboard Layout file  - ZMK Ferris Sweep
![download](https://github.com/greedysnakeDRV/zmk-configV2/assets/161101617/46c587f6-c152-48fe-9a19-bcc50d27c6b3)
<svg width="732" height="1736" viewBox="0 0 732 1736" class="keymap" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<style>/* inherit to force styles through use tags */
svg path {
    fill: inherit;
}

/* font and background color specifications */
svg.keymap {
    font-family: SFMono-Regular,Consolas,Liberation Mono,Menlo,monospace;
    font-size: 14px;
    font-kerning: normal;
    text-rendering: optimizeLegibility;
    fill: #24292e;
}

/* default key styling */
rect.key {
    fill: #f6f8fa;
}

rect.key, rect.combo {
    stroke: #c9cccf;
    stroke-width: 1;
}

/* default key side styling, only used is draw_key_sides is set */
rect.side {
    filter: brightness(90%);
}

/* color accent for combo boxes */
rect.combo, rect.combo-separate {
    fill: #cdf;
}

/* color accent for held keys */
rect.held, rect.combo.held {
    fill: #fdd;
}

/* color accent for ghost (optional) keys */
rect.ghost, rect.combo.ghost {
    stroke-dasharray: 4, 4;
    stroke-width: 2;
}

text {
    text-anchor: middle;
    dominant-baseline: middle;
}

/* styling for layer labels */
text.label {
    font-weight: bold;
    text-anchor: start;
    stroke: white;
    stroke-width: 2;
    paint-order: stroke;
}

/* styling for combo tap, and key hold/shifted label text */
text.combo, text.hold, text.shifted {
    font-size: 11px;
}

text.hold {
    text-anchor: middle;
    dominant-baseline: auto;
}

text.shifted {
    text-anchor: middle;
    dominant-baseline: hanging;
}

/* styling for hold/shifted label text in combo box */
text.combo.hold, text.combo.shifted {
    font-size: 8px;
}

/* lighter symbol for transparent keys */
text.trans {
    fill: #7b7e81;
}

/* styling for combo dendrons */
path.combo {
    stroke-width: 1;
    stroke: gray;
    fill: none;
}

/* Start Tabler Icons Cleanup */
/* cannot use height/width with glyphs */
.icon-tabler > path {
    fill: inherit;
    stroke: inherit;
    stroke-width: 2;
}
/* hide tabler's default box */
.icon-tabler > path[stroke="none"][fill="none"] {
    visibility: hidden;
}
/* End Tabler Icons Cleanup */
</style>
<g transform="translate(30, 0)" class="layer-default">
<text x="0" y="28" class="label">default:</text>
<g transform="translate(0, 56)">
<g transform="translate(28, 80)" class="key keypos-0">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">Q</text>
</g>
<g transform="translate(84, 45)" class="key keypos-1">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">W</text>
</g>
<g transform="translate(140, 28)" class="key keypos-2">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">E</text>
</g>
<g transform="translate(196, 44)" class="key keypos-3">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">R</text>
</g>
<g transform="translate(252, 52)" class="key keypos-4">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">T</text>
</g>
<g transform="translate(420, 52)" class="key keypos-5">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">Y</text>
</g>
<g transform="translate(476, 44)" class="key keypos-6">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">U</text>
</g>
<g transform="translate(532, 28)" class="key keypos-7">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">I</text>
</g>
<g transform="translate(588, 45)" class="key keypos-8">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">O</text>
</g>
<g transform="translate(644, 80)" class="key keypos-9">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">P</text>
</g>
<g transform="translate(28, 136)" class="key keypos-10">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">A</text>
</g>
<g transform="translate(84, 101)" class="key keypos-11">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">S</text>
<text x="0" y="24" class="key hold">LALT</text>
</g>
<g transform="translate(140, 84)" class="key keypos-12">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">D</text>
<text x="0" y="24" class="key hold">LCTRL</text>
</g>
<g transform="translate(196, 100)" class="key keypos-13">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">F</text>
<text x="0" y="24" class="key hold">LGUI</text>
</g>
<g transform="translate(252, 108)" class="key keypos-14">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">G</text>
</g>
<g transform="translate(420, 108)" class="key keypos-15">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">H</text>
</g>
<g transform="translate(476, 100)" class="key keypos-16">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">J</text>
<text x="0" y="24" class="key hold">RGUI</text>
</g>
<g transform="translate(532, 84)" class="key keypos-17">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">K</text>
<text x="0" y="24" class="key hold">RCTRL</text>
</g>
<g transform="translate(588, 101)" class="key keypos-18">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">L</text>
<text x="0" y="24" class="key hold">RALT</text>
</g>
<g transform="translate(644, 136)" class="key keypos-19">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap"><tspan style="font-size: 78%">BACKSPACE</tspan></text>
</g>
<g transform="translate(28, 192)" class="key keypos-20">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">Z</text>
</g>
<g transform="translate(84, 157)" class="key keypos-21">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">X</text>
</g>
<g transform="translate(140, 140)" class="key keypos-22">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">C</text>
</g>
<g transform="translate(196, 156)" class="key keypos-23">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">V</text>
</g>
<g transform="translate(252, 164)" class="key keypos-24">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">B</text>
</g>
<g transform="translate(420, 164)" class="key keypos-25">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">N</text>
</g>
<g transform="translate(476, 156)" class="key keypos-26">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">M</text>
</g>
<g transform="translate(532, 140)" class="key keypos-27">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">,</text>
</g>
<g transform="translate(588, 157)" class="key keypos-28">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">.</text>
</g>
<g transform="translate(644, 192)" class="key keypos-29">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">ENTER</text>
</g>
<g transform="translate(224, 238)" class="key keypos-30">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">TAB</text>
<text x="0" y="24" class="key hold">left</text>
</g>
<g transform="translate(280, 252)" class="key keypos-31">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">LSFT</text>
</g>
<g transform="translate(392, 252)" class="key keypos-32">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">SPACE</text>
</g>
<g transform="translate(448, 238)" class="key keypos-33">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">TAB</text>
<text x="0" y="24" class="key hold">Right</text>
</g>
<g class="combo combopos-0">
<rect rx="6" ry="6" x="42" y="50" width="28" height="26" class="combo"/>
<text x="56" y="63" class="combo tap">ESC</text>
</g>
<g class="combo combopos-1">
<rect rx="6" ry="6" x="98" y="136" width="28" height="26" class="combo"/>
<text x="112" y="149" class="combo tap">LG(C)</text>
</g>
<g class="combo combopos-2">
<rect rx="6" ry="6" x="154" y="135" width="28" height="26" class="combo"/>
<text x="168" y="148" class="combo tap">LG(V)</text>
</g>
<g class="combo combopos-3">
<path d="M140,178 l-93,12" class="combo"/>
<path d="M140,178 l93,-12" class="combo"/>
<rect rx="6" ry="6" x="126" y="165" width="28" height="26" class="combo"/>
<text x="140" y="178" class="combo tap">LG(Z)</text>
</g>
<g class="combo combopos-4">
<rect rx="6" ry="6" x="602" y="50" width="28" height="26" class="combo"/>
<text x="616" y="63" class="combo tap">DEL</text>
</g>
<g class="combo combopos-5">
<path d="M336,252 l-37,0" class="combo"/>
<path d="M336,252 l37,0" class="combo"/>
<rect rx="6" ry="6" x="322" y="239" width="28" height="26" class="combo"/>
<text x="336" y="252" class="combo tap">ENTER</text>
</g>
</g>
</g>
<g transform="translate(30, 336)" class="layer-windows">
<text x="0" y="28" class="label">windows:</text>
<g transform="translate(0, 56)">
<g transform="translate(28, 80)" class="key keypos-0">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">Q</text>
</g>
<g transform="translate(84, 45)" class="key keypos-1">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">W</text>
</g>
<g transform="translate(140, 28)" class="key keypos-2">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">E</text>
</g>
<g transform="translate(196, 44)" class="key keypos-3">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">R</text>
</g>
<g transform="translate(252, 52)" class="key keypos-4">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">T</text>
</g>
<g transform="translate(420, 52)" class="key keypos-5">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">Y</text>
</g>
<g transform="translate(476, 44)" class="key keypos-6">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">U</text>
</g>
<g transform="translate(532, 28)" class="key keypos-7">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">I</text>
</g>
<g transform="translate(588, 45)" class="key keypos-8">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">O</text>
</g>
<g transform="translate(644, 80)" class="key keypos-9">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">P</text>
</g>
<g transform="translate(28, 136)" class="key keypos-10">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">A</text>
</g>
<g transform="translate(84, 101)" class="key keypos-11">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">S</text>
<text x="0" y="24" class="key hold">LALT</text>
</g>
<g transform="translate(140, 84)" class="key keypos-12">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">D</text>
<text x="0" y="24" class="key hold">LGUI</text>
</g>
<g transform="translate(196, 100)" class="key keypos-13">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">F</text>
<text x="0" y="24" class="key hold">LCTRL</text>
</g>
<g transform="translate(252, 108)" class="key keypos-14">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">G</text>
</g>
<g transform="translate(420, 108)" class="key keypos-15">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">H</text>
</g>
<g transform="translate(476, 100)" class="key keypos-16">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">J</text>
<text x="0" y="24" class="key hold">RCTRL</text>
</g>
<g transform="translate(532, 84)" class="key keypos-17">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">K</text>
<text x="0" y="24" class="key hold">RGUI</text>
</g>
<g transform="translate(588, 101)" class="key keypos-18">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">L</text>
<text x="0" y="24" class="key hold">RALT</text>
</g>
<g transform="translate(644, 136)" class="key keypos-19">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap"><tspan style="font-size: 78%">BACKSPACE</tspan></text>
</g>
<g transform="translate(28, 192)" class="key keypos-20">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">Z</text>
</g>
<g transform="translate(84, 157)" class="key keypos-21">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">X</text>
</g>
<g transform="translate(140, 140)" class="key keypos-22">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">C</text>
</g>
<g transform="translate(196, 156)" class="key keypos-23">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">V</text>
</g>
<g transform="translate(252, 164)" class="key keypos-24">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">B</text>
</g>
<g transform="translate(420, 164)" class="key keypos-25">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">N</text>
</g>
<g transform="translate(476, 156)" class="key keypos-26">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">M</text>
</g>
<g transform="translate(532, 140)" class="key keypos-27">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">,</text>
</g>
<g transform="translate(588, 157)" class="key keypos-28">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">.</text>
</g>
<g transform="translate(644, 192)" class="key keypos-29">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">ENTER</text>
</g>
<g transform="translate(224, 238)" class="key keypos-30">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">TAB</text>
<text x="0" y="24" class="key hold">left</text>
</g>
<g transform="translate(280, 252)" class="key keypos-31">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">LSFT</text>
</g>
<g transform="translate(392, 252)" class="key keypos-32">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">SPACE</text>
</g>
<g transform="translate(448, 238)" class="key keypos-33">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">TAB</text>
<text x="0" y="24" class="key hold">Right</text>
</g>
<g class="combo combopos-0">
<rect rx="6" ry="6" x="42" y="50" width="28" height="26" class="combo"/>
<text x="56" y="63" class="combo tap">ESC</text>
</g>
<g class="combo combopos-1">
<rect rx="6" ry="6" x="98" y="136" width="28" height="26" class="combo"/>
<text x="112" y="149" class="combo tap">LC(C)</text>
</g>
<g class="combo combopos-2">
<rect rx="6" ry="6" x="154" y="135" width="28" height="26" class="combo"/>
<text x="168" y="148" class="combo tap">LC(V)</text>
</g>
<g class="combo combopos-3">
<path d="M140,178 l-93,12" class="combo"/>
<path d="M140,178 l93,-12" class="combo"/>
<rect rx="6" ry="6" x="126" y="165" width="28" height="26" class="combo"/>
<text x="140" y="178" class="combo tap">LC(Z)</text>
</g>
<g class="combo combopos-4">
<rect rx="6" ry="6" x="602" y="50" width="28" height="26" class="combo"/>
<text x="616" y="63" class="combo tap">DEL</text>
</g>
<g class="combo combopos-5">
<path d="M336,252 l-37,0" class="combo"/>
<path d="M336,252 l37,0" class="combo"/>
<rect rx="6" ry="6" x="322" y="239" width="28" height="26" class="combo"/>
<text x="336" y="252" class="combo tap">ENTER</text>
</g>
</g>
</g>
<g transform="translate(30, 672)" class="layer-left">
<text x="0" y="28" class="label">left:</text>
<g transform="translate(0, 56)">
<g transform="translate(28, 80)" class="key keypos-0">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">.</text>
</g>
<g transform="translate(84, 45)" class="key keypos-1">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">7</text>
</g>
<g transform="translate(140, 28)" class="key keypos-2">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">8</text>
</g>
<g transform="translate(196, 44)" class="key keypos-3">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">9</text>
</g>
<g transform="translate(252, 52)" class="key keypos-4">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap"><tspan style="font-size: 78%">BACKSPACE</tspan></text>
</g>
<g transform="translate(420, 52)" class="key keypos-5">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">
<tspan x="0" dy="-0.6em">&amp;mkp</tspan><tspan x="0" dy="1.2em">LCLK</tspan>
</text>
</g>
<g transform="translate(476, 44)" class="key keypos-6">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">
<tspan x="0" dy="-0.6em" style="font-size: 60%">&amp;mmv</tspan><tspan x="0" dy="1.2em" style="font-size: 60%">MOVE_HOR(-1400)</tspan>
</text>
</g>
<g transform="translate(532, 28)" class="key keypos-7">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">
<tspan x="0" dy="-0.6em" style="font-size: 60%">&amp;mmv</tspan><tspan x="0" dy="1.2em" style="font-size: 60%">MOVE_VERT(1400)</tspan>
</text>
</g>
<g transform="translate(588, 45)" class="key keypos-8">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">
<tspan x="0" dy="-0.6em" style="font-size: 60%">&amp;mmv</tspan><tspan x="0" dy="1.2em" style="font-size: 60%">MOVE_VERT(-1400)</tspan>
</text>
</g>
<g transform="translate(644, 80)" class="key keypos-9">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">
<tspan x="0" dy="-0.6em" style="font-size: 60%">&amp;mmv</tspan><tspan x="0" dy="1.2em" style="font-size: 60%">MOVE_HOR(1400)</tspan>
</text>
</g>
<g transform="translate(28, 136)" class="key keypos-10">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">0</text>
</g>
<g transform="translate(84, 101)" class="key keypos-11">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">4</text>
</g>
<g transform="translate(140, 84)" class="key keypos-12">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">5</text>
</g>
<g transform="translate(196, 100)" class="key keypos-13">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">6</text>
</g>
<g transform="translate(252, 108)" class="key keypos-14">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">ENTER</text>
</g>
<g transform="translate(420, 108)" class="key keypos-15">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">
<tspan x="0" dy="-0.6em">&amp;mkp</tspan><tspan x="0" dy="1.2em">MCLK</tspan>
</text>
</g>
<g transform="translate(476, 100)" class="key keypos-16">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">LEFT</text>
</g>
<g transform="translate(532, 84)" class="key keypos-17">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">DOWN</text>
</g>
<g transform="translate(588, 101)" class="key keypos-18">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">UP</text>
</g>
<g transform="translate(644, 136)" class="key keypos-19">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">RIGHT</text>
</g>
<g transform="translate(28, 192)" class="key keypos-20">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">%</text>
</g>
<g transform="translate(84, 157)" class="key keypos-21">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">1</text>
</g>
<g transform="translate(140, 140)" class="key keypos-22">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">2</text>
</g>
<g transform="translate(196, 156)" class="key keypos-23">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">3</text>
</g>
<g transform="translate(252, 164)" class="key keypos-24">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">DEL</text>
</g>
<g transform="translate(420, 164)" class="key keypos-25">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">
<tspan x="0" dy="-0.6em">&amp;mkp</tspan><tspan x="0" dy="1.2em">RCLK</tspan>
</text>
</g>
<g transform="translate(476, 156)" class="key keypos-26">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">HOME</text>
</g>
<g transform="translate(532, 140)" class="key keypos-27">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">
<tspan x="0" dy="-0.6em">PG</tspan><tspan x="0" dy="1.2em">DN</tspan>
</text>
</g>
<g transform="translate(588, 157)" class="key keypos-28">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">
<tspan x="0" dy="-0.6em">PG</tspan><tspan x="0" dy="1.2em">UP</tspan>
</text>
</g>
<g transform="translate(644, 192)" class="key keypos-29">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">END</text>
</g>
<g transform="translate(224, 238)" class="key held keypos-30">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key held"/>
</g>
<g transform="translate(280, 252)" class="key trans keypos-31">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key trans"/>
<text x="0" y="0" class="key trans tap">▽</text>
</g>
<g transform="translate(392, 252)" class="key trans keypos-32">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key trans"/>
<text x="0" y="0" class="key trans tap">▽</text>
</g>
<g transform="translate(448, 238)" class="key trans keypos-33">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key trans"/>
<text x="0" y="0" class="key trans tap">▽</text>
</g>
<g class="combo combopos-0">
<rect rx="6" ry="6" x="42" y="50" width="28" height="26" class="combo"/>
<text x="56" y="63" class="combo tap">ESC</text>
</g>
<g class="combo combopos-1">
<path d="M336,252 l-37,0" class="combo"/>
<path d="M336,252 l37,0" class="combo"/>
<rect rx="6" ry="6" x="322" y="239" width="28" height="26" class="combo"/>
<text x="336" y="252" class="combo tap">ENTER</text>
</g>
</g>
</g>
<g transform="translate(30, 1008)" class="layer-Right">
<text x="0" y="28" class="label">Right:</text>
<g transform="translate(0, 56)">
<g transform="translate(28, 80)" class="key keypos-0">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">!</text>
</g>
<g transform="translate(84, 45)" class="key keypos-1">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">@</text>
</g>
<g transform="translate(140, 28)" class="key keypos-2">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">#</text>
</g>
<g transform="translate(196, 44)" class="key keypos-3">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">$</text>
</g>
<g transform="translate(252, 52)" class="key keypos-4">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">%</text>
</g>
<g transform="translate(420, 52)" class="key keypos-5">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">^</text>
</g>
<g transform="translate(476, 44)" class="key keypos-6">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">&amp;</text>
</g>
<g transform="translate(532, 28)" class="key keypos-7">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">*</text>
</g>
<g transform="translate(588, 45)" class="key keypos-8">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">`</text>
</g>
<g transform="translate(644, 80)" class="key keypos-9">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">~</text>
</g>
<g transform="translate(28, 136)" class="key keypos-10">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">[</text>
</g>
<g transform="translate(84, 101)" class="key keypos-11">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">{</text>
</g>
<g transform="translate(140, 84)" class="key keypos-12">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">(</text>
</g>
<g transform="translate(196, 100)" class="key keypos-13">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">&quot;</text>
</g>
<g transform="translate(252, 108)" class="key keypos-14">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">/</text>
</g>
<g transform="translate(420, 108)" class="key keypos-15">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">-</text>
</g>
<g transform="translate(476, 100)" class="key keypos-16">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">=</text>
</g>
<g transform="translate(532, 84)" class="key keypos-17">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">:</text>
</g>
<g transform="translate(588, 101)" class="key keypos-18">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">;</text>
</g>
<g transform="translate(644, 136)" class="key keypos-19">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap"><tspan style="font-size: 78%">BACKSPACE</tspan></text>
</g>
<g transform="translate(28, 192)" class="key keypos-20">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">]</text>
</g>
<g transform="translate(84, 157)" class="key keypos-21">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">}</text>
</g>
<g transform="translate(140, 140)" class="key keypos-22">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">)</text>
</g>
<g transform="translate(196, 156)" class="key keypos-23">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">&#x27;</text>
</g>
<g transform="translate(252, 164)" class="key keypos-24">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">\</text>
</g>
<g transform="translate(420, 164)" class="key keypos-25">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">_</text>
</g>
<g transform="translate(476, 156)" class="key keypos-26">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">+</text>
</g>
<g transform="translate(532, 140)" class="key keypos-27">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">|</text>
</g>
<g transform="translate(588, 157)" class="key keypos-28">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">?</text>
</g>
<g transform="translate(644, 192)" class="key keypos-29">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">ENTER</text>
</g>
<g transform="translate(224, 238)" class="key trans keypos-30">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key trans"/>
<text x="0" y="0" class="key trans tap">▽</text>
</g>
<g transform="translate(280, 252)" class="key trans keypos-31">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key trans"/>
<text x="0" y="0" class="key trans tap">▽</text>
</g>
<g transform="translate(392, 252)" class="key trans keypos-32">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key trans"/>
<text x="0" y="0" class="key trans tap">▽</text>
</g>
<g transform="translate(448, 238)" class="key held keypos-33">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key held"/>
</g>
<g class="combo combopos-0">
<rect rx="6" ry="6" x="42" y="50" width="28" height="26" class="combo"/>
<text x="56" y="63" class="combo tap">ESC</text>
</g>
<g class="combo combopos-1">
<rect rx="6" ry="6" x="602" y="50" width="28" height="26" class="combo"/>
<text x="616" y="63" class="combo tap">DEL</text>
</g>
<g class="combo combopos-2">
<path d="M336,252 l-37,0" class="combo"/>
<path d="M336,252 l37,0" class="combo"/>
<rect rx="6" ry="6" x="322" y="239" width="28" height="26" class="combo"/>
<text x="336" y="252" class="combo tap">ENTER</text>
</g>
</g>
</g>
<g transform="translate(30, 1344)" class="layer-tri">
<text x="0" y="28" class="label">tri:</text>
<g transform="translate(0, 56)">
<g transform="translate(28, 80)" class="key keypos-0">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">F1</text>
</g>
<g transform="translate(84, 45)" class="key keypos-1">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">F2</text>
</g>
<g transform="translate(140, 28)" class="key keypos-2">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">F3</text>
</g>
<g transform="translate(196, 44)" class="key keypos-3">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">F4</text>
</g>
<g transform="translate(252, 52)" class="key keypos-4">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">BT</text>
<text x="0" y="24" class="key hold">0</text>
</g>
<g transform="translate(420, 52)" class="key keypos-5">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">BT</text>
<text x="0" y="24" class="key hold">2</text>
</g>
<g transform="translate(476, 44)" class="key keypos-6">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">
<tspan x="0" dy="-0.6em">OUT</tspan><tspan x="0" dy="1.2em">TOG</tspan>
</text>
</g>
<g transform="translate(532, 28)" class="key keypos-7">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">NEXT</text>
</g>
<g transform="translate(588, 45)" class="key keypos-8">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">MUTE</text>
</g>
<g transform="translate(644, 80)" class="key keypos-9">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">windows</text>
<text x="0" y="24" class="key hold">toggle</text>
</g>
<g transform="translate(28, 136)" class="key keypos-10">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">F5</text>
</g>
<g transform="translate(84, 101)" class="key keypos-11">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">F6</text>
</g>
<g transform="translate(140, 84)" class="key keypos-12">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">F7</text>
</g>
<g transform="translate(196, 100)" class="key keypos-13">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">F8</text>
</g>
<g transform="translate(252, 108)" class="key keypos-14">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">BT</text>
<text x="0" y="24" class="key hold">1</text>
</g>
<g transform="translate(420, 108)" class="key keypos-15">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">BT</text>
<text x="0" y="24" class="key hold">3</text>
</g>
<g transform="translate(476, 100)" class="key keypos-16">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">
<tspan x="0" dy="-0.6em">BRI</tspan><tspan x="0" dy="1.2em">UP</tspan>
</text>
</g>
<g transform="translate(532, 84)" class="key keypos-17">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">PP</text>
</g>
<g transform="translate(588, 101)" class="key keypos-18">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">
<tspan x="0" dy="-0.6em">VOL</tspan><tspan x="0" dy="1.2em">UP</tspan>
</text>
</g>
<g transform="translate(644, 136)" class="key keypos-19">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
</g>
<g transform="translate(28, 192)" class="key keypos-20">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">F9</text>
</g>
<g transform="translate(84, 157)" class="key keypos-21">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">F10</text>
</g>
<g transform="translate(140, 140)" class="key keypos-22">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">F11</text>
</g>
<g transform="translate(196, 156)" class="key keypos-23">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">F12</text>
</g>
<g transform="translate(252, 164)" class="key keypos-24">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">
<tspan x="0" dy="-0.6em">BT</tspan><tspan x="0" dy="1.2em">CLR</tspan>
</text>
</g>
<g transform="translate(420, 164)" class="key keypos-25">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">BT</text>
<text x="0" y="24" class="key hold">4</text>
</g>
<g transform="translate(476, 156)" class="key keypos-26">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">
<tspan x="0" dy="-0.6em">BRI</tspan><tspan x="0" dy="1.2em">DEC</tspan>
</text>
</g>
<g transform="translate(532, 140)" class="key keypos-27">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">PREV</text>
</g>
<g transform="translate(588, 157)" class="key keypos-28">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
<text x="0" y="0" class="key tap">
<tspan x="0" dy="-0.6em">VOL</tspan><tspan x="0" dy="1.2em">DN</tspan>
</text>
</g>
<g transform="translate(644, 192)" class="key keypos-29">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key"/>
</g>
<g transform="translate(224, 238)" class="key held keypos-30">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key held"/>
</g>
<g transform="translate(280, 252)" class="key trans keypos-31">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key trans"/>
<text x="0" y="0" class="key trans tap">▽</text>
</g>
<g transform="translate(392, 252)" class="key trans keypos-32">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key trans"/>
<text x="0" y="0" class="key trans tap">▽</text>
</g>
<g transform="translate(448, 238)" class="key held keypos-33">
<rect rx="6" ry="6" x="-26" y="-26" width="52" height="52" class="key held"/>
</g>
<g class="combo combopos-0">
<rect rx="6" ry="6" x="42" y="50" width="28" height="26" class="combo"/>
<text x="56" y="63" class="combo tap">ESC</text>
</g>
<g class="combo combopos-1">
<path d="M336,252 l-37,0" class="combo"/>
<path d="M336,252 l37,0" class="combo"/>
<rect rx="6" ry="6" x="322" y="239" width="28" height="26" class="combo"/>
<text x="336" y="252" class="combo tap">ENTER</text>
</g>
</g>
</g>
</svg>
