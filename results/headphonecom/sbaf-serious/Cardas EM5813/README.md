# Cardas EM5813

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 -8.5; 22 -8.5; 23 -8.5; 25 -8.5; 26 -8.5; 28 -8.6; 30 -8.6; 32 -8.6; 35 -8.6; 37 -8.5; 40 -8.5; 42 -8.6; 45 -8.7; 49 -8.9; 52 -9.0; 56 -9.1; 59 -9.2; 64 -9.3; 68 -9.5; 73 -9.7; 78 -9.8; 83 -10.0; 89 -10.0; 95 -10.2; 102 -10.2; 109 -10.3; 117 -10.3; 125 -10.3; 134 -10.3; 143 -10.4; 153 -10.3; 164 -10.2; 175 -10.1; 188 -9.9; 201 -9.7; 215 -9.5; 230 -9.2; 246 -8.9; 263 -8.6; 282 -8.2; 301 -7.8; 323 -7.3; 345 -6.9; 369 -6.4; 395 -6.0; 423 -5.5; 452 -5.2; 484 -4.8; 518 -4.3; 554 -3.8; 593 -3.3; 635 -2.9; 679 -2.6; 726 -2.3; 777 -2.1; 832 -2.0; 890 0.1; 952 1.3; 1019 -0.1; 1090 -0.7; 1167 -1.0; 1248 -1.3; 1336 -1.7; 1429 -2.2; 1529 -2.7; 1636 -3.1; 1751 -3.4; 1873 -3.6; 2004 -4.0; 2145 -4.6; 2295 -5.7; 2455 -7.0; 2627 -6.6; 2811 -3.9; 3008 -1.3; 3219 0.6; 3444 1.5; 3685 0.9; 3943 -1.5; 4219 -5.0; 4514 -6.8; 4830 -3.5; 5168 1.5; 5530 5.5; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.07254868210109dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Cardas EM5813 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.2dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 22 Hz   | 0.24 | -7.7 dB |
| Peaking | 132 Hz  | 0.59 | -6.3 dB |
| Peaking | 295 Hz  | 0.78 | -4.4 dB |
| Peaking | 2357 Hz | 2.22 | -6.3 dB |
| Peaking | 6078 Hz | 5.49 | 7.3 dB  |
| Peaking | 954 Hz  | 6.04 | 3.3 dB  |
| Peaking | 1311 Hz | 0.55 | -0.6 dB |
| Peaking | 3457 Hz | 4.05 | 4.5 dB  |
| Peaking | 4453 Hz | 4.71 | -8.0 dB |
| Peaking | 5380 Hz | 7.58 | 4.2 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Cardas%20EM5813/Cardas%20EM5813.png)