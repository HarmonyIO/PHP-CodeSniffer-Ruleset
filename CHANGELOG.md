# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

*None*

### Changed

*None*

### Deprecated

*None*

### Removed

*None*

### Fixed

*None*

### Security

*None*

## [1.0.0-rc1]

### Added

- [[0ea3367](https://github.com/HarmonyIO/PHP-CodeSniffer-Ruleset/commit/0ea33679e9ccf78b2aec889ebef89ba876464c4f)] Added .gitattributes file
- [[738e340](https://github.com/HarmonyIO/PHP-CodeSniffer-Ruleset/commit/738e34025d3c18460aa96a89e18273653cb70aa4)] Added changelog 

### Changed

- [[d420eac](https://github.com/HarmonyIO/PHP-CodeSniffer-Ruleset/commit/d420eac5ef5c42f0efc0b0302fd9981ecb435660)] Allow single line property docblock
- [[b4dffa0](https://github.com/HarmonyIO/PHP-CodeSniffer-Ruleset/commit/b4dffa09b891c07a89322e61c7b999e7998822f8)] Excluded requirement of fully qualified exceptions 
- [[52eb47c](https://github.com/HarmonyIO/PHP-CodeSniffer-Ruleset/commit/52eb47cead6676e3b91cae625644871613a9e514)] Prevent errors on unused imports in annotations
- [[1023bbe](https://github.com/HarmonyIO/PHP-CodeSniffer-Ruleset/commit/1023bbeba0c631e59f20a31a4ad4d191d7ed8825)] Disable control structure spacing for yields
- [[bd74644](https://github.com/HarmonyIO/PHP-CodeSniffer-Ruleset/commit/bd746444e6d715899d464ab6d4763a4abda78137)] Disable DisallowedPostDecrementOperator rule
- [[85bfb91](https://github.com/HarmonyIO/PHP-CodeSniffer-Ruleset/commit/85bfb91fb829f084ff00c8e19f529c3a6f8e5308)] Allow @dataProvider annotation 
- [[9e93294](https://github.com/HarmonyIO/PHP-CodeSniffer-Ruleset/commit/9e9329473f6cf000cb21bbca76b5498537a0753e)] Disable DisallowedPostIncrementOperator rule
- [[d41e21b](https://github.com/HarmonyIO/PHP-CodeSniffer-Ruleset/commit/d41e21b1c3166d96688b9f905200113b8cd72337)] Update php_codesniffer to 3.4.0

### Deprecated

*None*

### Removed

*None*

### Fixed

- [[d3678da](https://github.com/HarmonyIO/PHP-CodeSniffer-Ruleset/commit/d3678daabd50b81e88cacda3053f1e22f61a0f1b)] Disable Classes.SuperfluousExceptionNaming.SuperfluousSuffix sniff until upstream release the bug fix where classes called `Exception` result in a false positive (https://github.com/slevomat/coding-standard/issues/552)

### Security

*None*
