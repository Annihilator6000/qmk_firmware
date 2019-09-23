# UT47.2 Planck-style layout switching keymap

This keymap has layouts for Qwerty, Workman, Colemak, Colemak-Mod-DH, and Dvorak. Qwerty is the default layout. Layouts are switched Planck-style using the Lower and Raise at the same time and pressing one of the H, J, K, L, or ; keys (this is while on the Qwerty layout - adjust if on another layout). See Layer 8 below for layout swapping keys.

You can load the ut472_annihilator6000_configurator_file.json file in the [QMK Configurator](https://config.qmk.fm/#/ut472/LAYOUT) if you want to check out the configuration there or easily modify it.

Make example for this keyboard (after setting up your build environment):

    make ut472:annihilator6000

To flash this board without removing the bottom plate to press the reset button you can instead:
1. Start up QMK Toolbox
2. Open the ut472_annihilator6000.hex file in it
3. Set the Microcontroller field to atmega32u2
4. Unplug the UT47.2
5. Hold the spacebar and B keys down at the same time
6. Plug the keyboard back in and wait a few seconds
7. Release the spacebar and B keys

This should put the keyboard into DFU (flashing) mode in QMK Toolbox. You should see a message in yellow that says `DFU Device connected: ATmega32U2`.

If you get that message you can press the `Flash` button to flash the new keymap hex file to the keyboard.

---

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

![UT47.2 layout image](https://i.imgur.com/lICX4uz.png)

[KLE](http://www.keyboard-layout-editor.com/##@@_y:0%3B&=Esc&=Q&=W&=E&=R&=T&=Y&=U&=I&=O&=P&_w:1.5%3B&=Back%20Space&_x:0.25&a:4&f:4&w:4&h:4&d:true%3B&=%3Cb%3EGNAP!%3C%2F%2Fb%3E%3Cp%3E%3Cp%3EMinimum%20stagger%3Cp%3E47%20key%20layout%3B&@_a:7&f:3&w:1.25%3B&=Tab&=A&=S&=D&=F&=G&=H&=J&=K&=L&=%2F%3B&_w:1.25%3B&=%27%3B&@_w:1.5%3B&=Shift&=Z&=X&=C&=V&=B&=N&=M&=,&=.&=%2F%2F&=Return%3B&@=Ctrl&=Alt&=Super&=Menu&_w:1.25%3B&=%2F&dArr%2F%3B&_w:2%3B&=&_w:1.25%3B&=%2F&uArr%2F%3B&=%2F&larr%2F%3B&=%2F&darr%2F%3B&=%2F&uarr%2F%3B&=%2F&rarr%2F%3B%3B&=undefined)
