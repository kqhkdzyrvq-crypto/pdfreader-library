# pdfreader-library

This repository serves development library data through GitHub Pages. It is not a released literature catalogue.

## Current vector source
- [Ruoyo PDFReader Library](sources/ruoyo-vector-demo/): one source containing the complete 6-page original Demo and the 1,210-page Lord of the Rings test document. Uses the current 2-draft vector reader with capacity-packed multi-page PNG data. The source URL remains unchanged.

## Earlier SDF prototype sources (legacy)
- [Ruoyo Library](sources/ruoyo-test-library/): two short original Japanese test texts.
- [Evening Collection](sources/evening-collection/): a second independent source used to test library selection.

Each legacy source below is a self-contained PDFReader source/1-draft directory. Its source.json points to content-addressed book data, a shared SDF font atlas, the font mapping and its OFL licence. The atlas is derived from Noto and its licence is included alongside it.

To configure a world, copy the source.json link from the chosen collection into PDFReader's Online libraries window in Unity. This is a development preview.

## Earlier connection test
probe/20260914-v1/ remains unchanged. It contains the original connectivity and pixel-preservation fixtures.

Product code, converter code, Unity assets, original font binaries and private workspace files are not included.
