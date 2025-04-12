[![pub version](https://img.shields.io/pub/v/coca_lints?logo=dart)](https://pub.dev/packages/coca_lints)

This package provides enhanced analyzer settings (linter) that include all recommended configurations from the Dart team plus additional stricter rules. Some informative messages are elevated to warnings or even errors to ensure strict adherence to coding standards.

**Note:** This package is intended for local use only. Any changes to it depend solely on its creator, and updates may be infrequent or nonexistent.

## Install

Add `coca_lints` as dev dependency to your `pubspec.yaml`.

```yaml
dev_dependencies:
    coca_lints: ^1.0.0
```

Or install via command line:

```bash
dart pub add dev:coca_lints
# or
flutter pub add dev:coca_lints
```

Create an `analysis_options.yaml` file at the root of the project with the following content:

```yaml
include: package:coca_lints/analysis_options.yaml
```

## Package versions table

| Flutter |  Dart  | Package |
|:-------:|:------:|:-------:|
| 3.29.x  | 3.7.x  | 1.0.0   |
