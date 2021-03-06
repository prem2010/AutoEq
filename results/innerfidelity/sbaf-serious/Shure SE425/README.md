# Shure SE425

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 5.9; 26 5.8; 28 5.6; 30 5.4; 32 5.2; 35 5.0; 37 4.8; 40 4.5; 42 4.3; 45 4.1; 49 3.8; 52 3.6; 56 3.2; 59 3.0; 64 2.6; 68 2.3; 73 2.0; 78 1.6; 83 1.2; 89 0.8; 95 0.5; 102 0.2; 109 -0.1; 117 -0.3; 125 -0.6; 134 -0.9; 143 -1.1; 153 -1.3; 164 -1.4; 175 -1.5; 188 -1.6; 201 -1.7; 215 -1.7; 230 -1.8; 246 -1.8; 263 -1.8; 282 -1.7; 301 -1.6; 323 -1.6; 345 -1.5; 369 -1.4; 395 -1.3; 423 -1.0; 452 -0.9; 484 -0.8; 518 -0.7; 554 -0.4; 593 -0.0; 635 0.1; 679 0.2; 726 0.3; 777 0.5; 832 0.5; 890 0.3; 952 0.2; 1019 0.0; 1090 -0.2; 1167 -0.3; 1248 -0.5; 1336 -0.8; 1429 -1.1; 1529 -1.5; 1636 -1.7; 1751 -2.0; 1873 -2.0; 2004 -2.0; 2145 -2.1; 2295 -2.1; 2455 -1.3; 2627 -0.5; 2811 0.4; 3008 1.7; 3219 2.6; 3444 3.3; 3685 3.5; 3943 3.6; 4219 3.1; 4514 3.0; 4830 3.9; 5168 5.5; 5530 6.0; 5917 5.9; 6331 4.8; 6775 2.8; 7249 0.7; 7756 0.2; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Shure SE425 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.7dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 24 Hz   | 1.28 | 6.1 dB  |
| Peaking | 48 Hz   | 1.93 | 2.9 dB  |
| Peaking | 2208 Hz | 1.31 | -3.2 dB |
| Peaking | 3487 Hz | 1.9  | 4.3 dB  |
| Peaking | 5667 Hz | 3.35 | 6.1 dB  |
| Peaking | 77 Hz   | 1.87 | 1.1 dB  |
| Peaking | 232 Hz  | 0.56 | -2.0 dB |
| Peaking | 772 Hz  | 1.56 | 1.2 dB  |
| Peaking | 8132 Hz | 4.37 | -0.9 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Shure%20SE425/Shure%20SE425.png)