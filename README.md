# eHatid
It is a simple application that allows user to: 1) see the list of his deliveries; 2) see the details of each of the deliveries; and, 3) favorite or unfavorite deliveries.

## Demo
<img src="https://github.com/iamjcabarra/eHatid/blob/master/demo.gif" width="300" height="600" />

## Features
1. Pagination - load more deliveries when scrolling to the bottom of the list
2. Remember favorite - data are stored locally
3. Customizable theme - can be built based on desired theme

## Version
eHatid was developed using Swift 4.2, iOS 11, and Xcode 11.2.1.

## Network
I utilized Moya and PromiseKit as third-party libraries to accomplish networking-related tasks.

## Database
For local database, I made use of CoreData, an object graph and persistence framework provided by Apple in the macOS and iOS operating systems.

## UI
I implemented UIs programmatically with the help of third-party library called SnapKit.

## Testing
I utilized Quick and Nimble in order for me to write tests that read exactly like regular sentences, allowing me to easily and swiftly describe the behavior I wish to verify.

## Style
I used SwiftLint as a tool to enforce Swift style and conventions which is loosely based on GitHub's Swift Style Guide.

## License

The MIT License (MIT)

Copyright (c) 2020 Julius Abarra

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
