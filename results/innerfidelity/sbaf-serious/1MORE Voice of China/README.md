# 1MORE Voice of China

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -3.4dB
GraphicEQ: 10 -84; 20 1.3; 22 0.7; 23 0.4; 25 -0.2; 26 -0.4; 28 -0.9; 30 -1.3; 32 -1.6; 35 -2.1; 37 -2.4; 40 -2.8; 42 -3.0; 45 -3.4; 49 -3.8; 52 -4.0; 56 -4.4; 59 -4.6; 64 -5.0; 68 -5.2; 73 -5.5; 78 -5.8; 83 -6.1; 89 -6.4; 95 -6.6; 102 -6.8; 109 -6.8; 117 -7.0; 125 -7.0; 134 -7.1; 143 -7.2; 153 -7.1; 164 -7.1; 175 -6.9; 188 -6.8; 201 -6.7; 215 -6.4; 230 -6.1; 246 -5.9; 263 -5.6; 282 -5.2; 301 -4.8; 323 -4.5; 345 -4.1; 369 -3.7; 395 -3.3; 423 -2.8; 452 -2.4; 484 -2.1; 518 -1.8; 554 -1.3; 593 -0.7; 635 -0.4; 679 -0.3; 726 -0.0; 777 0.4; 832 0.5; 890 0.4; 952 0.2; 1019 0.0; 1090 -0.1; 1167 -0.3; 1248 -0.4; 1336 -0.9; 1429 -0.9; 1529 -1.4; 1636 -1.8; 1751 -2.1; 1873 -2.2; 2004 -2.2; 2145 -2.5; 2295 -3.0; 2455 -3.4; 2627 -3.6; 2811 -3.9; 3008 -3.2; 3219 -2.6; 3444 -1.7; 3685 -1.7; 3943 -2.4; 4219 -4.5; 4514 -6.4; 4830 -7.6; 5168 -7.0; 5530 -4.1; 5917 -0.4; 6331 1.9; 6775 3.3; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 -0.3; 10879 -0.2; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-3.445513352299784dB` and instead set Global volume in the UI for both channels to **-34**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `1MORE Voice of China ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-3.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -3.3dB.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 103 Hz  |  0.58 | -6.2 dB |
| Peaking | 239 Hz  |  1.03 | -3.4 dB |
| Peaking | 2506 Hz |  1.87 | -3.4 dB |
| Peaking | 4935 Hz |  3.44 | -8.3 dB |
| Peaking | 6581 Hz |  4.36 | 4.8 dB  |
| Peaking | 19 Hz   |  2.3  | 1.9 dB  |
| Peaking | 408 Hz  |  2.45 | -0.7 dB |
| Peaking | 812 Hz  |  1.82 | 1.3 dB  |
| Peaking | 1666 Hz |  4.4  | -0.9 dB |
| Peaking | 3669 Hz | 10.81 | 1.0 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/1MORE%20Voice%20of%20China/1MORE%20Voice%20of%20China.png)