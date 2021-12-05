# ImmunePDF

## About

This is a simple script that creates a PDF file from a screenshot of the CovPass app similar to the service offered at https://immunkarte.de/. But you can print it yourself, recylce transparent lanyard ticket holders for it and thus it is way cheaper!

**Warning:** The project is at a "proof-of-concept" developement state. Contributions are welcome!

## Installation

```
pip install base45 qrcode cbor2 pyzbar opencv-python
```

## Usage

- Take a screenshot of your CovPass app on your smartphone.
- Transfer it to your computer.
- Generate the PDF from the screenshot:

```
python main.py your_screenshot.png
```
- Print the PDF on A4 paper.
- Fold the paper twice.
- Put it into a transparent lanyard ticket holder.

## Todo

- Make other card sizes possible by using options for the script.

## License

Copyright 2021, Mebus

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
