# Devnagari : FPM Font Package

This repository contains a [fpm font package](https://fpm.dev/featured/fonts/) containing [Google Font: 
Rubik Iso](https://fonts.google.com/specimen/Rubik+Iso/about).

The Generative Fonts is an original, script-generated collection of fonts based on the Google Fonts Rubik by Hubert and Fischer, Meir Sadan and Cyreal. 

Designers: Luke Prowse, Principal design

## How To Use This Font In Your FPM Package:

[Read the docs and demo](https://jahanvir.github.io/rubik-font).

TLRD:

Include jahanvir.github.io/rubik-font package into `FPM.ftd` file:

```ftd
;-- fpm.dependency: jahanvir.github.io/rubik-font
```

Inside your `FPM/config.ftd` use the font:

```ftd
;-- import: jahanvir.github.io/rubik-font/assets as inter

;-- fpm.type.headline-small: $rubik.fonts.Rubik-Iso
```

Now if in any file you do:

```ftd
;-- ftd.text:
role: $fpm.type.headline-small
```

You will see the `rubik` font.

## 👀 Want to learn more?

Feel free to check [our documentation](https://fpm.dev/) or jump into our [FifthTry Discord 
server](https://discord.gg/bucrdvptYd).

## License

Since Rubik Font is under [Open Font Licence](https://fonts.google.com/specimen/Rubik+Iso/about), this FPM wrapper is also
under [Open Font Licence](LICENSE).
