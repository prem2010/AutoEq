# PSB M4U 4

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 -1.1; 22 -1.4; 23 -1.5; 25 -1.8; 26 -1.9; 28 -2.0; 30 -2.2; 32 -2.3; 35 -2.4; 37 -2.4; 40 -2.4; 42 -2.5; 45 -2.4; 49 -2.4; 52 -2.4; 56 -2.4; 59 -2.4; 64 -2.4; 68 -2.4; 73 -2.4; 78 -2.4; 83 -2.4; 89 -2.4; 95 -2.4; 102 -2.3; 109 -2.2; 117 -2.1; 125 -2.0; 134 -1.9; 143 -1.7; 153 -1.6; 164 -1.4; 175 -1.2; 188 -1.1; 201 -0.9; 215 -0.6; 230 -0.4; 246 -0.3; 263 -0.1; 282 0.2; 301 0.3; 323 0.5; 345 0.7; 369 0.8; 395 0.9; 423 1.2; 452 1.2; 484 1.2; 518 1.2; 554 1.3; 593 1.5; 635 1.5; 679 1.3; 726 1.2; 777 1.2; 832 1.0; 890 0.6; 952 0.3; 1019 -0.0; 1090 -0.3; 1167 -0.7; 1248 -0.6; 1336 -0.9; 1429 -1.2; 1529 -1.7; 1636 -1.8; 1751 -1.9; 1873 -1.8; 2004 -1.6; 2145 -1.5; 2295 -1.4; 2455 -0.9; 2627 -0.4; 2811 0.1; 3008 0.8; 3219 1.2; 3444 1.4; 3685 1.7; 3943 2.1; 4219 1.4; 4514 1.8; 4830 3.7; 5168 5.9; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.097714767088152dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `PSB M4U 4 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.8dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 66 Hz   | 0.3  | -2.6 dB |
| Peaking | 701 Hz  | 0.51 | 3.2 dB  |
| Peaking | 2464 Hz | 0.37 | -4.5 dB |
| Peaking | 3272 Hz | 1.48 | 4.1 dB  |
| Peaking | 5711 Hz | 2.22 | 8.5 dB  |
| Peaking | 6675 Hz | 7.7  | 2.1 dB  |
| Peaking | 7229 Hz | 2.15 | -1.7 dB |
| Peaking | 9110 Hz | 0.72 | 0.5 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/PSB%20M4U%204/PSB%20M4U%204.png)