# Vsonic VC1000

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 3.2; 22 3.1; 23 3.0; 25 2.9; 26 2.9; 28 2.9; 30 2.8; 32 2.8; 35 2.6; 37 2.5; 40 2.4; 42 2.3; 45 2.2; 49 2.1; 52 1.9; 56 1.8; 59 1.6; 64 1.3; 68 1.1; 73 0.8; 78 0.4; 83 0.1; 89 -0.2; 95 -0.5; 102 -0.7; 109 -0.9; 117 -1.0; 125 -1.2; 134 -1.5; 143 -1.6; 153 -1.7; 164 -1.9; 175 -2.0; 188 -2.1; 201 -2.2; 215 -2.1; 230 -2.1; 246 -2.2; 263 -2.2; 282 -2.1; 301 -2.0; 323 -2.0; 345 -1.8; 369 -1.7; 395 -1.6; 423 -1.3; 452 -1.2; 484 -1.2; 518 -1.0; 554 -0.7; 593 -0.3; 635 -0.2; 679 -0.2; 726 0.0; 777 0.3; 832 0.2; 890 0.2; 952 0.1; 1019 -0.0; 1090 -0.1; 1167 -0.2; 1248 -0.3; 1336 -0.5; 1429 -0.6; 1529 -0.6; 1636 -0.5; 1751 -0.4; 1873 -0.0; 2004 0.4; 2145 0.6; 2295 0.9; 2455 1.4; 2627 2.4; 2811 4.1; 3008 5.9; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 4.1; 4514 2.0; 4830 2.6; 5168 4.5; 5530 5.7; 5917 6.0; 6331 5.7; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 -1.4; 10879 -3.6; 11640 -3.7; 12455 -1.2; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.101835143632008dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Vsonic VC1000 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc       |     Q | Gain    |
|:--------|:---------|:------|:--------|
| Peaking | 26 Hz    |  0.39 | 3.1 dB  |
| Peaking | 195 Hz   |  0.56 | -2.6 dB |
| Peaking | 3408 Hz  |  2.45 | 6.6 dB  |
| Peaking | 5951 Hz  |  3.55 | 6.0 dB  |
| Peaking | 11229 Hz |  4.36 | -4.5 dB |
| Peaking | 818 Hz   |  1.45 | 1.4 dB  |
| Peaking | 1403 Hz  |  0.43 | -0.9 dB |
| Peaking | 2926 Hz  |  9.36 | 1.9 dB  |
| Peaking | 3985 Hz  | 14.44 | 2.0 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Vsonic%20VC1000/Vsonic%20VC1000.png)