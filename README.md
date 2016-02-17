#Printr - ANSI Formatted Output for Swift CLI Applications

This library provides helpers to format output for CLI applications written in Swift for OSX and Linux.

###Basic Example

```swift
import Printr

let printer = Printr() //Default formatting. Alternatively init with custom formats

print.alert(.Error("Oh no, something broke"))
//prints a styled error

let formats = [Text.Bold, Color.Red]
print.text("some formatted text", formats: formats)
//prints the string in bold, red

```

###Instructions

Install this library with the Swift Package Manager

```swift

let package = Package(
    name: "MyCLIApp",
    dependencies: [
        .Package(url: "https://github.com/mpclarkson/printr.git", majorVersion: 0)
    ]
)

```

###Contributions

Pull requests are welcome!

You can learn how from this series [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)

###Todos

- [ ] Tests

###Author

Matthew Clarkson
[@matt_clarkson](https://twitter.com/matt_clarkson)
[Blog](https://mpclarkson.github.io)
[Work](https://hilenium.com)
