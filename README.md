# README

This is a repackaging fork of the Chromium Embedded Framework (CEF) binary distribution files, found at https://cef-builds.spotifycdn.com/index.html, into NuGet packages.

## Supported Platforms

### macOS
- `cef.redist.osx64` - macOS x64 (Intel)
- `cef.redist.osxarm64` - macOS ARM64 (Apple Silicon)

### Linux
- `cef.redist.linux64` - Linux x64
- `cef.redist.linuxarm64` - Linux ARM64

## Building

### macOS

```bash
# For Intel (x64)
./make_cefredist.sh osx64

# For Apple Silicon (ARM64)
./make_cefredist.sh osxarm64
```

### Linux

```bash
# For x64
./make_cefredist_linux.sh linux64

# For ARM64
./make_cefredist_linux.sh linuxarm64
```

The build scripts will download the CEF binaries from Spotify CDN and package them into NuGet-compatible directories.
