# Sennheiser RS 220

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 5.9; 26 5.8; 28 5.5; 30 5.1; 32 4.8; 35 4.3; 37 4.0; 40 3.6; 42 3.4; 45 3.1; 49 2.7; 52 2.5; 56 2.1; 59 1.8; 64 1.7; 68 2.2; 73 2.2; 78 1.1; 83 0.4; 89 0.0; 95 -0.4; 102 -0.6; 109 -0.9; 117 -1.1; 125 -1.2; 134 -1.4; 143 -1.6; 153 -1.6; 164 -1.4; 175 -1.6; 188 -1.7; 201 -1.7; 215 -1.5; 230 -1.2; 246 -1.0; 263 -0.9; 282 -0.9; 301 -0.8; 323 -0.7; 345 -0.5; 369 -0.4; 395 -0.5; 423 -0.5; 452 -0.4; 484 -0.1; 518 0.2; 554 0.3; 593 0.3; 635 0.4; 679 0.4; 726 0.4; 777 0.4; 832 0.4; 890 0.3; 952 0.2; 1019 -0.1; 1090 0.2; 1167 -0.2; 1248 -0.3; 1336 0.3; 1429 2.1; 1529 3.8; 1636 4.3; 1751 4.2; 1873 4.0; 2004 2.4; 2145 -0.3; 2295 -2.8; 2455 -3.9; 2627 -3.2; 2811 -1.7; 3008 -0.6; 3219 0.1; 3444 1.3; 3685 3.7; 3943 5.8; 4219 6.0; 4514 6.0; 4830 6.0; 5168 5.2; 5530 2.1; 5917 3.0; 6331 5.2; 6775 2.1; 7249 -0.7; 7756 -0.5; 8299 0.0; 8880 0.0; 9502 -0.4; 10167 -1.3; 10879 -0.3; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1000000000000005dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser RS 220 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.7dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 24 Hz   | 1.52 | 6.1 dB  |
| Peaking | 43 Hz   | 2.01 | 2.2 dB  |
| Peaking | 1812 Hz | 2.68 | 7.1 dB  |
| Peaking | 2439 Hz | 1.9  | -6.6 dB |
| Peaking | 4397 Hz | 1.92 | 7.3 dB  |
| Peaking | 71 Hz   | 4.18 | 1.9 dB  |
| Peaking | 162 Hz  | 0.91 | -1.9 dB |
| Peaking | 6430 Hz | 8.67 | 4.8 dB  |
| Peaking | 6652 Hz | 6.55 | 1.4 dB  |
| Peaking | 6930 Hz | 2.53 | -2.8 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sennheiser%20RS%20220/Sennheiser%20RS%20220.png)