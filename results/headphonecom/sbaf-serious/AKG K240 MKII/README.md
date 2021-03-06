# AKG K240 MKII

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.2dB
GraphicEQ: 10 -84; 20 6.1; 22 5.3; 23 4.9; 25 4.2; 26 3.9; 28 3.3; 30 2.8; 32 2.3; 35 1.6; 37 1.2; 40 0.7; 42 0.4; 45 0.2; 49 -0.3; 52 -0.7; 56 -1.1; 59 -0.9; 64 -0.9; 68 -1.7; 73 -2.9; 78 -3.7; 83 -4.3; 89 -4.8; 95 -5.4; 102 -5.8; 109 -6.0; 117 -6.3; 125 -6.5; 134 -6.7; 143 -6.7; 153 -6.5; 164 -6.1; 175 -6.2; 188 -5.9; 201 -5.7; 215 -5.4; 230 -5.1; 246 -4.7; 263 -4.6; 282 -4.5; 301 -4.4; 323 -4.3; 345 -4.0; 369 -3.8; 395 -3.5; 423 -3.4; 452 -3.4; 484 -3.4; 518 -0.9; 554 -0.2; 593 -1.0; 635 -1.1; 679 -1.0; 726 -0.9; 777 -0.7; 832 -0.5; 890 -0.2; 952 -0.1; 1019 0.1; 1090 0.4; 1167 0.5; 1248 0.6; 1336 0.2; 1429 -0.4; 1529 -1.0; 1636 -1.5; 1751 -2.3; 1873 -2.9; 2004 -2.9; 2145 -3.9; 2295 -3.7; 2455 -3.4; 2627 -2.1; 2811 -1.3; 3008 -0.4; 3219 1.0; 3444 1.8; 3685 1.7; 3943 0.5; 4219 -0.3; 4514 -0.9; 4830 -0.7; 5168 1.1; 5530 2.1; 5917 1.3; 6331 -0.1; 6775 -1.9; 7249 -3.0; 7756 -5.4; 8299 -8.1; 8880 -9.8; 9502 -9.1; 10167 -6.0; 10879 -2.5; 11640 -0.3; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.218146045396237dB` and instead set Global volume in the UI for both channels to **-62**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `AKG K240 MKII ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -5.0dB.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 13 Hz   | 0.18 | 6.3 dB   |
| Peaking | 126 Hz  | 0.38 | -7.9 dB  |
| Peaking | 2173 Hz | 1.8  | -6.0 dB  |
| Peaking | 4012 Hz | 0.22 | 2.6 dB   |
| Peaking | 8932 Hz | 2.51 | -12.6 dB |
| Peaking | 63 Hz   | 7.03 | 1.3 dB   |
| Peaking | 236 Hz  | 5.12 | 0.6 dB   |
| Peaking | 3566 Hz | 4.75 | 2.5 dB   |
| Peaking | 4778 Hz | 2.05 | -3.3 dB  |
| Peaking | 5467 Hz | 4.34 | 3.9 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/AKG%20K240%20MKII/AKG%20K240%20MKII.png)