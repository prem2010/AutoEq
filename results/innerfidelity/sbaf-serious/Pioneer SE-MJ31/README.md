# Pioneer SE-MJ31

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 5.8; 68 4.9; 73 3.6; 78 2.4; 83 1.5; 89 0.6; 95 -0.1; 102 -0.5; 109 -0.5; 117 -0.7; 125 -1.0; 134 -1.1; 143 -1.2; 153 -1.1; 164 -1.2; 175 -0.8; 188 -0.6; 201 -0.6; 215 -0.5; 230 -0.2; 246 -0.2; 263 -0.1; 282 0.2; 301 0.1; 323 -0.1; 345 0.2; 369 0.2; 395 0.1; 423 0.0; 452 -0.1; 484 -0.2; 518 -0.3; 554 -0.4; 593 -0.4; 635 -0.6; 679 -0.8; 726 -0.8; 777 -0.7; 832 -0.6; 890 0.1; 952 0.3; 1019 -0.1; 1090 -1.1; 1167 -2.4; 1248 -3.9; 1336 -5.8; 1429 -7.0; 1529 -6.4; 1636 -7.0; 1751 -8.2; 1873 -7.1; 2004 -4.7; 2145 -2.2; 2295 0.4; 2455 1.8; 2627 3.3; 2811 4.9; 3008 5.9; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 4.7; 6775 -1.2; 7249 -2.8; 7756 -0.8; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.4; 16326 -0.7; 17469 -0.9; 18692 -1.8; 20000 -3.4
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Pioneer SE-MJ31 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.0dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 50 Hz    | 0.37 | 8.3 dB   |
| Peaking | 112 Hz   | 0.82 | -6.5 dB  |
| Peaking | 1713 Hz  | 1.78 | -11.8 dB |
| Peaking | 3601 Hz  | 0.73 | 8.3 dB   |
| Peaking | 7324 Hz  | 5.58 | -6.4 dB  |
| Peaking | 995 Hz   | 3.39 | 4.0 dB   |
| Peaking | 1019 Hz  | 1.75 | -2.4 dB  |
| Peaking | 3910 Hz  | 6.19 | -0.9 dB  |
| Peaking | 5927 Hz  | 6.41 | 2.9 dB   |
| Peaking | 20912 Hz | 0.2  | -1.7 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Pioneer%20SE-MJ31/Pioneer%20SE-MJ31.png)