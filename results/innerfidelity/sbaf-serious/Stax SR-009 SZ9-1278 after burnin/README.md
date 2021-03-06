# Stax SR-009 SZ9-1278 after burnin

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 5.6; 59 5.0; 64 4.5; 68 4.5; 73 4.6; 78 4.6; 83 4.5; 89 4.4; 95 4.2; 102 4.0; 109 4.0; 117 3.9; 125 3.7; 134 3.5; 143 3.4; 153 3.3; 164 3.1; 175 3.0; 188 3.0; 201 2.9; 215 2.9; 230 2.9; 246 2.8; 263 2.6; 282 2.6; 301 2.6; 323 2.5; 345 2.5; 369 2.4; 395 2.4; 423 2.3; 452 2.2; 484 1.8; 518 1.7; 554 1.8; 593 1.8; 635 1.5; 679 1.3; 726 1.2; 777 1.3; 832 1.4; 890 1.1; 952 0.5; 1019 -0.1; 1090 -0.1; 1167 -0.6; 1248 -0.4; 1336 -0.5; 1429 -0.7; 1529 -1.0; 1636 -1.4; 1751 -0.7; 1873 0.4; 2004 1.5; 2145 2.0; 2295 2.8; 2455 3.9; 2627 4.1; 2811 3.1; 3008 2.7; 3219 2.4; 3444 3.5; 3685 3.5; 3943 2.1; 4219 1.3; 4514 0.2; 4830 -0.5; 5168 0.9; 5530 5.2; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -0.9
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Stax SR-009 SZ9-1278 after burnin ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.7dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 16 Hz   | 0.05 | 5.0 dB  |
| Peaking | 2545 Hz | 2.45 | 6.7 dB  |
| Peaking | 3487 Hz | 0.71 | -4.5 dB |
| Peaking | 3610 Hz | 3.22 | 6.0 dB  |
| Peaking | 6038 Hz | 3.36 | 8.4 dB  |
| Peaking | 36 Hz   | 0.73 | 1.4 dB  |
| Peaking | 166 Hz  | 0.42 | -1.2 dB |
| Peaking | 520 Hz  | 0.52 | 1.2 dB  |
| Peaking | 1649 Hz | 1.79 | -1.5 dB |
| Peaking | 1997 Hz | 5.3  | 1.6 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Stax%20SR-009%20SZ9-1278%20after%20burnin/Stax%20SR-009%20SZ9-1278%20after%20burnin.png)