# Koss Pro4S

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 3.7; 22 3.1; 23 2.8; 25 2.3; 26 2.0; 28 1.6; 30 1.3; 32 1.0; 35 0.6; 37 0.4; 40 0.1; 42 -0.1; 45 -0.3; 49 -0.5; 52 -0.7; 56 -0.8; 59 -0.9; 64 -1.1; 68 -1.3; 73 -1.5; 78 -1.6; 83 -1.7; 89 -1.8; 95 -1.8; 102 -1.7; 109 -1.5; 117 -1.1; 125 -0.3; 134 0.5; 143 0.6; 153 0.1; 164 0.8; 175 2.2; 188 3.1; 201 2.9; 215 3.8; 230 4.1; 246 5.5; 263 5.0; 282 4.0; 301 2.5; 323 1.3; 345 0.6; 369 0.8; 395 0.7; 423 0.5; 452 0.4; 484 0.0; 518 -0.2; 554 -0.1; 593 0.1; 635 -0.1; 679 -0.2; 726 -0.3; 777 -0.2; 832 -0.3; 890 -0.2; 952 -0.1; 1019 0.1; 1090 0.1; 1167 -0.2; 1248 -0.5; 1336 -0.8; 1429 -1.1; 1529 -1.2; 1636 -1.4; 1751 -1.6; 1873 -1.8; 2004 -2.0; 2145 -1.8; 2295 -2.4; 2455 -2.9; 2627 -3.2; 2811 -3.2; 3008 -2.5; 3219 -1.5; 3444 -0.6; 3685 0.4; 3943 2.4; 4219 4.1; 4514 5.9; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099937591843524dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Koss Pro4S ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.0dB.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 20 Hz   |  1.67 | 3.6 dB  |
| Peaking | 85 Hz   |  1.35 | -2.2 dB |
| Peaking | 241 Hz  |  2.2  | 5.4 dB  |
| Peaking | 2786 Hz |  1.18 | -4.3 dB |
| Peaking | 5016 Hz |  1.74 | 8.2 dB  |
| Peaking | 182 Hz  | 13.45 | 1.3 dB  |
| Peaking | 436 Hz  |  1.25 | -0.3 dB |
| Peaking | 5259 Hz |  7.83 | -1.6 dB |
| Peaking | 6489 Hz |  2.91 | 3.4 dB  |
| Peaking | 7520 Hz |  2.23 | -2.8 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Koss%20Pro4S/Koss%20Pro4S.png)