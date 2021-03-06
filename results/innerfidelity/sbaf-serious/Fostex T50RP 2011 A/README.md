# Fostex T50RP 2011 A

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 5.5; 117 5.0; 125 4.3; 134 3.8; 143 3.3; 153 3.0; 164 2.9; 175 2.4; 188 2.1; 201 1.9; 215 1.6; 230 1.5; 246 1.4; 263 1.5; 282 1.7; 301 1.8; 323 2.1; 345 2.2; 369 2.1; 395 1.9; 423 1.9; 452 1.7; 484 1.5; 518 1.8; 554 1.8; 593 2.1; 635 1.6; 679 1.6; 726 1.4; 777 1.5; 832 1.3; 890 0.7; 952 0.1; 1019 0.2; 1090 0.5; 1167 0.7; 1248 0.7; 1336 0.4; 1429 -0.0; 1529 -0.4; 1636 -0.7; 1751 -0.1; 1873 0.7; 2004 1.9; 2145 3.1; 2295 4.2; 2455 5.6; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Fostex T50RP 2011 A ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.0dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 29 Hz   | 0.33 | 5.9 dB  |
| Peaking | 96 Hz   | 1.22 | 3.0 dB  |
| Peaking | 430 Hz  | 1.26 | 1.6 dB  |
| Peaking | 4371 Hz | 0.79 | 7.1 dB  |
| Peaking | 8603 Hz | 1.91 | -2.9 dB |
| Peaking | 1565 Hz | 4.21 | -1.0 dB |
| Peaking | 1753 Hz | 2.81 | -2.1 dB |
| Peaking | 2583 Hz | 2.3  | 3.0 dB  |
| Peaking | 4702 Hz | 0.84 | -1.4 dB |
| Peaking | 6109 Hz | 3.99 | 2.6 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Fostex%20T50RP%202011%20A/Fostex%20T50RP%202011%20A.png)