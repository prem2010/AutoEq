# Ortofon 0-One

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 5.8; 42 5.6; 45 5.4; 49 5.1; 52 5.0; 56 5.3; 59 5.7; 64 5.8; 68 5.0; 73 3.8; 78 3.1; 83 2.6; 89 2.3; 95 2.2; 102 2.3; 109 2.3; 117 2.2; 125 2.0; 134 2.1; 143 2.3; 153 2.6; 164 2.9; 175 3.1; 188 3.6; 201 3.9; 215 4.6; 230 5.3; 246 5.9; 263 6.0; 282 6.0; 301 6.0; 323 5.1; 345 3.3; 369 1.6; 395 0.3; 423 -0.4; 452 -0.7; 484 -1.0; 518 -1.0; 554 -0.6; 593 -0.2; 635 1.4; 679 3.0; 726 2.2; 777 1.3; 832 0.7; 890 0.3; 952 0.1; 1019 -0.1; 1090 0.6; 1167 1.9; 1248 1.6; 1336 1.0; 1429 0.2; 1529 -0.6; 1636 -0.3; 1751 1.0; 1873 3.3; 2004 5.4; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 5.5; 3943 3.0; 4219 3.7; 4514 6.0; 4830 3.6; 5168 2.3; 5530 3.1; 5917 5.8; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.8; 9502 -0.2; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -0.2; 17469 -0.7; 18692 -2.5; 20000 -6.4
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000001dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Ortofon 0-One ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 28 Hz   | 0.41 | 6.1 dB  |
| Peaking | 63 Hz   | 4.97 | 2.1 dB  |
| Peaking | 259 Hz  | 2.09 | 6.2 dB  |
| Peaking | 2899 Hz | 1.28 | 6.7 dB  |
| Peaking | 6125 Hz | 5.18 | 5.1 dB  |
| Peaking | 487 Hz  | 3.15 | -2.4 dB |
| Peaking | 689 Hz  | 7.37 | 3.0 dB  |
| Peaking | 1613 Hz | 5.11 | -3.0 dB |
| Peaking | 2070 Hz | 5.97 | 2.7 dB  |
| Peaking | 8837 Hz | 4.15 | -1.4 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Ortofon%200-One/Ortofon%200-One.png)