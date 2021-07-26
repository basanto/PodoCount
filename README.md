# PodoCount: A tool for whole-slide podocyte quantification

**Version 1.0.0**

**Prepared by Briana Santo at SUNY Buffalo on 27July2021**

This repository contains the source codes for the publication, "PodoCount: A robust, fully atuomated whole-slide podocyte quantification tool." All algorithms were developed and written by Briana Santo. The function xmltomask has been adapted from Lutnick et al.'s work "An integrated iterative annotation technique for easing neural network training in medical image analysis," Nature Machine Intelligence, 2019.

---
## A pre-print version of this work is available at: X

## Image Data

Whole slide images (WSIs) of murine kidney data are available at: http://bit.ly/3rdGPEd. Murine data includes whole kidney sections derived from both wild type and diseased mice across six mouse models [T2DM A, T2DM B, Aging, FSGS (SAND), HIVAN, Progeroid]. All kidney specimens were stained with p57kip2 immunohistochemistry and Periodic Acid-Schiff (without Hematoxylin counter stain) prior to digitization. 

## Requirements

This code runs using python3.

## Dependencies

- argparse [1.1]
- cv2 [4.1.2]
- lxml.etree [4.5.0]
- matplotlib [3.3.4]
- numpy [1.18.1]
- openslide-python [1.1.1]
- pandas [0.25.3]
- scikit-image [0.17.2]
- scipy [1.5.4]

## Modules from the Python Standard Library

- glob 
- os 
- sys
- time
- warnings

## Usage

The pipeline is run using: podocount_main_serv.py.

To run this code you must be in the downloaded pipeline folder, with WSIs and XMLs in the corresponding subfolders. You must also provide the necessary flags (below). 
