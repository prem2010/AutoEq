# Wicked Audio Deuce

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -0.6dB
GraphicEQ: 10 -84; 20 -14.0; 22 -13.9; 23 -13.8; 25 -13.7; 26 -13.7; 28 -13.6; 30 -13.5; 32 -13.3; 35 -13.2; 37 -13.1; 40 -12.9; 42 -12.8; 45 -12.7; 49 -12.6; 52 -12.4; 56 -12.3; 59 -12.2; 64 -12.1; 68 -12.0; 73 -11.9; 78 -11.8; 83 -11.7; 89 -11.7; 95 -11.6; 102 -11.4; 109 -11.1; 117 -10.9; 125 -10.7; 134 -10.4; 143 -10.2; 153 -9.9; 164 -9.6; 175 -9.1; 188 -8.8; 201 -8.4; 215 -8.0; 230 -7.5; 246 -7.1; 263 -6.7; 282 -6.2; 301 -5.7; 323 -5.3; 345 -4.8; 369 -4.3; 395 -3.9; 423 -3.2; 452 -2.8; 484 -2.5; 518 -2.0; 554 -1.5; 593 -0.9; 635 -0.6; 679 -0.5; 726 -0.2; 777 -0.1; 832 0.3; 890 0.4; 952 0.2; 1019 -0.0; 1090 -0.2; 1167 -0.4; 1248 -0.8; 1336 -1.0; 1429 -1.5; 1529 -2.2; 1636 -2.9; 1751 -3.8; 1873 -4.5; 2004 -5.0; 2145 -5.4; 2295 -5.7; 2455 -5.5; 2627 -5.3; 2811 -4.6; 3008 -2.9; 3219 -1.6; 3444 -0.1; 3685 0.4; 3943 -0.3; 4219 -1.8; 4514 -3.5; 4830 -4.9; 5168 -6.5; 5530 -10.2; 5917 -12.7; 6331 -8.6; 6775 -4.9; 7249 -3.1; 7756 -3.0; 8299 -4.6; 8880 -6.2; 9502 -6.1; 10167 -3.2; 10879 -0.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-0.5798669540411645dB` and instead set Global volume in the UI for both channels to **-5**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Wicked Audio Deuce ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-0.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of --0.0dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 22 Hz    | 0.18 | -13.5 dB |
| Peaking | 170 Hz   | 0.66 | -4.6 dB  |
| Peaking | 2226 Hz  | 2.38 | -5.9 dB  |
| Peaking | 5898 Hz  | 3.15 | -12.0 dB |
| Peaking | 22469 Hz | 2.24 | -3.8 dB  |
| Peaking | 856 Hz   | 2.15 | 1.4 dB   |
| Peaking | 1712 Hz  | 4.05 | -1.3 dB  |
| Peaking | 7157 Hz  | 5.86 | 1.4 dB   |
| Peaking | 8177 Hz  | 0.37 | 0.8 dB   |
| Peaking | 9142 Hz  | 4.02 | -6.6 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Wicked%20Audio%20Deuce/Wicked%20Audio%20Deuce.png)