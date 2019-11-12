# Custom Call Progress Tones - 2019
The vendor supplied CPT files for the UK don't include any distinctive ringing, and are missing some useful error tones.

This is my attempt to fix that.

Latest available is `call_progress_uk-c3.dat`... `call_progress_uk-orig.ini` is the vendor supplied UK tones file, for reference.

## Compilation
These tone files are prepared using the vendor supplied `DConvert.exe` Windows program, with the following settings:
* V1 Tone file
* "Use dBM units for Tone Levels" box ticked

## Changelog:
2019-11-12:
  * Tone specification validated against https://www.itu.int/ITU-T/inr/forms/files/tones-0203.pdf
  * Added "Tone Type 7" (Reorder) as UK NU tone
  * Added distinctive ringing section from NZ tone file, as that has the right cadence

## TODO
  * Add entries for all valid Audiocodes tone types
  * Prepare equivalent files for older UK tone styles
  * Validate against https://www.btplc.com/SINet/SINs/pdf/350v1p6.pdf

```
.
├── README.md
├── call_progress_uk-c3.dat
├── call_progress_uk-c3.ini
├── call_progress_uk-orig.dat
└── call_progress_uk-orig.ini

0 directories, 5 files
```

