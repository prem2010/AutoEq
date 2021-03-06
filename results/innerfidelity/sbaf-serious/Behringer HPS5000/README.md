# Behringer HPS5000

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 5.9; 117 5.5; 125 5.1; 134 4.9; 143 4.6; 153 4.3; 164 4.2; 175 4.2; 188 4.0; 201 3.9; 215 3.8; 230 3.8; 246 3.8; 263 4.0; 282 4.2; 301 4.5; 323 4.5; 345 4.5; 369 4.5; 395 4.5; 423 3.6; 452 3.5; 484 3.3; 518 3.3; 554 3.4; 593 3.5; 635 3.4; 679 3.1; 726 2.8; 777 2.5; 832 1.7; 890 0.9; 952 0.3; 1019 -0.1; 1090 -0.4; 1167 -0.9; 1248 -0.7; 1336 -0.9; 1429 -2.7; 1529 -3.7; 1636 -3.8; 1751 -3.4; 1873 -2.1; 2004 -0.3; 2145 1.5; 2295 3.5; 2455 5.6; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 5.4; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Behringer HPS5000 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.0dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 44 Hz   | 0.21 | 6.3 dB  |
| Peaking | 358 Hz  | 1.76 | 2.6 dB  |
| Peaking | 635 Hz  | 2.49 | 2.3 dB  |
| Peaking | 1656 Hz | 1.95 | -7.7 dB |
| Peaking | 3284 Hz | 0.72 | 7.6 dB  |
| Peaking | 1047 Hz | 6.73 | -0.8 dB |
| Peaking | 2525 Hz | 7.18 | 1.7 dB  |
| Peaking | 3463 Hz | 2.62 | -1.0 dB |
| Peaking | 6181 Hz | 2.32 | 5.5 dB  |
| Peaking | 7452 Hz | 1.44 | -4.2 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Behringer%20HPS5000/Behringer%20HPS5000.png)