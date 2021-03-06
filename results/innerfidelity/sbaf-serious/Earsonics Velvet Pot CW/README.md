# Earsonics Velvet Pot CW

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 -3.2; 22 -3.5; 23 -3.6; 25 -3.9; 26 -3.9; 28 -4.1; 30 -4.2; 32 -4.3; 35 -4.4; 37 -4.4; 40 -4.5; 42 -4.6; 45 -4.7; 49 -4.8; 52 -4.8; 56 -4.9; 59 -4.9; 64 -5.0; 68 -5.0; 73 -5.0; 78 -5.0; 83 -5.0; 89 -5.0; 95 -4.9; 102 -4.6; 109 -4.3; 117 -4.0; 125 -3.7; 134 -3.2; 143 -2.8; 153 -2.2; 164 -1.6; 175 -0.8; 188 -0.0; 201 0.8; 215 1.6; 230 2.4; 246 3.1; 263 3.5; 282 4.0; 301 4.1; 323 4.0; 345 3.8; 369 3.5; 395 3.2; 423 2.9; 452 2.5; 484 2.1; 518 1.8; 554 1.8; 593 1.8; 635 1.6; 679 1.4; 726 1.2; 777 1.2; 832 0.9; 890 0.6; 952 0.3; 1019 -0.0; 1090 -0.3; 1167 -0.6; 1248 -0.9; 1336 -1.2; 1429 -1.5; 1529 -1.7; 1636 -1.7; 1751 -1.3; 1873 -0.3; 2004 1.1; 2145 2.7; 2295 3.6; 2455 4.7; 2627 5.8; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 5.7; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.2; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999999964643dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Earsonics Velvet Pot CW ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 31 Hz   | 0.4  | -3.3 dB |
| Peaking | 121 Hz  | 0.52 | -4.7 dB |
| Peaking | 279 Hz  | 0.85 | 6.5 dB  |
| Peaking | 1578 Hz | 1.83 | -4.6 dB |
| Peaking | 3522 Hz | 0.78 | 7.2 dB  |
| Peaking | 1854 Hz | 8.18 | -0.7 dB |
| Peaking | 2608 Hz | 2.91 | 1.2 dB  |
| Peaking | 3479 Hz | 2.51 | -1.2 dB |
| Peaking | 6259 Hz | 2.44 | 5.3 dB  |
| Peaking | 7204 Hz | 1.43 | -4.0 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Earsonics%20Velvet%20Pot%20CW/Earsonics%20Velvet%20Pot%20CW.png)