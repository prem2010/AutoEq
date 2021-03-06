# Sennheiser HD 800 S

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -5.0dB
GraphicEQ: 10 -84; 20 4.9; 22 4.4; 23 4.1; 25 3.7; 26 3.5; 28 3.2; 30 2.9; 32 2.6; 35 2.3; 37 2.1; 40 1.8; 42 1.7; 45 1.5; 49 1.4; 52 1.3; 56 1.1; 59 1.0; 64 1.0; 68 0.9; 73 0.7; 78 0.2; 83 -0.3; 89 -0.6; 95 -1.0; 102 -1.4; 109 -1.7; 117 -1.9; 125 -2.2; 134 -2.4; 143 -2.6; 153 -2.7; 164 -2.7; 175 -2.8; 188 -2.9; 201 -3.0; 215 -3.0; 230 -3.0; 246 -3.0; 263 -3.0; 282 -2.8; 301 -2.8; 323 -2.7; 345 -2.6; 369 -2.5; 395 -2.4; 423 -2.1; 452 -2.0; 484 -2.0; 518 -1.9; 554 -1.6; 593 -1.3; 635 -1.2; 679 -1.2; 726 -1.0; 777 -0.6; 832 -0.5; 890 -0.4; 952 -0.1; 1019 0.1; 1090 0.5; 1167 0.5; 1248 0.9; 1336 1.3; 1429 1.5; 1529 1.8; 1636 1.7; 1751 1.6; 1873 1.5; 2004 1.7; 2145 1.7; 2295 1.6; 2455 2.1; 2627 2.5; 2811 2.1; 3008 1.9; 3219 2.1; 3444 2.3; 3685 1.1; 3943 0.3; 4219 -0.2; 4514 -0.0; 4830 0.1; 5168 -0.4; 5530 -1.3; 5917 -1.2; 6331 -3.6; 6775 -4.2; 7249 -3.0; 7756 -1.9; 8299 -1.1; 8880 -0.5; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -0.3
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-5.003500267927264dB` and instead set Global volume in the UI for both channels to **-50**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 800 S ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -4.8dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 15 Hz   | 0.53 | 5.4 dB  |
| Peaking | 69 Hz   | 1.45 | 1.8 dB  |
| Peaking | 201 Hz  | 0.34 | -3.2 dB |
| Peaking | 2151 Hz | 0.67 | 2.3 dB  |
| Peaking | 6712 Hz | 3.21 | -4.6 dB |
| Peaking | 1494 Hz | 3.01 | 1.1 dB  |
| Peaking | 1734 Hz | 1.36 | -0.9 dB |
| Peaking | 3489 Hz | 2.12 | 1.3 dB  |
| Peaking | 4059 Hz | 4.24 | -1.7 dB |
| Peaking | 9870 Hz | 5.17 | 0.3 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sennheiser%20HD%20800%20S/Sennheiser%20HD%20800%20S.png)