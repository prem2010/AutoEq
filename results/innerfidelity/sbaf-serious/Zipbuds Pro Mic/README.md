# Zipbuds Pro Mic

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -0.5dB
GraphicEQ: 10 -84; 20 -6.6; 22 -7.1; 23 -7.3; 25 -7.7; 26 -7.8; 28 -8.1; 30 -8.3; 32 -8.4; 35 -8.5; 37 -8.6; 40 -8.7; 42 -8.9; 45 -9.0; 49 -9.2; 52 -9.3; 56 -9.4; 59 -9.5; 64 -9.7; 68 -9.7; 73 -9.7; 78 -9.9; 83 -10.0; 89 -10.1; 95 -10.2; 102 -10.2; 109 -10.1; 117 -10.0; 125 -9.9; 134 -9.9; 143 -9.7; 153 -9.6; 164 -9.4; 175 -9.2; 188 -8.9; 201 -8.6; 215 -8.3; 230 -7.9; 246 -7.6; 263 -7.3; 282 -6.8; 301 -6.5; 323 -6.0; 345 -5.5; 369 -5.1; 395 -4.6; 423 -3.9; 452 -3.5; 484 -3.3; 518 -2.8; 554 -2.2; 593 -1.6; 635 -1.1; 679 -0.9; 726 -0.5; 777 -0.0; 832 0.1; 890 0.2; 952 0.2; 1019 0.0; 1090 0.2; 1167 0.4; 1248 0.1; 1336 -0.3; 1429 -0.9; 1529 -1.6; 1636 -2.2; 1751 -2.8; 1873 -3.1; 2004 -3.3; 2145 -3.4; 2295 -3.6; 2455 -3.5; 2627 -3.9; 2811 -3.6; 3008 -3.2; 3219 -2.6; 3444 -1.6; 3685 -1.6; 3943 -2.9; 4219 -5.7; 4514 -8.9; 4830 -12.3; 5168 -12.1; 5530 -8.3; 5917 -4.3; 6331 -2.4; 6775 -2.4; 7249 -4.4; 7756 -8.0; 8299 -10.3; 8880 -8.7; 9502 -4.5; 10167 -1.4; 10879 -1.4; 11640 -2.0; 12455 -1.5; 13327 -0.7; 14260 -0.4; 15258 -0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-0.5406460349632655dB` and instead set Global volume in the UI for both channels to **-5**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Zipbuds Pro Mic ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-0.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of --0.1dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 42 Hz    | 0.33 | -8.2 dB  |
| Peaking | 142 Hz   | 0.73 | -5.3 dB  |
| Peaking | 293 Hz   | 1.3  | -3.1 dB  |
| Peaking | 5579 Hz  | 0.75 | -7.5 dB  |
| Peaking | 24000 Hz | 2.55 | -6.4 dB  |
| Peaking | 2298 Hz  | 2.08 | -2.8 dB  |
| Peaking | 3727 Hz  | 4.55 | 3.4 dB   |
| Peaking | 5022 Hz  | 2.77 | -14.6 dB |
| Peaking | 6229 Hz  | 1.07 | 12.5 dB  |
| Peaking | 8319 Hz  | 3.22 | -12.1 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Zipbuds%20Pro%20Mic/Zipbuds%20Pro%20Mic.png)