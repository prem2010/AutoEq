# Nocs NS 400

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -2.7dB
GraphicEQ: 10 -84; 20 -12.4; 22 -12.4; 23 -12.3; 25 -12.2; 26 -12.2; 28 -12.1; 30 -12.0; 32 -11.9; 35 -11.8; 37 -11.7; 40 -11.6; 42 -11.5; 45 -11.4; 49 -11.2; 52 -11.2; 56 -11.0; 59 -11.0; 64 -10.9; 68 -10.8; 73 -10.7; 78 -10.6; 83 -10.6; 89 -10.5; 95 -10.5; 102 -10.3; 109 -10.0; 117 -9.8; 125 -9.5; 134 -9.4; 143 -9.2; 153 -8.9; 164 -8.6; 175 -8.2; 188 -7.9; 201 -7.5; 215 -7.1; 230 -6.7; 246 -6.3; 263 -5.9; 282 -5.4; 301 -4.9; 323 -4.5; 345 -4.0; 369 -3.6; 395 -3.2; 423 -2.6; 452 -2.2; 484 -1.8; 518 -1.5; 554 -1.0; 593 -0.5; 635 -0.1; 679 -0.0; 726 0.2; 777 0.5; 832 0.5; 890 0.4; 952 0.2; 1019 -0.1; 1090 -0.3; 1167 -0.6; 1248 -0.8; 1336 -1.3; 1429 -1.6; 1529 -1.9; 1636 -2.2; 1751 -2.5; 1873 -2.7; 2004 -3.0; 2145 -3.8; 2295 -4.4; 2455 -4.2; 2627 -4.1; 2811 -3.4; 3008 -1.7; 3219 0.1; 3444 1.9; 3685 2.5; 3943 2.3; 4219 0.9; 4514 -0.4; 4830 -1.0; 5168 -1.7; 5530 -3.5; 5917 -5.8; 6331 -7.8; 6775 -6.2; 7249 -4.2; 7756 -2.5; 8299 -1.9; 8880 -2.2; 9502 -2.6; 10167 -1.9; 10879 -0.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.3; 18692 -0.5; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-2.716500217783854dB` and instead set Global volume in the UI for both channels to **-27**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Nocs NS 400 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-2.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -2.8dB.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 23 Hz   | 0.18 | -12.0 dB |
| Peaking | 167 Hz  | 0.71 | -4.2 dB  |
| Peaking | 2484 Hz | 1.73 | -5.2 dB  |
| Peaking | 3664 Hz | 2.63 | 5.1 dB   |
| Peaking | 6399 Hz | 2.81 | -7.5 dB  |
| Peaking | 339 Hz  | 2.22 | -0.7 dB  |
| Peaking | 782 Hz  | 1.52 | 1.6 dB   |
| Peaking | 1521 Hz | 2.83 | -0.9 dB  |
| Peaking | 9706 Hz | 4.26 | -3.3 dB  |
| Peaking | 9851 Hz | 1.69 | 1.4 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Nocs%20NS%20400/Nocs%20NS%20400.png)