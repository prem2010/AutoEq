# Fostex T50RP Mk2

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 5.8; 30 5.4; 32 5.0; 35 4.5; 37 4.2; 40 3.8; 42 3.7; 45 3.5; 49 3.3; 52 3.2; 56 3.2; 59 3.1; 64 3.0; 68 2.9; 73 2.8; 78 2.7; 83 2.6; 89 2.4; 95 2.3; 102 2.1; 109 2.0; 117 1.8; 125 1.2; 134 0.9; 143 0.6; 153 0.5; 164 0.8; 175 0.7; 188 0.3; 201 0.2; 215 0.2; 230 0.3; 246 0.4; 263 0.4; 282 0.6; 301 0.6; 323 0.7; 345 0.9; 369 1.0; 395 1.0; 423 1.1; 452 1.0; 484 0.8; 518 0.8; 554 0.7; 593 0.2; 635 0.4; 679 2.5; 726 3.1; 777 2.6; 832 2.1; 890 1.2; 952 0.5; 1019 -0.3; 1090 -1.2; 1167 -1.6; 1248 -1.6; 1336 -1.4; 1429 -0.4; 1529 -0.6; 1636 -1.2; 1751 -1.0; 1873 0.3; 2004 2.5; 2145 4.6; 2295 5.5; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Fostex T50RP Mk2 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.0dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 22 Hz   | 0.76 | 6.0 dB  |
| Peaking | 78 Hz   | 0.98 | 1.8 dB  |
| Peaking | 752 Hz  | 3.71 | 3.1 dB  |
| Peaking | 1494 Hz | 1.3  | -5.2 dB |
| Peaking | 3110 Hz | 0.66 | 7.7 dB  |
| Peaking | 1830 Hz | 5.29 | -2.9 dB |
| Peaking | 2135 Hz | 1.86 | 2.3 dB  |
| Peaking | 3176 Hz | 2.01 | -1.5 dB |
| Peaking | 6262 Hz | 2.05 | 5.9 dB  |
| Peaking | 7371 Hz | 1.43 | -4.8 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Fostex%20T50RP%20Mk2/Fostex%20T50RP%20Mk2.png)