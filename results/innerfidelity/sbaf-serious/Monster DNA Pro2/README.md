# Monster DNA Pro2

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.5dB
GraphicEQ: 10 -84; 20 6.4; 22 5.0; 23 4.3; 25 3.2; 26 2.7; 28 1.8; 30 1.0; 32 0.4; 35 -0.4; 37 -0.7; 40 -1.1; 42 -1.2; 45 -1.4; 49 -1.4; 52 -1.4; 56 -1.4; 59 -1.3; 64 -1.3; 68 -1.3; 73 -1.3; 78 -1.3; 83 -1.3; 89 -1.3; 95 -1.2; 102 -1.2; 109 -1.3; 117 -1.4; 125 -1.6; 134 -1.8; 143 -1.8; 153 -1.9; 164 -1.7; 175 -1.5; 188 -1.6; 201 -1.7; 215 -1.5; 230 -1.3; 246 -1.3; 263 -1.0; 282 -0.4; 301 0.2; 323 0.8; 345 1.5; 369 2.0; 395 3.0; 423 2.5; 452 0.9; 484 -0.2; 518 -0.6; 554 -0.8; 593 -0.8; 635 -0.9; 679 -1.2; 726 -1.2; 777 -1.0; 832 -1.0; 890 -0.9; 952 -0.5; 1019 0.2; 1090 1.1; 1167 1.9; 1248 2.6; 1336 3.3; 1429 3.1; 1529 2.8; 1636 2.0; 1751 1.0; 1873 0.0; 2004 -1.1; 2145 -2.6; 2295 -4.1; 2455 -4.9; 2627 -4.6; 2811 -3.8; 3008 -2.2; 3219 -0.8; 3444 0.5; 3685 0.4; 3943 -3.0; 4219 -3.6; 4514 -2.2; 4830 0.2; 5168 4.3; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.532139529344752dB` and instead set Global volume in the UI for both channels to **-65**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Monster DNA Pro2 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 21 Hz   |  3.5  | 5.7 dB  |
| Peaking | 1425 Hz |  3.17 | 3.9 dB  |
| Peaking | 2486 Hz |  3.35 | -5.7 dB |
| Peaking | 4297 Hz |  5.73 | -5.1 dB |
| Peaking | 5780 Hz |  3.15 | 7.2 dB  |
| Peaking | 23 Hz   |  1.65 | 2.5 dB  |
| Peaking | 92 Hz   |  0.23 | -1.7 dB |
| Peaking | 391 Hz  |  3.19 | 4.2 dB  |
| Peaking | 665 Hz  |  1.87 | -1.1 dB |
| Peaking | 3506 Hz | 11.66 | 1.9 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Monster%20DNA%20Pro2/Monster%20DNA%20Pro2.png)