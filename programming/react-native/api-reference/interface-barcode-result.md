---
layout: default-layout
title: Interface BarcodeResult of React-Native Dynamsoft Capture Vision
description: The interface of BarcodeResult result
keywords: Interface BarcodeResult, API reference
needAutoGenerateSidebar: true
needGenerateH3Content: true
noTitleIndex: true
breadcrumbText: BarcodeResult
---

# BarcodeResult

Interface `BarcodeResult`. The return value when a barcode is detected. It stores the barcode information including barcode text and barcode formats.

```js
export interface BarcodeResult {
    /**
     * The barcode text.
     */
    barcodeText: string;
    /**
     * Barcode type in string.
     */
    barcodeFormatString: string;
    /**
     * The location of the barcode.
     */
    barcodeLocation: BarcodeLocationResult;
}
```
