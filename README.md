# Mac App Shell

Creates a Mac OSX .app folder (complete with icons) ready for your binary file. Perfect for Golang, C++, Rust, or any other language to compiles to a binary file on OSX.

## Usage

1. Download or clone the repo.

2. Pass the name of your Application and an image file for the icon.

    $ ./setup.sh MyNewApp app-icon.svg

3. Then just copy the binary file into the folder

		$ cp mybinary MyNewApp.app/Contents/MacOS/MyNewApp

## Icon formats:

The image file can be `.svg` (recomended), `.png`, `.gif`, `.jpg`, or `.tiff` format.

## Free SVG Icons

- http://fontawesome.io/
- http://ionicons.com/

## MIT License

Copyright (c) 2017 David Pennington

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Thanks to @HaoDong for his [original gist](https://gist.github.com/haodong/4aebdc102bdfbff5ec36).