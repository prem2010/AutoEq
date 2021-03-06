# Yamaha YH3 Sn180629

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 3.3; 22 3.0; 23 2.8; 25 2.5; 26 2.4; 28 2.2; 30 2.0; 32 1.9; 35 1.7; 37 1.6; 40 1.4; 42 1.3; 45 1.2; 49 1.1; 52 1.0; 56 0.8; 59 0.7; 64 0.4; 68 0.3; 73 0.1; 78 -0.1; 83 -0.2; 89 -0.4; 95 -0.7; 102 -1.1; 109 -1.2; 117 -1.3; 125 -1.5; 134 -1.8; 143 -2.0; 153 -2.2; 164 -2.2; 175 -2.3; 188 -2.5; 201 -2.6; 215 -2.6; 230 -2.6; 246 -2.7; 263 -2.7; 282 -2.5; 301 -2.4; 323 -2.3; 345 -2.1; 369 -2.2; 395 -2.3; 423 -2.3; 452 -2.2; 484 -2.3; 518 -2.3; 554 -2.1; 593 -2.0; 635 -2.0; 679 -2.2; 726 -1.9; 777 -1.3; 832 -1.0; 890 -0.9; 952 -0.5; 1019 0.2; 1090 1.1; 1167 2.2; 1248 3.2; 1336 4.0; 1429 4.4; 1529 4.3; 1636 4.2; 1751 3.9; 1873 3.3; 2004 1.9; 2145 1.2; 2295 0.6; 2455 0.7; 2627 1.5; 2811 2.8; 3008 5.3; 3219 6.0; 3444 5.7; 3685 3.5; 3943 3.4; 4219 3.2; 4514 4.0; 4830 5.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.1; 9502 -0.5; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.8; 16326 -1.4; 17469 -0.2; 18692 0.0; 20000 -0.5
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.09999999703621dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Yamaha YH3 Sn180629 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.7dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 14 Hz    | 0.2  | 3.0 dB  |
| Peaking | 887 Hz   | 0.08 | -3.0 dB |
| Peaking | 1484 Hz  | 1.51 | 7.3 dB  |
| Peaking | 3220 Hz  | 3.62 | 6.7 dB  |
| Peaking | 5546 Hz  | 1.8  | 8.4 dB  |
| Peaking | 2411 Hz  | 5.02 | -0.9 dB |
| Peaking | 6577 Hz  | 6.06 | 2.7 dB  |
| Peaking | 7034 Hz  | 1.39 | -2.8 dB |
| Peaking | 8406 Hz  | 0.43 | 1.3 dB  |
| Peaking | 16005 Hz | 4.3  | -1.8 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Yamaha%20YH3%20Sn180629/Yamaha%20YH3%20Sn180629.png)