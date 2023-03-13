# CatalystPreviewFailure

Demonstrates Mac Catalyst SwiftUI preview failure when used in Swift Packages.

When using a (local) Swift Package, SwiftUI preview doesn’t work at all for Mac Catalyst. 
It works for other platforms (tested iOS and macOS). 

Note that preview works for Catalyst if we’re not using it inside a Swift Package.

1. Open CatalystPreviewFailure.swift.
2. Set the run destination to Mac Catalyst.
3. Try to use the SwiftUI preview.

Reported to Apple (FB12055511).
