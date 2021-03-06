# Philips ONeil Crash

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -4.9dB
GraphicEQ: 10 -84; 20 -8.0; 22 -8.4; 23 -8.5; 25 -8.8; 26 -8.9; 28 -9.1; 30 -9.3; 32 -9.5; 35 -9.7; 37 -9.8; 40 -9.9; 42 -10.0; 45 -10.1; 49 -10.2; 52 -10.3; 56 -10.3; 59 -10.4; 64 -10.6; 68 -10.7; 73 -10.9; 78 -11.1; 83 -11.3; 89 -11.5; 95 -11.6; 102 -11.7; 109 -11.6; 117 -11.6; 125 -12.0; 134 -12.4; 143 -12.5; 153 -12.2; 164 -11.5; 175 -11.3; 188 -11.4; 201 -11.0; 215 -10.6; 230 -10.0; 246 -9.4; 263 -8.8; 282 -8.0; 301 -7.5; 323 -7.0; 345 -6.4; 369 -6.1; 395 -6.0; 423 -5.5; 452 -5.2; 484 -5.0; 518 -4.7; 554 -4.2; 593 -3.5; 635 -2.9; 679 -2.3; 726 -1.7; 777 -1.2; 832 -0.9; 890 -0.5; 952 -0.1; 1019 0.1; 1090 0.0; 1167 -0.1; 1248 -0.1; 1336 -0.7; 1429 -1.6; 1529 -2.0; 1636 -2.0; 1751 -3.1; 1873 -3.6; 2004 -4.3; 2145 -5.4; 2295 -6.5; 2455 -7.2; 2627 -7.3; 2811 -7.3; 3008 -6.2; 3219 -5.1; 3444 -3.2; 3685 -0.6; 3943 0.8; 4219 -0.8; 4514 -1.0; 4830 2.5; 5168 4.6; 5530 4.6; 5917 3.0; 6331 0.5; 6775 -1.4; 7249 -3.5; 7756 -4.9; 8299 -5.9; 8880 -6.1; 9502 -4.7; 10167 -1.3; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 -0.9; 20000 -2.4
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-4.9219598054277025dB` and instead set Global volume in the UI for both channels to **-49**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Philips ONeil Crash ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.3dB** and build filters manually
with these parameters. The first 4 filters can be used independently.
When using independent subset of filters, apply preamp of -0.1dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 36 Hz   | 0.24 | -8.4 dB |
| Peaking | 180 Hz  | 0.53 | -7.9 dB |
| Peaking | 2553 Hz | 2.6  | -8.1 dB |
| Peaking | 8599 Hz | 4.47 | -7.0 dB |
| Peaking | 1035 Hz | 2.72 | 1.7 dB  |
| Peaking | 1837 Hz | 3.98 | -1.3 dB |
| Peaking | 3147 Hz | 8.03 | -2.2 dB |
| Peaking | 5433 Hz | 3.93 | 6.1 dB  |
| Peaking | 7332 Hz | 5.48 | -2.7 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Philips%20ONeil%20Crash/Philips%20ONeil%20Crash.png)