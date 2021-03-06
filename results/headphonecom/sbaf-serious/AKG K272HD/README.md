# AKG K272HD

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 5.9; 49 5.6; 52 5.2; 56 4.3; 59 3.6; 64 2.4; 68 1.7; 73 1.3; 78 1.3; 83 1.6; 89 2.4; 95 3.0; 102 2.6; 109 1.5; 117 0.3; 125 -0.6; 134 -1.2; 143 -1.6; 153 -1.9; 164 -1.7; 175 -1.4; 188 -0.9; 201 -0.5; 215 -0.6; 230 -0.8; 246 -0.7; 263 -0.8; 282 -0.9; 301 -0.8; 323 -0.8; 345 -0.9; 369 -1.2; 395 -1.4; 423 -1.4; 452 -1.6; 484 -1.5; 518 -1.7; 554 -1.8; 593 -2.2; 635 -3.2; 679 -3.0; 726 -0.3; 777 0.2; 832 0.5; 890 0.6; 952 0.3; 1019 -0.1; 1090 -0.6; 1167 -1.0; 1248 -1.5; 1336 -1.8; 1429 -2.6; 1529 -3.5; 1636 -4.1; 1751 -4.0; 1873 -3.1; 2004 -0.5; 2145 3.0; 2295 3.0; 2455 3.7; 2627 3.0; 2811 3.0; 3008 2.7; 3219 2.7; 3444 3.5; 3685 4.6; 3943 4.8; 4219 4.2; 4514 4.0; 4830 4.9; 5168 5.9; 5530 6.0; 5917 5.8; 6331 3.5; 6775 3.1; 7249 1.3; 7756 0.3; 8299 -1.3; 8880 -5.5; 9502 -6.7; 10167 -4.3; 10879 -0.6; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000001dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `AKG K272HD ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.0dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 32 Hz   | 0.86 | 6.9 dB  |
| Peaking | 1832 Hz | 1.79 | -8.4 dB |
| Peaking | 2198 Hz | 2.36 | 7.5 dB  |
| Peaking | 5167 Hz | 1    | 5.9 dB  |
| Peaking | 9316 Hz | 3.73 | -9.1 dB |
| Peaking | 99 Hz   | 5.13 | 2.6 dB  |
| Peaking | 149 Hz  | 2.24 | -2.3 dB |
| Peaking | 498 Hz  | 1.02 | -1.8 dB |
| Peaking | 657 Hz  | 4.84 | -4.1 dB |
| Peaking | 757 Hz  | 1.85 | 2.9 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/AKG%20K272HD/AKG%20K272HD.png)