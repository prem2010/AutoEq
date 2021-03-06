# JAYS q-Jays

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 1.3; 22 1.3; 23 1.3; 25 1.3; 26 1.3; 28 1.2; 30 1.1; 32 1.0; 35 0.9; 37 0.9; 40 0.8; 42 0.8; 45 0.7; 49 0.5; 52 0.4; 56 0.2; 59 0.0; 64 -0.1; 68 -0.2; 73 -0.4; 78 -0.6; 83 -0.8; 89 -1.1; 95 -1.3; 102 -1.5; 109 -1.6; 117 -1.8; 125 -1.8; 134 -2.0; 143 -2.2; 153 -2.3; 164 -2.5; 175 -2.6; 188 -2.7; 201 -2.6; 215 -2.6; 230 -2.6; 246 -2.4; 263 -2.4; 282 -2.3; 301 -2.1; 323 -1.8; 345 -1.6; 369 -1.8; 395 -1.9; 423 -1.7; 452 -1.5; 484 -1.2; 518 -1.0; 554 -0.7; 593 -0.4; 635 -0.2; 679 -0.1; 726 0.1; 777 0.2; 832 0.3; 890 0.3; 952 0.2; 1019 0.0; 1090 -0.1; 1167 -0.1; 1248 -0.1; 1336 -0.3; 1429 -0.6; 1529 -1.2; 1636 -1.8; 1751 -2.2; 1873 -2.0; 2004 -1.7; 2145 -1.2; 2295 -0.5; 2455 0.6; 2627 2.2; 2811 4.5; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -1.5; 8880 -5.0; 9502 -5.3; 10167 -1.6; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999999437615dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `JAYS q-Jays ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.8dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 192 Hz   | 0.87 | -2.7 dB |
| Peaking | 420 Hz   | 2.01 | -1.1 dB |
| Peaking | 1979 Hz  | 1.35 | -7.4 dB |
| Peaking | 3672 Hz  | 0.54 | 8.4 dB  |
| Peaking | 9122 Hz  | 3.36 | -8.9 dB |
| Peaking | 27 Hz    | 1.01 | 1.5 dB  |
| Peaking | 3023 Hz  | 6.77 | 2.0 dB  |
| Peaking | 3792 Hz  | 1.06 | -0.7 dB |
| Peaking | 6052 Hz  | 5.63 | 1.7 dB  |
| Peaking | 14552 Hz | 1.98 | -0.6 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/JAYS%20q-Jays/JAYS%20q-Jays.png)