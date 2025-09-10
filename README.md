# Arabic-Text-to-Video-Converter

This project demonstrates how to convert Arabic text to video using the Diffusers library in Python. The resulting video is saved as an MP4 file.

## Features

- Converts any Arabic text to video.
- Outputs the video as an `.mp4` video file.
- Uses the `diffusers` library.

## Installation

To use this project, you need to have Python installed along with the `diffusers` package. You can install the package using the following command:

```bash
pip install diffusers
```

## How to Use

1. Clone or download this repository.
2. Edit the `arabic_prompt` variable in the code to contain the Arabic text you want to convert to video.
3. Run the script, and the output will be saved as an `.mp4` file.

### Example:

```python
arabic_prompt = "سبايدرمان يتزلج على الأمواج"
text_to_video_arabic(arabic_prompt)
```

In this example, the text `"سبايدرمان يتزلج على الأمواج"` will be converted to video and saved, example [output](output.mp4).

## License

This project is open-source and available under the MIT License.
