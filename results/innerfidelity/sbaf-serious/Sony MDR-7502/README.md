# Sony MDR-7502

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 5.8; 143 5.0; 153 4.3; 164 4.3; 175 4.2; 188 3.6; 201 3.4; 215 3.3; 230 3.0; 246 2.8; 263 2.8; 282 2.7; 301 2.8; 323 3.0; 345 2.9; 369 2.4; 395 2.3; 423 2.3; 452 1.8; 484 1.3; 518 1.0; 554 1.2; 593 1.4; 635 1.4; 679 1.2; 726 1.1; 777 1.1; 832 0.7; 890 0.3; 952 0.1; 1019 -0.1; 1090 -0.5; 1167 -0.9; 1248 -1.4; 1336 -1.6; 1429 -1.9; 1529 -2.5; 1636 -3.3; 1751 -3.6; 1873 -3.6; 2004 -3.3; 2145 -3.2; 2295 -2.5; 2455 -1.3; 2627 -0.2; 2811 0.6; 3008 1.7; 3219 2.3; 3444 2.8; 3685 3.4; 3943 4.3; 4219 4.7; 4514 5.7; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -1.7; 9502 -2.2; 10167 -0.1; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDR-7502 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.4dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 15 Hz   | 0.09 | 5.7 dB  |
| Peaking | 182 Hz  | 0.24 | 1.6 dB  |
| Peaking | 1911 Hz | 1.37 | -5.3 dB |
| Peaking | 5628 Hz | 0.84 | 8.4 dB  |
| Peaking | 8502 Hz | 1.47 | -5.9 dB |
| Peaking | 122 Hz  | 1.67 | 2.0 dB  |
| Peaking | 143 Hz  | 0.73 | -1.3 dB |
| Peaking | 341 Hz  | 3.81 | 0.7 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sony%20MDR-7502/Sony%20MDR-7502.png)