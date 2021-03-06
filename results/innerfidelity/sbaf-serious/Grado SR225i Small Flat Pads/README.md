# Grado SR225i Small Flat Pads

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 5.8; 45 5.2; 49 4.1; 52 3.3; 56 2.5; 59 1.9; 64 1.1; 68 0.5; 73 0.0; 78 -0.4; 83 -0.8; 89 -1.0; 95 -1.3; 102 -1.4; 109 -1.5; 117 -1.6; 125 -1.8; 134 -1.9; 143 -1.9; 153 -2.0; 164 -2.0; 175 -2.0; 188 -2.0; 201 -2.0; 215 -1.8; 230 -1.6; 246 -1.6; 263 -1.4; 282 -1.2; 301 -1.3; 323 -1.4; 345 -1.2; 369 -1.0; 395 -1.0; 423 -0.8; 452 -0.7; 484 -0.7; 518 -0.6; 554 -0.4; 593 -0.1; 635 0.0; 679 0.0; 726 0.1; 777 0.2; 832 0.2; 890 0.1; 952 0.1; 1019 0.1; 1090 0.2; 1167 0.1; 1248 -0.0; 1336 -0.3; 1429 -0.9; 1529 -1.2; 1636 -1.2; 1751 -1.3; 1873 -2.3; 2004 -4.9; 2145 -5.6; 2295 -3.8; 2455 -1.1; 2627 0.9; 2811 2.3; 3008 3.1; 3219 4.0; 3444 3.6; 3685 3.4; 3943 4.6; 4219 5.9; 4514 6.0; 4830 5.8; 5168 5.0; 5530 5.4; 5917 5.9; 6331 4.6; 6775 1.7; 7249 -0.2; 7756 -0.8; 8299 -1.2; 8880 -1.5; 9502 -0.3; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Grado SR225i Small Flat Pads ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.6dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 34 Hz    | 0.56 | 9.2 dB  |
| Peaking | 82 Hz    | 0.39 | -4.6 dB |
| Peaking | 2098 Hz  | 3.73 | -7.6 dB |
| Peaking | 5387 Hz  | 0.82 | 8.1 dB  |
| Peaking | 7982 Hz  | 1.54 | -6.3 dB |
| Peaking | 1489 Hz  | 8.06 | -1.0 dB |
| Peaking | 3270 Hz  | 4.32 | 1.3 dB  |
| Peaking | 3611 Hz  | 8.23 | -1.9 dB |
| Peaking | 9874 Hz  | 6.39 | 0.7 dB  |
| Peaking | 13683 Hz | 0.97 | -0.4 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Grado%20SR225i%20Small%20Flat%20Pads/Grado%20SR225i%20Small%20Flat%20Pads.png)