# FlakeNAudioAdapter

An adapter that reads FLAC audio files using [CUETools.Flake](https://github.com/teekay/FLACTools) and makes it available to applications using the [NAudio](https://github.com/naudio/NAudio) library.

## Usage

Reference the library in your project and instantiate the `FlakeFileReader` class:

```cs
var reader = new FlakeFileReader('/path/to/flac/file');
```

Then, use it just like any other `WaveStream` implementation.
