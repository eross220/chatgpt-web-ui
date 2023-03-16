# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.5] – 2023-03-12

### Fixed

- Scrolling to the bottom of the page on new message ([#61](https://github.com/felixbade/chatgpt-web-ui/issues/61)).

## [1.1.4] – 2023-03-12

### Changed

- Improved PWA caching with Workbox – all files come from cache by default, but update in the background ([#63](https://github.com/felixbade/chatgpt-web-ui/issues/63)).

### Fixed

- ”Start by getting an API key” no longer flashes on page refresh ([#63](https://github.com/felixbade/chatgpt-web-ui/issues/63)).

## [1.1.3] – 2023-03-12

### Fixed

- iOS Safari: text is no longer incorrectly zooming when the phone is in landscape orientation ([#59](https://github.com/felixbade/chatgpt-web-ui/issues/59)).

## [1.1.2] – 2023-03-12

### Fixed

- Images no longer expand outside the message bubble ([#62](https://github.com/felixbade/chatgpt-web-ui/issues/62)).

## [1.1.1] – 2023-03-12

### Fixed

- Layout with devices that have a notch ([#58](https://github.com/felixbade/chatgpt-web-ui/issues/58)).

## [1.1.0] – 2023-03-12

### Added

- Streaming responses ([#45](https://github.com/felixbade/chatgpt-web-ui/issues/45)).

### Changed

- Scrolling is now instant after new data in assistant’s message. User’s messages still use smooth scrolling.

### Fixed

- Ordering of responses when multiple questions are sent before a response is received ([#47](https://github.com/felixbade/chatgpt-web-ui/issues/47)).

## [1.0.4] – 2023-03-09

### Added

- Link to API usage page ([#8](https://github.com/felixbade/chatgpt-web-ui/issues/8)).

## [1.0.3] – 2023-03-09

### Added

- Background for code blocks and inline code to increase contrast.
- Spacing between paragraphs.

### Fixed

- Code blocks with long lines on narrow screens causing horizontal scroll.

## [1.0.2] – 2023-03-07

### Fixed

- Multi-line code block rendering ([#55](https://github.com/felixbade/chatgpt-web-ui/issues/55)).

## [1.0.1] – 2023-03-07

### Fixed

- PWA error due to incorrect cacheable files list ([#56](https://github.com/felixbade/chatgpt-web-ui/issues/56)).

## [1.0.0] – 2023-03-07

- See commits for all the stuff that was added.