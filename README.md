# TemporalLabsLLC YouTube Transcriber



## Overview

TemporalLabsLLC YouTube Transcriber is an advanced tool designed to convert lists of YouTube videos into text data that can be further distilled for a generative AI pipeline. This functionality is crucial for creating insightful information and driving AI models with rich text data.

## Features

- Convert YouTube videos to text data.
- Seamlessly handle lists of videos.
- Ideal for generative AI pipelines.
- Modular design for easy integration with other AI tools.

## Installation

### Prerequisites

- Python 3.10.9
- pip

### Steps

1. Clone the repository:
    ```sh
    git clone https://github.com/TemporalLabsLLC-SOL/TemporalLabsLLC-YouTubeTranscriber.git
    cd TemporalLabsLLC-YouTubeTranscriber
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```
Dependencies should install according to your setup but I'm still testing how compatible it is across builds. I kept these for now.

3. Install dependencies:
    ```sh
    pip install -r requirements-cpu.txt   # or requirements-cuda.txt for CUDA support
    ```

## Usage

1. Run the main script:
    ```sh
    python SOLTRANS.py
    ```

2. Follow the on-screen instructions to convert YouTube videos to text data.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Donations

If you find this project useful, please consider donating to support further development.

## Contact

For any inquiries, please contact us at [sol@temporallab.com](mailto:sol@temporallab.com).
