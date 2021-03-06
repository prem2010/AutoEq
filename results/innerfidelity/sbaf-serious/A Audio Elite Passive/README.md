# A Audio Elite Passive

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.0dB
GraphicEQ: 10 -84; 20 -1.8; 22 -1.9; 23 -1.9; 25 -2.0; 26 -2.1; 28 -2.1; 30 -2.2; 32 -2.2; 35 -2.2; 37 -2.2; 40 -2.2; 42 -2.2; 45 -2.2; 49 -2.2; 52 -2.1; 56 -2.1; 59 -2.1; 64 -2.0; 68 -1.9; 73 -1.8; 78 -1.8; 83 -1.9; 89 -2.3; 95 -2.3; 102 -2.5; 109 -2.5; 117 -2.4; 125 -2.8; 134 -3.3; 143 -3.3; 153 -3.0; 164 -1.9; 175 -2.2; 188 -2.1; 201 -1.4; 215 -0.5; 230 0.2; 246 0.8; 263 1.3; 282 1.4; 301 1.8; 323 1.9; 345 1.9; 369 1.8; 395 1.5; 423 1.3; 452 1.2; 484 0.7; 518 0.3; 554 0.4; 593 0.8; 635 1.1; 679 1.0; 726 0.4; 777 -0.2; 832 -0.4; 890 -0.3; 952 -0.1; 1019 0.1; 1090 0.3; 1167 0.5; 1248 0.9; 1336 1.1; 1429 1.1; 1529 1.0; 1636 1.0; 1751 1.2; 1873 1.8; 2004 2.4; 2145 3.2; 2295 3.8; 2455 4.3; 2627 4.7; 2811 4.7; 3008 4.4; 3219 3.8; 3444 3.8; 3685 2.8; 3943 1.2; 4219 -0.5; 4514 -1.1; 4830 0.1; 5168 2.5; 5530 4.3; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-5.97675394329972dB` and instead set Global volume in the UI for both channels to **-59**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `A Audio Elite Passive ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.7dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 33 Hz   | 0.49 | -2.1 dB |
| Peaking | 149 Hz  | 1.08 | -3.2 dB |
| Peaking | 306 Hz  | 1.28 | 2.8 dB  |
| Peaking | 2676 Hz | 2    | 5.0 dB  |
| Peaking | 6104 Hz | 5    | 6.3 dB  |
| Peaking | 3549 Hz | 5.48 | 1.7 dB  |
| Peaking | 3864 Hz | 3.72 | 0.3 dB  |
| Peaking | 4526 Hz | 3.57 | -3.6 dB |
| Peaking | 5277 Hz | 4.44 | 2.2 dB  |
| Peaking | 8322 Hz | 4.42 | -0.6 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/A%20Audio%20Elite%20Passive/A%20Audio%20Elite%20Passive.png)