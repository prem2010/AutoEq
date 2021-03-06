# Denon AH-C551

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -0.9dB
GraphicEQ: 10 -84; 20 -5.5; 22 -5.9; 23 -6.1; 25 -6.4; 26 -6.5; 28 -6.8; 30 -6.9; 32 -7.1; 35 -7.4; 37 -7.5; 40 -7.7; 42 -7.8; 45 -8.0; 49 -8.2; 52 -8.3; 56 -8.4; 59 -8.5; 64 -8.7; 68 -8.9; 73 -9.1; 78 -9.2; 83 -9.4; 89 -9.6; 95 -9.7; 102 -9.7; 109 -9.6; 117 -9.6; 125 -9.6; 134 -9.6; 143 -9.5; 153 -9.3; 164 -9.1; 175 -8.8; 188 -8.6; 201 -8.3; 215 -8.0; 230 -7.6; 246 -7.1; 263 -6.8; 282 -6.3; 301 -5.8; 323 -5.3; 345 -4.8; 369 -4.3; 395 -3.8; 423 -3.1; 452 -2.6; 484 -2.2; 518 -1.7; 554 -1.1; 593 -0.4; 635 -0.1; 679 0.1; 726 0.4; 777 0.8; 832 0.7; 890 0.5; 952 0.3; 1019 -0.1; 1090 -0.4; 1167 -0.8; 1248 -1.3; 1336 -1.7; 1429 -2.3; 1529 -3.1; 1636 -3.8; 1751 -4.4; 1873 -4.8; 2004 -5.2; 2145 -5.8; 2295 -6.7; 2455 -7.7; 2627 -8.9; 2811 -9.9; 3008 -9.5; 3219 -7.1; 3444 -4.7; 3685 -3.8; 3943 -3.9; 4219 -5.4; 4514 -7.0; 4830 -8.3; 5168 -9.7; 5530 -11.2; 5917 -10.3; 6331 -7.6; 6775 -5.6; 7249 -4.3; 7756 -4.3; 8299 -5.7; 8880 -7.2; 9502 -6.7; 10167 -3.2; 10879 -0.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -2.2; 16326 -2.5; 17469 -0.1; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-0.8806536457704622dB` and instead set Global volume in the UI for both channels to **-8**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Denon AH-C551 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-1.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of --0.0dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 55 Hz    | 0.33 | -7.9 dB |
| Peaking | 181 Hz   | 0.78 | -5.1 dB |
| Peaking | 2602 Hz  | 1.98 | -8.1 dB |
| Peaking | 5763 Hz  | 1.5  | -9.3 dB |
| Peaking | 15999 Hz | 3.66 | -2.1 dB |
| Peaking | 775 Hz   | 2.78 | 2.2 dB  |
| Peaking | 5656 Hz  | 3.93 | -4.0 dB |
| Peaking | 6665 Hz  | 1.49 | 4.1 dB  |
| Peaking | 9200 Hz  | 2.88 | -8.4 dB |
| Peaking | 10870 Hz | 2.28 | 3.7 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Denon%20AH-C551/Denon%20AH-C551.png)