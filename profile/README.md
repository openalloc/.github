# OpenAlloc Project

A family of libraries and applications, written in Swift

## Flow App Suite

The workspace in this Github repository has been broken up into separate projects. The two top-level projects are the ‘Flow’ apps:

- [FlowAllocator](https://github.com/openalloc/FlowAllocatorApp) - a portfolio rebalancing tool
- [FlowWorth](https://github.com/openalloc/FlowWorthApp) - a tool for tracking the value and performance of a portfolio over time

They are formerly proprietary applications now entirely open-sourced in August 2022. 

They are written in _Swift_ language and the _SwiftUI_ framework using Xcode 13.4

The current target is macOS 12.0 (Monterey) and newer, for Intel and Apple Silicon. This requirement will move forward in the future.

There’s strong potential for supporting iPadOS/iOS, but would require further development and testing by interested developers.

## Tracker App Suite

Apps for tracking daily calories, gym routines, and task routines, for the iPhone, iPad, and Apple Watch.

* [_Open Trackers_](https://open-trackers.github.io) - product website for all the tracker apps
* [_Open Trackers_ Project](https://github.com/open-trackers) - Github site for the development project, including full source code

## Libraries

A variety of reusable Swift libraries, written principally to support the apps above.

### Swift Components

* [SwiftCompactor](https://github.com/openalloc/SwiftCompactor) - formatters for the concise display of Numbers, Currency, and Time Intervals
* [SwiftModifiedDietz](https://github.com/openalloc/SwiftModifiedDietz) - a tool for calculating portfolio performance using the Modified Dietz method
* [SwiftNiceScale](https://github.com/openalloc/SwiftNiceScale) - generate 'nice' numbers for label ticks over a range, such as for y-axis on a chart
* [SwiftRegressor](https://github.com/openalloc/SwiftRegressor) - a linear regression tool that’s flexible and easy to use
* [SwiftSeriesResampler](https://github.com/openalloc/SwiftSeriesResampler) - transform a series of coordinate values into a new series with uniform intervals
* [SwiftSimpleTree](https://github.com/openalloc/SwiftSimpleTree) - a nested data structure that’s flexible and easy to use

### SwiftUI (User Interface Framework) Components

* [SwiftDetailer](https://github.com/openalloc/SwiftDetailer) - a multi-platform SwiftUI component for editing fielded data
* [SwiftNumberPad](https://github.com/openalloc/SwiftNumberPad) - a multi-platform SwiftUI component for basic number input
* [SwiftTabler](https://github.com/openalloc/SwiftTabler) - a multi-platform SwiftUI component for tabular data.
* [SwiftTextFieldPreset](https://github.com/openalloc/SwiftTextFieldPreset) - a multi-platform SwiftUI component for text input with presets support

### Financial data import

* [AllocData](https://github.com/openalloc/AllocData) - standardized data formats for investing-focused apps and tools
* [FINporter](https://github.com/openalloc/FINporter) - library and command-line tool to transform various specialized finance-related formats to the standardized schema of AllocData

## License

Copyright 2021, 2022 OpenAlloc LLC

All application code is licensed under the [Mozilla Public License 2](https://www.mozilla.org/en-US/MPL/2.0/), except where noted in individual modules.

## Contributing

Contributions are welcome. You are encouraged to submit pull requests to fix bugs, improve documentation, or offer new features. 

The pull request need not be a production-ready feature or fix. It can be a draft of proposed changes, or simply a test to show that expected behavior is buggy. Discussion on the pull request can proceed from there.

Contributions should ultimately have adequate test coverage. See tests for current entities to see what coverage is expected.
