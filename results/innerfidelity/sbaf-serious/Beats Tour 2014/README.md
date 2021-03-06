# Beats Tour 2014

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 -5.7; 22 -6.0; 23 -6.2; 25 -6.5; 26 -6.6; 28 -6.8; 30 -7.0; 32 -7.2; 35 -7.4; 37 -7.5; 40 -7.6; 42 -7.7; 45 -7.9; 49 -8.1; 52 -8.2; 56 -8.3; 59 -8.5; 64 -8.6; 68 -8.7; 73 -8.9; 78 -9.0; 83 -9.2; 89 -9.4; 95 -9.5; 102 -9.5; 109 -9.4; 117 -9.4; 125 -9.4; 134 -9.3; 143 -9.3; 153 -9.1; 164 -9.0; 175 -8.7; 188 -8.4; 201 -8.2; 215 -7.8; 230 -7.5; 246 -7.2; 263 -6.8; 282 -6.3; 301 -5.9; 323 -5.5; 345 -5.1; 369 -4.6; 395 -4.2; 423 -3.6; 452 -3.2; 484 -2.8; 518 -2.4; 554 -1.8; 593 -1.2; 635 -0.9; 679 -0.6; 726 -0.3; 777 0.1; 832 0.1; 890 0.1; 952 0.0; 1019 -0.1; 1090 -0.2; 1167 -0.3; 1248 -0.3; 1336 -0.5; 1429 -0.9; 1529 -1.1; 1636 -1.2; 1751 -1.1; 1873 -0.8; 2004 -0.4; 2145 0.0; 2295 0.5; 2455 1.6; 2627 2.3; 2811 3.1; 3008 4.5; 3219 5.5; 3444 6.0; 3685 6.0; 3943 5.5; 4219 3.7; 4514 2.1; 4830 1.5; 5168 1.6; 5530 1.8; 5917 2.7; 6331 3.8; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999979483249dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Beats Tour 2014 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.2dB** and build filters manually
with these parameters. The first 4 filters can be used independently.
When using independent subset of filters, apply preamp of -6.4dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 75 Hz    | 0.42 | -7.2 dB |
| Peaking | 204 Hz   | 0.68 | -4.6 dB |
| Peaking | 3573 Hz  | 2.1  | 6.3 dB  |
| Peaking | 23026 Hz | 2.35 | 1.5 dB  |
| Peaking | 22 Hz    | 0.72 | -3.2 dB |
| Peaking | 804 Hz   | 2.54 | 1.2 dB  |
| Peaking | 1711 Hz  | 2.91 | -1.6 dB |
| Peaking | 6506 Hz  | 4.27 | 5.5 dB  |
| Peaking | 6641 Hz  | 1.59 | -1.8 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Beats%20Tour%202014/Beats%20Tour%202014.png)