# Grado SR 80

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 5.6; 64 4.8; 68 4.0; 73 3.1; 78 2.2; 83 1.6; 89 0.9; 95 0.4; 102 0.0; 109 -0.2; 117 -0.6; 125 -0.8; 134 -1.0; 143 -1.1; 153 -1.1; 164 -1.0; 175 -0.9; 188 -0.8; 201 -0.8; 215 -0.8; 230 -0.7; 246 -0.5; 263 -0.3; 282 -0.1; 301 -0.1; 323 0.0; 345 0.2; 369 0.3; 395 0.4; 423 0.4; 452 0.5; 484 0.6; 518 0.6; 554 0.6; 593 0.7; 635 0.7; 679 0.7; 726 0.7; 777 0.6; 832 0.6; 890 0.4; 952 0.2; 1019 -0.1; 1090 -0.3; 1167 -0.6; 1248 -1.0; 1336 -1.6; 1429 -2.4; 1529 -3.2; 1636 -3.9; 1751 -4.5; 1873 -5.2; 2004 -5.9; 2145 -6.1; 2295 -6.1; 2455 -5.6; 2627 -5.3; 2811 -4.9; 3008 -4.4; 3219 -4.1; 3444 -4.4; 3685 -6.9; 3943 -10.2; 4219 -7.9; 4514 -4.7; 4830 -4.3; 5168 -4.6; 5530 -6.1; 5917 -6.8; 6331 -3.8; 6775 -4.4; 7249 -6.0; 7756 -7.5; 8299 -9.2; 8880 -10.6; 9502 -10.8; 10167 -9.0; 10879 -5.3; 11640 -1.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -5.4
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Grado SR 80 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.2dB.

| Type    | Fc       |     Q | Gain     |
|:--------|:---------|:------|:---------|
| Peaking | 35 Hz    |  0.88 | 7.1 dB   |
| Peaking | 2116 Hz  |  1.89 | -5.8 dB  |
| Peaking | 4034 Hz  |  2.65 | -7.3 dB  |
| Peaking | 8948 Hz  |  2.23 | -11.1 dB |
| Peaking | 20396 Hz |  4.02 | -6.8 dB  |
| Peaking | 62 Hz    |  2.88 | 2.5 dB   |
| Peaking | 137 Hz   |  0.9  | -1.8 dB  |
| Peaking | 623 Hz   |  1.11 | 1.1 dB   |
| Peaking | 5774 Hz  | 11.51 | -4.0 dB  |
| Peaking | 12557 Hz |  4.07 | 2.7 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Grado%20SR%2080/Grado%20SR%2080.png)