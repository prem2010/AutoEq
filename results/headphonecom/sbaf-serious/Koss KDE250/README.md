# Koss KDE250

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 6.0; 143 6.0; 153 5.7; 164 5.2; 175 4.7; 188 4.3; 201 3.9; 215 3.5; 230 3.1; 246 2.6; 263 2.2; 282 1.9; 301 1.7; 323 1.5; 345 1.4; 369 1.2; 395 1.3; 423 1.3; 452 1.3; 484 1.5; 518 1.5; 554 1.5; 593 1.5; 635 1.5; 679 1.5; 726 1.4; 777 1.3; 832 1.1; 890 0.9; 952 0.4; 1019 -0.1; 1090 -0.5; 1167 -1.0; 1248 -1.7; 1336 -2.7; 1429 -4.1; 1529 -5.7; 1636 -7.1; 1751 -8.0; 1873 -9.1; 2004 -10.7; 2145 -13.0; 2295 -15.4; 2455 -16.1; 2627 -14.8; 2811 -13.5; 3008 -11.9; 3219 -8.1; 3444 -3.8; 3685 -0.3; 3943 1.7; 4219 4.2; 4514 6.0; 4830 4.9; 5168 2.8; 5530 2.4; 5917 2.6; 6331 1.1; 6775 -2.0; 7249 -5.5; 7756 -7.9; 8299 -8.5; 8880 -7.4; 9502 -5.9; 10167 -5.0; 10879 -5.2; 11640 -5.7; 12455 -5.5; 13327 -3.2; 14260 -0.2; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Koss KDE250 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.6dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 53 Hz    | 0.23 | 6.5 dB   |
| Peaking | 991 Hz   | 0.95 | 4.8 dB   |
| Peaking | 2566 Hz  | 1.02 | -23.3 dB |
| Peaking | 4520 Hz  | 1.06 | 17.4 dB  |
| Peaking | 8546 Hz  | 1.24 | -10.2 dB |
| Peaking | 17 Hz    | 2.08 | 1.0 dB   |
| Peaking | 6343 Hz  | 4.3  | 5.3 dB   |
| Peaking | 7184 Hz  | 1.36 | -5.5 dB  |
| Peaking | 10725 Hz | 0.88 | 6.0 dB   |
| Peaking | 12084 Hz | 2.62 | -7.2 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Koss%20KDE250/Koss%20KDE250.png)