# Yutai BAS02

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 -0.9; 22 -1.1; 23 -1.1; 25 -1.2; 26 -1.3; 28 -1.3; 30 -1.4; 32 -1.5; 35 -1.7; 37 -1.7; 40 -1.8; 42 -1.9; 45 -2.0; 49 -2.1; 52 -2.3; 56 -2.4; 59 -2.4; 64 -2.6; 68 -2.8; 73 -3.1; 78 -3.2; 83 -3.4; 89 -3.7; 95 -3.9; 102 -4.1; 109 -4.1; 117 -4.2; 125 -4.3; 134 -4.5; 143 -4.5; 153 -4.6; 164 -4.6; 175 -4.6; 188 -4.5; 201 -4.5; 215 -4.4; 230 -4.2; 246 -4.2; 263 -4.1; 282 -3.8; 301 -3.6; 323 -3.5; 345 -3.2; 369 -3.1; 395 -2.8; 423 -2.5; 452 -2.2; 484 -2.1; 518 -1.8; 554 -1.4; 593 -1.0; 635 -0.7; 679 -0.6; 726 -0.3; 777 0.1; 832 0.1; 890 0.1; 952 -0.0; 1019 -0.1; 1090 -0.2; 1167 -0.2; 1248 -0.3; 1336 -0.6; 1429 -0.8; 1529 -1.0; 1636 -1.1; 1751 -1.0; 1873 -0.7; 2004 -0.3; 2145 -0.2; 2295 -0.2; 2455 -0.1; 2627 -0.2; 2811 -0.4; 3008 0.4; 3219 2.4; 3444 5.1; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999857591355dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Yutai BAS02 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.1dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 66 Hz   | 0.39 | -1.6 dB |
| Peaking | 160 Hz  | 0.7  | -3.4 dB |
| Peaking | 333 Hz  | 1.35 | -1.6 dB |
| Peaking | 2569 Hz | 1.27 | -2.8 dB |
| Peaking | 4399 Hz | 1.25 | 7.8 dB  |
| Peaking | 1450 Hz | 0.98 | 1.4 dB  |
| Peaking | 1520 Hz | 2.1  | -2.1 dB |
| Peaking | 4607 Hz | 7.02 | -1.3 dB |
| Peaking | 6395 Hz | 3.06 | 4.3 dB  |
| Peaking | 7426 Hz | 1.77 | -3.2 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Yutai%20BAS02/Yutai%20BAS02.png)