# KRK Systems KNS 6400

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 5.1; 22 4.9; 23 4.8; 25 4.5; 26 4.4; 28 4.2; 30 4.0; 32 3.9; 35 3.7; 37 3.7; 40 3.5; 42 3.5; 45 3.8; 49 4.8; 52 5.2; 56 5.5; 59 5.8; 64 6.0; 68 6.0; 73 5.7; 78 4.3; 83 2.8; 89 1.6; 95 0.9; 102 0.2; 109 -0.2; 117 -0.8; 125 -1.4; 134 -1.9; 143 -2.3; 153 -1.9; 164 -1.5; 175 -2.7; 188 -3.8; 201 -4.3; 215 -4.7; 230 -4.3; 246 -3.4; 263 -3.6; 282 -3.8; 301 -3.9; 323 -4.1; 345 -3.9; 369 -3.4; 395 -2.7; 423 -1.9; 452 -1.4; 484 -1.0; 518 -1.1; 554 -1.5; 593 -2.0; 635 -2.0; 679 -1.3; 726 0.4; 777 0.2; 832 -0.9; 890 -0.3; 952 -0.1; 1019 0.0; 1090 -0.3; 1167 -0.7; 1248 -0.9; 1336 -0.8; 1429 -0.8; 1529 -1.1; 1636 -0.9; 1751 -2.1; 1873 -3.0; 2004 -3.6; 2145 -3.6; 2295 -3.5; 2455 -3.9; 2627 -3.6; 2811 -2.7; 3008 -0.8; 3219 -1.1; 3444 0.1; 3685 2.5; 3943 1.2; 4219 0.8; 4514 0.8; 4830 2.6; 5168 3.0; 5530 3.0; 5917 0.1; 6331 -1.7; 6775 -2.0; 7249 0.2; 7756 0.3; 8299 0.0; 8880 -1.3; 9502 -3.0; 10167 -1.8; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 -1.7; 20000 -7.6
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000001dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `KRK Systems KNS 6400 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.4dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 17 Hz   | 0.6  | 5.1 dB  |
| Peaking | 67 Hz   | 1.47 | 7.1 dB  |
| Peaking | 94 Hz   | 1.03 | -2.1 dB |
| Peaking | 250 Hz  | 0.9  | -4.3 dB |
| Peaking | 2234 Hz | 2.7  | -4.3 dB |
| Peaking | 2692 Hz | 6.37 | -2.0 dB |
| Peaking | 5348 Hz | 6.1  | 2.4 dB  |
| Peaking | 5412 Hz | 0.98 | 2.1 dB  |
| Peaking | 6416 Hz | 4.81 | -4.2 dB |
| Peaking | 9589 Hz | 5.95 | -3.9 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/KRK%20Systems%20KNS%206400/KRK%20Systems%20KNS%206400.png)