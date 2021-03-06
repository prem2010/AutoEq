# Philips Fidelio S2 Early 2013

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -4.0dB
GraphicEQ: 10 -84; 20 -0.2; 22 -0.3; 23 -0.4; 25 -0.5; 26 -0.5; 28 -0.6; 30 -0.6; 32 -0.7; 35 -0.8; 37 -0.8; 40 -0.9; 42 -1.0; 45 -1.0; 49 -1.1; 52 -1.1; 56 -1.3; 59 -1.4; 64 -1.5; 68 -1.7; 73 -1.8; 78 -2.0; 83 -2.1; 89 -2.3; 95 -2.4; 102 -2.5; 109 -2.5; 117 -2.5; 125 -2.6; 134 -2.6; 143 -2.6; 153 -2.5; 164 -2.5; 175 -2.3; 188 -2.2; 201 -2.1; 215 -1.9; 230 -1.7; 246 -1.5; 263 -1.4; 282 -1.1; 301 -0.9; 323 -0.7; 345 -0.5; 369 -0.3; 395 -0.1; 423 0.2; 452 0.3; 484 0.4; 518 0.5; 554 0.8; 593 1.1; 635 1.1; 679 1.1; 726 1.1; 777 1.2; 832 1.0; 890 0.7; 952 0.4; 1019 -0.1; 1090 -0.4; 1167 -0.8; 1248 -1.1; 1336 -1.7; 1429 -2.3; 1529 -2.8; 1636 -3.3; 1751 -3.5; 1873 -3.5; 2004 -3.4; 2145 -3.2; 2295 -2.7; 2455 -1.9; 2627 -1.0; 2811 -0.1; 3008 1.1; 3219 2.0; 3444 2.7; 3685 2.2; 3943 1.0; 4219 -1.2; 4514 -3.2; 4830 -3.9; 5168 -2.7; 5530 -0.7; 5917 1.5; 6331 3.1; 6775 3.6; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-4.001542058492684dB` and instead set Global volume in the UI for both channels to **-40**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Philips Fidelio S2 Early 2013 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -4.1dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 119 Hz  | 0.75 | -2.8 dB |
| Peaking | 1908 Hz | 1.98 | -4.1 dB |
| Peaking | 3528 Hz | 2.93 | 4.1 dB  |
| Peaking | 4753 Hz | 3.5  | -5.1 dB |
| Peaking | 6491 Hz | 4.93 | 4.6 dB  |
| Peaking | 35 Hz   | 1.55 | -0.4 dB |
| Peaking | 239 Hz  | 1.94 | -0.6 dB |
| Peaking | 714 Hz  | 1.17 | 1.7 dB  |
| Peaking | 1141 Hz | 2.72 | -0.5 dB |
| Peaking | 1464 Hz | 4.51 | -0.9 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Philips%20Fidelio%20S2%20Early%202013/Philips%20Fidelio%20S2%20Early%202013.png)