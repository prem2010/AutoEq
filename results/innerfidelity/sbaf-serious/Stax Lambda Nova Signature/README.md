# Stax Lambda Nova Signature

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 5.0; 23 4.6; 25 3.9; 26 3.6; 28 3.1; 30 2.7; 32 2.5; 35 2.5; 37 2.5; 40 2.6; 42 2.7; 45 2.8; 49 3.0; 52 3.2; 56 3.3; 59 3.4; 64 3.4; 68 3.4; 73 3.4; 78 3.3; 83 3.2; 89 2.9; 95 2.6; 102 2.4; 109 2.5; 117 2.5; 125 2.3; 134 2.3; 143 2.2; 153 2.2; 164 2.1; 175 2.0; 188 2.0; 201 2.0; 215 2.0; 230 2.0; 246 1.9; 263 1.9; 282 1.9; 301 1.9; 323 1.8; 345 1.9; 369 1.9; 395 1.8; 423 2.0; 452 2.1; 484 1.9; 518 1.8; 554 1.9; 593 2.0; 635 1.8; 679 1.5; 726 1.5; 777 1.4; 832 1.0; 890 0.6; 952 0.3; 1019 -0.0; 1090 -0.2; 1167 -0.8; 1248 -1.5; 1336 -2.4; 1429 -3.2; 1529 -3.1; 1636 -3.5; 1751 -3.7; 1873 -2.4; 2004 -0.4; 2145 1.7; 2295 3.8; 2455 3.6; 2627 2.5; 2811 0.8; 3008 0.5; 3219 0.3; 3444 0.9; 3685 1.3; 3943 2.1; 4219 2.0; 4514 1.9; 4830 2.1; 5168 4.1; 5530 4.2; 5917 0.9; 6331 1.4; 6775 3.5; 7249 1.3; 7756 0.3; 8299 -1.5; 8880 -3.5; 9502 -3.1; 10167 -0.9; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.077037988955674dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Stax Lambda Nova Signature ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -5.9dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 13 Hz    | 1.14 | 6.6 dB  |
| Peaking | 90 Hz    | 0.07 | 2.4 dB  |
| Peaking | 1667 Hz  | 1.58 | -5.6 dB |
| Peaking | 2323 Hz  | 3.59 | 5.9 dB  |
| Peaking | 5224 Hz  | 3.23 | 4.0 dB  |
| Peaking | 33 Hz    | 2.05 | -1.0 dB |
| Peaking | 66 Hz    | 2.46 | 1.0 dB  |
| Peaking | 6809 Hz  | 9.69 | 2.9 dB  |
| Peaking | 9097 Hz  | 4.53 | -4.3 dB |
| Peaking | 10599 Hz | 4.09 | 0.8 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Stax%20Lambda%20Nova%20Signature/Stax%20Lambda%20Nova%20Signature.png)