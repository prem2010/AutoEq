# Bose QuietComfort 25 Passive

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 2.5; 22 1.7; 23 1.3; 25 0.6; 26 0.3; 28 -0.3; 30 -0.8; 32 -1.4; 35 -2.1; 37 -2.5; 40 -3.1; 42 -3.4; 45 -4.0; 49 -4.6; 52 -4.9; 56 -5.4; 59 -5.7; 64 -6.1; 68 -6.3; 73 -6.4; 78 -6.5; 83 -6.4; 89 -6.2; 95 -6.1; 102 -6.0; 109 -6.2; 117 -6.2; 125 -5.6; 134 -5.1; 143 -5.6; 153 -6.8; 164 -4.9; 175 -4.0; 188 -4.8; 201 -4.7; 215 -4.1; 230 -3.0; 246 -2.4; 263 -1.8; 282 -0.8; 301 -0.1; 323 0.6; 345 1.1; 369 1.4; 395 1.6; 423 1.8; 452 1.9; 484 1.7; 518 1.5; 554 1.4; 593 1.3; 635 0.9; 679 0.4; 726 -0.0; 777 -0.3; 832 -0.7; 890 -0.9; 952 -0.6; 1019 0.2; 1090 1.1; 1167 2.3; 1248 3.5; 1336 4.5; 1429 5.7; 1529 5.8; 1636 6.0; 1751 6.0; 1873 6.0; 2004 6.0; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 5.9; 3219 5.1; 3444 4.8; 3685 4.9; 3943 5.0; 4219 5.3; 4514 5.9; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.1; 6331 4.4; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000001dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Bose QuietComfort 25 Passive ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.8dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 20 Hz   | 1.87 | 3.1 dB  |
| Peaking | 73 Hz   | 0.83 | -6.4 dB |
| Peaking | 159 Hz  | 1.7  | -3.7 dB |
| Peaking | 2132 Hz | 0.94 | 6.4 dB  |
| Peaking | 5131 Hz | 1.99 | 5.1 dB  |
| Peaking | 224 Hz  | 3.33 | -1.8 dB |
| Peaking | 424 Hz  | 1.17 | 2.3 dB  |
| Peaking | 901 Hz  | 2.03 | -2.9 dB |
| Peaking | 1415 Hz | 4.31 | 2.2 dB  |
| Peaking | 8510 Hz | 3.78 | -1.4 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Bose%20QuietComfort%2025%20Passive/Bose%20QuietComfort%2025%20Passive.png)