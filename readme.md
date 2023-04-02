# My own notes
[Youtube video that helped](https://www.youtube.com/watch?v=fR-w97o7dgg)  
[QMK setup guide](https://docs.qmk.fm/#/newbs_getting_started)  

! The keyboard is of type `redox/rev1/base`

! Compile a firmware with your new keymap by typing: `qmk compile -kb redox/rev1/base -km Motsols`.

What Joakim sent me:
> För att bygga layout kan man använda qmk’s grafiska verktyg: https://config.qmk.fm/#/redox/rev1/base/LAYOUT  
och tror att den mesta av dokumentationen som behövs finns: https://github.com/qmk/qmk_firmware  

>I bygg-guiden jag följde när jag satte ihop hela så har han något exempel på firmware också men tror inte jag testade den: https://github.com/mattdibi/redox-keyboard  

>jag körde primärt på det grafiska verktyget om jag minns rätt. Sen om det va någon setting som inte gick att få till så har jag för mig att jag skrev in den i C filer själv  

>Sen finns det hur mycket info som helst på reddit. Det är där jag grottade ner mig först för att ta reda på vad man skulle bygga osv osv :slightly_smiling_face:  

>Men fråga gärna om de är några konstigheter :slightly_smiling_face:  
https://qmk.fm/  





# Quantum Mechanical Keyboard Firmware

[![Current Version](https://img.shields.io/github/tag/qmk/qmk_firmware.svg)](https://github.com/qmk/qmk_firmware/tags)
[![Discord](https://img.shields.io/discord/440868230475677696.svg)](https://discord.gg/Uq7gcHh)
[![Docs Status](https://img.shields.io/badge/docs-ready-orange.svg)](https://docs.qmk.fm)
[![GitHub contributors](https://img.shields.io/github/contributors/qmk/qmk_firmware.svg)](https://github.com/qmk/qmk_firmware/pulse/monthly)
[![GitHub forks](https://img.shields.io/github/forks/qmk/qmk_firmware.svg?style=social&label=Fork)](https://github.com/qmk/qmk_firmware/)

This is a keyboard firmware based on the [tmk\_keyboard firmware](https://github.com/tmk/tmk_keyboard) with some useful features for Atmel AVR and ARM controllers, and more specifically, the [OLKB product line](https://olkb.com), the [ErgoDox EZ](https://ergodox-ez.com) keyboard, and the [Clueboard product line](https://clueboard.co).

## Documentation

* [See the official documentation on docs.qmk.fm](https://docs.qmk.fm)

The docs are powered by [Docsify](https://docsify.js.org/) and hosted on [GitHub](/docs/). They are also viewable offline; see [Previewing the Documentation](https://docs.qmk.fm/#/contributing?id=previewing-the-documentation) for more details.

You can request changes by making a fork and opening a [pull request](https://github.com/qmk/qmk_firmware/pulls), or by clicking the "Edit this page" link at the bottom of any page.

## Supported Keyboards

* [Planck](/keyboards/planck/)
* [Preonic](/keyboards/preonic/)
* [ErgoDox EZ](/keyboards/ergodox_ez/)
* [Clueboard](/keyboards/clueboard/)
* [Cluepad](/keyboards/clueboard/17/)
* [Atreus](/keyboards/atreus/)

The project also includes community support for [lots of other keyboards](/keyboards/).

## Maintainers

QMK is developed and maintained by Jack Humbert of OLKB with contributions from the community, and of course, [Hasu](https://github.com/tmk). The OLKB product firmwares are maintained by [Jack Humbert](https://github.com/jackhumbert), the Ergodox EZ by [ZSA Technology Labs](https://github.com/zsa), the Clueboard by [Zach White](https://github.com/skullydazed), and the Atreus by [Phil Hagelberg](https://github.com/technomancy).

## Official Website

[qmk.fm](https://qmk.fm) is the official website of QMK, where you can find links to this page, the documentation, and the keyboards supported by QMK.
