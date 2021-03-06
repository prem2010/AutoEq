# Pioneer HDJ-1000

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 5.4; 83 4.2; 89 3.1; 95 2.2; 102 1.6; 109 1.2; 117 0.9; 125 0.6; 134 0.6; 143 0.6; 153 0.7; 164 0.8; 175 0.9; 188 1.1; 201 1.1; 215 1.1; 230 1.1; 246 1.3; 263 1.4; 282 1.8; 301 1.8; 323 1.8; 345 2.0; 369 2.1; 395 2.2; 423 2.5; 452 2.7; 484 2.2; 518 1.7; 554 2.7; 593 3.2; 635 3.1; 679 2.7; 726 2.3; 777 1.7; 832 1.1; 890 0.6; 952 0.2; 1019 -0.1; 1090 -0.4; 1167 -0.9; 1248 -1.5; 1336 -2.3; 1429 -3.0; 1529 -3.4; 1636 -3.2; 1751 -2.4; 1873 -1.2; 2004 0.2; 2145 1.7; 2295 3.2; 2455 4.5; 2627 5.4; 2811 5.9; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 4.3; 4219 3.4; 4514 5.4; 4830 6.0; 5168 6.0; 5530 6.0; 5917 4.6; 6331 3.0; 6775 3.8; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Pioneer HDJ-1000 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.0dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 38 Hz   | 0.6  | 6.9 dB  |
| Peaking | 562 Hz  | 0.97 | 2.9 dB  |
| Peaking | 1594 Hz | 1.64 | -5.7 dB |
| Peaking | 2885 Hz | 1.33 | 7.0 dB  |
| Peaking | 5325 Hz | 2.85 | 4.9 dB  |
| Peaking | 41 Hz   | 2.98 | -0.9 dB |
| Peaking | 73 Hz   | 3.02 | 2.4 dB  |
| Peaking | 114 Hz  | 2.02 | -1.5 dB |
| Peaking | 6737 Hz | 9.59 | 2.2 dB  |
| Peaking | 7977 Hz | 2.17 | -1.1 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Pioneer%20HDJ-1000/Pioneer%20HDJ-1000.png)