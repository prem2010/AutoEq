# Fostex TH900

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -4.3dB
GraphicEQ: 10 -84; 20 -3.4; 22 -3.7; 23 -3.9; 25 -4.1; 26 -4.1; 28 -4.3; 30 -4.3; 32 -4.4; 35 -4.4; 37 -4.5; 40 -4.5; 42 -4.4; 45 -4.3; 49 -4.1; 52 -4.0; 56 -4.1; 59 -4.3; 64 -4.5; 68 -4.6; 73 -4.8; 78 -5.0; 83 -5.2; 89 -5.4; 95 -5.6; 102 -5.7; 109 -5.6; 117 -5.6; 125 -5.7; 134 -5.6; 143 -5.5; 153 -5.4; 164 -5.0; 175 -4.9; 188 -4.8; 201 -4.5; 215 -4.3; 230 -3.9; 246 -3.6; 263 -3.3; 282 -2.9; 301 -2.5; 323 -2.0; 345 -1.4; 369 -0.7; 395 0.0; 423 1.0; 452 1.8; 484 2.6; 518 3.6; 554 4.1; 593 4.1; 635 3.2; 679 2.0; 726 1.8; 777 1.8; 832 0.9; 890 0.2; 952 0.0; 1019 0.0; 1090 0.0; 1167 0.2; 1248 0.4; 1336 0.4; 1429 0.2; 1529 0.0; 1636 -0.2; 1751 -0.2; 1873 0.2; 2004 1.5; 2145 3.1; 2295 3.1; 2455 2.9; 2627 3.2; 2811 2.5; 3008 1.7; 3219 1.5; 3444 1.7; 3685 2.2; 3943 2.8; 4219 1.2; 4514 -0.1; 4830 -0.6; 5168 -0.4; 5530 -1.2; 5917 -2.5; 6331 -2.4; 6775 -2.2; 7249 -1.8; 7756 -1.3; 8299 -0.3; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -1.0; 18692 -3.1; 20000 -4.7
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-4.312619567187761dB` and instead set Global volume in the UI for both channels to **-43**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Fostex TH900 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -4.3dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 27 Hz   | 0.86 | -3.3 dB |
| Peaking | 130 Hz  | 0.45 | -5.5 dB |
| Peaking | 545 Hz  | 2    | 5.5 dB  |
| Peaking | 2703 Hz | 1.64 | 3.1 dB  |
| Peaking | 6363 Hz | 3.02 | -3.0 dB |
| Peaking | 1847 Hz | 3.09 | -1.9 dB |
| Peaking | 2149 Hz | 3.72 | 2.3 dB  |
| Peaking | 3488 Hz | 1.74 | -1.3 dB |
| Peaking | 3871 Hz | 5.9  | 3.1 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Fostex%20TH900/Fostex%20TH900.png)