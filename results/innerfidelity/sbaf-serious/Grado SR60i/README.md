# Grado SR60i

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 5.8; 32 5.4; 35 4.7; 37 4.2; 40 3.5; 42 3.0; 45 2.4; 49 1.6; 52 1.1; 56 0.6; 59 0.2; 64 -0.2; 68 -0.6; 73 -1.0; 78 -1.2; 83 -1.5; 89 -1.8; 95 -2.0; 102 -2.1; 109 -2.2; 117 -2.2; 125 -2.3; 134 -2.3; 143 -2.3; 153 -2.2; 164 -2.2; 175 -2.0; 188 -1.9; 201 -1.9; 215 -1.6; 230 -1.3; 246 -1.1; 263 -1.1; 282 -0.9; 301 -0.8; 323 -0.8; 345 -0.7; 369 -0.6; 395 -0.5; 423 -0.3; 452 -0.2; 484 -0.2; 518 -0.2; 554 0.0; 593 0.3; 635 0.4; 679 0.3; 726 0.3; 777 0.4; 832 0.3; 890 0.2; 952 0.1; 1019 -0.0; 1090 0.0; 1167 -0.3; 1248 -0.6; 1336 -1.1; 1429 -1.8; 1529 -2.6; 1636 -3.2; 1751 -3.9; 1873 -7.0; 2004 -9.7; 2145 -9.1; 2295 -7.2; 2455 -5.1; 2627 -3.5; 2811 -1.9; 3008 -1.3; 3219 -1.4; 3444 -1.5; 3685 -0.7; 3943 1.2; 4219 1.7; 4514 1.5; 4830 2.1; 5168 1.0; 5530 0.2; 5917 1.9; 6331 2.6; 6775 -0.3; 7249 -1.6; 7756 -1.5; 8299 -1.6; 8880 -1.8; 9502 -0.6; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Grado SR60i ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.4dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 26 Hz    | 0.77 | 6.8 dB   |
| Peaking | 109 Hz   | 0.56 | -3.0 dB  |
| Peaking | 2087 Hz  | 2.22 | -12.0 dB |
| Peaking | 2229 Hz  | 0.52 | 2.4 dB   |
| Peaking | 21501 Hz | 1.75 | -0.7 dB  |
| Peaking | 629 Hz   | 4.69 | 0.4 dB   |
| Peaking | 3431 Hz  | 6.87 | -2.0 dB  |
| Peaking | 6390 Hz  | 1.14 | 2.6 dB   |
| Peaking | 7837 Hz  | 2.14 | -4.2 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Grado%20SR60i/Grado%20SR60i.png)