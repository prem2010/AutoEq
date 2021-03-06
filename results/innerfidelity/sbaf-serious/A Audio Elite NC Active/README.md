# A Audio Elite NC Active

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 6.0; 143 6.0; 153 6.0; 164 6.0; 175 6.0; 188 6.0; 201 6.0; 215 6.0; 230 6.0; 246 6.0; 263 6.0; 282 6.0; 301 6.0; 323 6.0; 345 6.0; 369 6.0; 395 6.0; 423 6.0; 452 6.0; 484 6.0; 518 6.0; 554 6.0; 593 6.0; 635 6.0; 679 6.0; 726 5.4; 777 4.1; 832 2.8; 890 1.8; 952 0.6; 1019 -0.0; 1090 -0.2; 1167 -0.4; 1248 0.5; 1336 1.3; 1429 2.1; 1529 2.8; 1636 3.5; 1751 4.2; 1873 5.1; 2004 5.9; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 5.9; 4219 4.3; 4514 3.6; 4830 4.5; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000003dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `A Audio Elite NC Active ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 60 Hz    | 0.14 | 6.3 dB  |
| Peaking | 508 Hz   | 1.35 | 3.8 dB  |
| Peaking | 2795 Hz  | 1.19 | 6.4 dB  |
| Peaking | 5721 Hz  | 3.06 | 5.2 dB  |
| Peaking | 24000 Hz | 2.36 | 4.3 dB  |
| Peaking | 705 Hz   | 5.04 | 2.3 dB  |
| Peaking | 1084 Hz  | 2.57 | -3.0 dB |
| Peaking | 1902 Hz  | 3.95 | 1.9 dB  |
| Peaking | 6572 Hz  | 6.88 | 2.1 dB  |
| Peaking | 7824 Hz  | 2.24 | -1.6 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/A%20Audio%20Elite%20NC%20Active/A%20Audio%20Elite%20NC%20Active.png)