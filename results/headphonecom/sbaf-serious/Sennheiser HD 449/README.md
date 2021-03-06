# Sennheiser HD 449

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 4.4; 22 3.6; 23 3.3; 25 2.7; 26 2.4; 28 1.9; 30 1.4; 32 1.0; 35 0.4; 37 -0.0; 40 -0.5; 42 -0.8; 45 -1.2; 49 -1.6; 52 -1.9; 56 -2.3; 59 -2.5; 64 -2.8; 68 -2.9; 73 -2.8; 78 -2.7; 83 -2.6; 89 -2.6; 95 -2.0; 102 -0.6; 109 0.3; 117 -0.9; 125 -2.9; 134 -3.9; 143 -3.9; 153 -3.1; 164 -1.7; 175 -3.0; 188 -3.7; 201 -3.3; 215 -3.0; 230 -3.4; 246 -3.1; 263 -2.3; 282 -1.2; 301 -0.4; 323 0.1; 345 0.6; 369 0.8; 395 1.2; 423 1.6; 452 1.7; 484 1.5; 518 1.6; 554 1.6; 593 1.2; 635 0.7; 679 0.4; 726 0.3; 777 0.2; 832 0.3; 890 0.2; 952 -0.1; 1019 0.0; 1090 0.1; 1167 0.0; 1248 -0.6; 1336 -1.4; 1429 -1.9; 1529 -2.3; 1636 -2.2; 1751 -2.0; 1873 -1.4; 2004 -0.6; 2145 0.5; 2295 2.1; 2455 2.7; 2627 2.7; 2811 3.3; 3008 3.7; 3219 3.6; 3444 3.8; 3685 4.5; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999017734476dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 449 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.0dB** and build filters manually
with these parameters. The first 4 filters can be used independently.
When using independent subset of filters, apply preamp of -7.0dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 20 Hz   | 1.39 | 4.7 dB  |
| Peaking | 65 Hz   | 1.36 | -3.0 dB |
| Peaking | 187 Hz  | 1.76 | -3.5 dB |
| Peaking | 4685 Hz | 1.41 | 6.9 dB  |
| Peaking | 249 Hz  | 5.31 | -1.8 dB |
| Peaking | 456 Hz  | 1.46 | 2.0 dB  |
| Peaking | 1689 Hz | 2.07 | -3.5 dB |
| Peaking | 2520 Hz | 2.22 | 2.2 dB  |
| Peaking | 8525 Hz | 3.89 | -1.7 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sennheiser%20HD%20449/Sennheiser%20HD%20449.png)