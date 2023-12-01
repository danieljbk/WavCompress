# WAV Compressor

## Overview

The WAV Compressor is a JavaScript tool designed to reduce the size of WAV audio files by adjusting their sample rate. This tool is intended to help users compress audio files to a target size in megabytes (MB), making it easier to manage and share large audio files.

## Features

- **Sample Rate Adjustment**: Dynamically modifies the sample rate to achieve the desired file size reduction.
- **Web-Based**: Runs directly in the browser, no server-side processing required.
- **User Interface**: Provides a simple and intuitive interface for selecting files and setting the target file size.
- **Client-Side Processing**: Ensures privacy as files are processed locally without the need to upload them to a server.

## Prerequisites

Before using the WAV Compressor, ensure that your browser is up to date and supports the necessary Web APIs, such as `AudioContext` and `OfflineAudioContext`.

## Installation

No installation is required. The WAV Compressor can be accessed and used directly in the browser.

## Usage

To compress a WAV file:

1. Open the WAV Compressor in your web browser.
2. Use the file input to select the WAV file you wish to compress.
3. Enter the target size in megabytes (MB) for the compressed file.
4. Click the "Compress" button to start the compression process.
5. Once compression is complete, the file will be automatically downloaded to your device.

## How It Works

The tool works by:

1. Decoding the selected WAV file into an audio buffer.
2. Calculating the new frame rate needed to reach the target file size.
3. Changing the sample rate of the audio buffer to the new frame rate.
4. Encoding the modified audio buffer back into a WAV file.
5. Triggering a download of the compressed WAV file.

## Interface

The user interface consists of:

- A file input for selecting WAV files.
- A number input for specifying the target file size in MB.
- A "Compress" button to initiate the compression process.

## Styling

The accompanying `styles.css` file provides a clean and responsive design for the tool's interface, ensuring a good user experience across various devices and screen sizes.

## Limitations

- The tool currently only supports WAV file format.
- Compression is solely based on sample rate adjustment, which may affect the audio quality.

## License

This tool is open-source and can be freely used and modified.

## Contributions

Contributions to the project are welcome. Feel free to fork the repository, make improvements, and submit pull requests.
