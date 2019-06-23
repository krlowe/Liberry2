# Unca Ken's Lending Liberry

The Unca Ken's Lending Liberry app performs certain database functions on Unca Ken's Lending Liberry.

## Overview

This app allows one to perform an inventory of the Liberry by scanning a QR code identifying
a location within the Liberry, for example "Shelf 3 in Bookshelf 17" followed by the QR codes
of the items at that location.

Items can be checked out from the Liberry by scanning the QR code identifying oneself,
followed by the QR codes of the items to be checked out.  Similarly they can be checked back
in by scanning the QR code of the shelf they're returned to followed by the their own QR codes.

## Implementation

This app is a blatant ripoff of AVCamBarcode, the "Using AVFoundation to Detect Barcodes
and Faces" sample app from Apple.

AVCamBarcode demonstrates how to use the AVFoundation capture API to detect barcodes and faces.

## Requirements

### Build

Xcode 9.0, iOS 11.0 SDK

### Runtime

iOS 11.0 or later

Copyright (C) 2018 Ken Lowe.  All rights reserved.
Copyright (C) 2017 Apple Inc. All rights reserved.
