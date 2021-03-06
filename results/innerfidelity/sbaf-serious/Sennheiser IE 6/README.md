# Sennheiser IE 6

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -5.5dB
GraphicEQ: 10 -84; 20 -3.2; 22 -3.6; 23 -3.8; 25 -4.1; 26 -4.2; 28 -4.4; 30 -4.7; 32 -4.9; 35 -5.2; 37 -5.3; 40 -5.6; 42 -5.8; 45 -6.0; 49 -6.2; 52 -6.4; 56 -6.7; 59 -6.8; 64 -7.0; 68 -7.3; 73 -7.6; 78 -7.8; 83 -8.0; 89 -8.2; 95 -8.4; 102 -8.5; 109 -8.6; 117 -8.6; 125 -8.7; 134 -8.8; 143 -8.7; 153 -8.7; 164 -8.6; 175 -8.4; 188 -8.3; 201 -8.1; 215 -7.8; 230 -7.5; 246 -7.2; 263 -6.9; 282 -6.5; 301 -6.2; 323 -5.7; 345 -5.3; 369 -4.9; 395 -4.5; 423 -3.9; 452 -3.4; 484 -3.1; 518 -2.7; 554 -2.0; 593 -1.5; 635 -1.0; 679 -0.8; 726 -0.4; 777 0.0; 832 0.1; 890 0.2; 952 0.1; 1019 0.0; 1090 -0.0; 1167 0.0; 1248 -0.2; 1336 -0.5; 1429 -0.7; 1529 -0.7; 1636 -1.0; 1751 -1.2; 1873 -1.2; 2004 -1.1; 2145 -1.2; 2295 -1.3; 2455 -1.1; 2627 -1.3; 2811 -1.1; 3008 -0.5; 3219 -0.1; 3444 0.3; 3685 -0.4; 3943 -2.3; 4219 -5.8; 4514 -9.1; 4830 -9.0; 5168 -4.1; 5530 0.3; 5917 3.8; 6331 5.4; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-5.531493808493221dB` and instead set Global volume in the UI for both channels to **-55**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser IE 6 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -5.9dB.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 59 Hz   | 0.37 | -5.5 dB  |
| Peaking | 152 Hz  | 0.74 | -4.9 dB  |
| Peaking | 303 Hz  | 1.23 | -2.9 dB  |
| Peaking | 4669 Hz | 4.83 | -11.2 dB |
| Peaking | 6221 Hz | 4.45 | 7.1 dB   |
| Peaking | 490 Hz  | 2.49 | -0.8 dB  |
| Peaking | 865 Hz  | 1.1  | 1.3 dB   |
| Peaking | 2100 Hz | 0.89 | -1.3 dB  |
| Peaking | 3485 Hz | 5.06 | 2.2 dB   |
| Peaking | 8078 Hz | 6.35 | -0.4 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sennheiser%20IE%206/Sennheiser%20IE%206.png)