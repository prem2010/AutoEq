# Munitio Pro40

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 1.7; 22 0.8; 23 0.4; 25 -0.4; 26 -0.8; 28 -1.5; 30 -2.1; 32 -2.6; 35 -3.3; 37 -3.7; 40 -4.1; 42 -4.3; 45 -4.6; 49 -4.8; 52 -4.9; 56 -5.0; 59 -5.0; 64 -5.0; 68 -5.1; 73 -5.2; 78 -5.3; 83 -5.6; 89 -5.9; 95 -6.2; 102 -6.5; 109 -6.6; 117 -6.6; 125 -6.8; 134 -6.9; 143 -7.1; 153 -7.2; 164 -6.9; 175 -7.1; 188 -7.2; 201 -7.3; 215 -7.3; 230 -7.2; 246 -7.2; 263 -7.0; 282 -6.7; 301 -6.2; 323 -5.4; 345 -4.6; 369 -4.1; 395 -3.5; 423 -3.1; 452 -2.2; 484 -1.2; 518 0.1; 554 1.8; 593 3.7; 635 5.3; 679 5.9; 726 5.5; 777 4.5; 832 2.9; 890 1.5; 952 0.6; 1019 0.0; 1090 0.1; 1167 0.8; 1248 1.4; 1336 1.7; 1429 1.7; 1529 2.1; 1636 2.5; 1751 3.3; 1873 4.0; 2004 4.5; 2145 5.2; 2295 5.7; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 5.9; 3685 5.8; 3943 5.9; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -0.8
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.0999999999983245dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Munitio Pro40 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 14 Hz   | 0.61 | 4.1 dB  |
| Peaking | 38 Hz   | 0.95 | -3.3 dB |
| Peaking | 195 Hz  | 0.33 | -7.4 dB |
| Peaking | 659 Hz  | 2.24 | 9.2 dB  |
| Peaking | 3384 Hz | 0.7  | 6.9 dB  |
| Peaking | 1039 Hz | 6.43 | -1.4 dB |
| Peaking | 2240 Hz | 2.96 | 1.1 dB  |
| Peaking | 3456 Hz | 2.58 | -1.2 dB |
| Peaking | 6266 Hz | 2.07 | 6.0 dB  |
| Peaking | 7369 Hz | 1.46 | -4.9 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Munitio%20Pro40/Munitio%20Pro40.png)