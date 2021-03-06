# Beyerdynamic DT 48 E pad holes c

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 4.6; 73 -0.8; 78 -3.8; 83 -2.8; 89 -0.5; 95 0.3; 102 -1.6; 109 -2.0; 117 -1.5; 125 -1.1; 134 -0.8; 143 -0.4; 153 0.2; 164 0.4; 175 -0.8; 188 -0.2; 201 0.2; 215 0.6; 230 1.1; 246 1.5; 263 2.0; 282 2.5; 301 2.9; 323 3.4; 345 3.8; 369 4.3; 395 4.9; 423 5.7; 452 6.0; 484 6.0; 518 6.0; 554 6.0; 593 6.0; 635 6.0; 679 6.0; 726 5.9; 777 4.9; 832 3.5; 890 2.1; 952 1.0; 1019 -0.3; 1090 -1.1; 1167 -1.8; 1248 -2.0; 1336 -2.4; 1429 -2.8; 1529 -3.5; 1636 -4.4; 1751 -5.0; 1873 -4.9; 2004 -4.9; 2145 -4.3; 2295 -3.0; 2455 -0.7; 2627 1.4; 2811 2.9; 3008 3.5; 3219 3.6; 3444 4.3; 3685 5.4; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.2; 7756 -3.4; 8299 -7.0; 8880 -6.7; 9502 -3.7; 10167 -0.4; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 -1.4; 15258 -5.0; 16326 -6.5; 17469 -5.7; 18692 -2.7; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Beyerdynamic DT 48 E pad holes c ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.3dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 34 Hz    | 1.12 | 7.3 dB   |
| Peaking | 512 Hz   | 1.56 | 7.1 dB   |
| Peaking | 5213 Hz  | 1.52 | 7.6 dB   |
| Peaking | 8505 Hz  | 4.77 | -10.0 dB |
| Peaking | 16702 Hz | 2.25 | -7.4 dB  |
| Peaking | 64 Hz    | 2.66 | 5.5 dB   |
| Peaking | 77 Hz    | 5.63 | -7.8 dB  |
| Peaking | 114 Hz   | 2.9  | -2.7 dB  |
| Peaking | 737 Hz   | 5.28 | 3.4 dB   |
| Peaking | 1747 Hz  | 2.18 | -6.3 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Beyerdynamic%20DT%2048%20E%20pad%20holes%20c/Beyerdynamic%20DT%2048%20E%20pad%20holes%20c.png)