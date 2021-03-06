# Audio Technica ATH-AD700

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 5.9; 83 5.3; 89 4.8; 95 4.3; 102 3.9; 109 3.7; 117 3.4; 125 3.0; 134 2.7; 143 2.5; 153 2.3; 164 2.3; 175 2.0; 188 1.9; 201 1.7; 215 1.6; 230 1.6; 246 1.5; 263 1.5; 282 1.6; 301 1.6; 323 1.7; 345 1.6; 369 1.6; 395 1.7; 423 1.8; 452 1.7; 484 1.6; 518 1.5; 554 1.6; 593 1.7; 635 1.6; 679 1.5; 726 1.3; 777 1.3; 832 1.0; 890 0.5; 952 0.3; 1019 -0.0; 1090 -0.1; 1167 -0.4; 1248 -0.6; 1336 -0.8; 1429 -1.1; 1529 -1.0; 1636 -0.6; 1751 -0.7; 1873 -0.5; 2004 -0.3; 2145 -0.1; 2295 0.5; 2455 1.0; 2627 1.3; 2811 1.0; 3008 1.2; 3219 0.8; 3444 2.3; 3685 4.7; 3943 4.4; 4219 1.4; 4514 0.1; 4830 1.4; 5168 4.2; 5530 5.9; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 -0.8; 10167 -0.6; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Audio Technica ATH-AD700 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 43 Hz   | 0.23 | 6.4 dB  |
| Peaking | 149 Hz  | 1.04 | -1.9 dB |
| Peaking | 554 Hz  | 1.8  | 1.2 dB  |
| Peaking | 3767 Hz | 6.96 | 4.8 dB  |
| Peaking | 5900 Hz | 3.87 | 6.7 dB  |
| Peaking | 1495 Hz | 2.25 | -1.3 dB |
| Peaking | 2609 Hz | 4.72 | 1.2 dB  |
| Peaking | 4565 Hz | 8.75 | -1.9 dB |
| Peaking | 5248 Hz | 9.8  | 1.5 dB  |
| Peaking | 9583 Hz | 4.28 | -1.2 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Audio%20Technica%20ATH-AD700/Audio%20Technica%20ATH-AD700.png)