# Mondrian Art Generator

This Python program generates random artwork in the style of Piet Mondrian using the Tkinter library for graphical output.

## Description

This program creates random artwork inspired by the compositions of the famous Dutch artist Piet Mondrian. The generated artwork consists of rectangles filled with random colors, arranged in a grid-like fashion, reminiscent of Mondrian's abstract paintings.

The program uses a recursive algorithm to split the canvas into smaller rectangles, applying random colors to each rectangle. The size and placement of the rectangles are determined by random splits along both horizontal and vertical axes, resulting in a varied and visually interesting composition.

## Features

- Generates random artwork in the style of Piet Mondrian.
- Uses Tkinter for graphical output.
- Customizable parameters such as canvas size and split thresholds.
- Randomly assigns colors to rectangles for dynamic compositions.

## Usage

To run the program:

1. Make sure you have Python installed on your system.
2. Clone the repository or download the `mondrian_art.py` file.
3. Run the script using Python: `python mondrian_art.py`.

The generated artwork will be displayed in a graphical window using Tkinter.

## Parameters

You can customize the following parameters in the `mondrian_art.py` script:

- `WIDTH`: Width of the canvas in pixels.
- `HEIGHT`: Height of the canvas in pixels.
- `SPLIT_LOW`: Minimum size threshold for splitting rectangles.
- `SPLIT_PENALTY`: Factor determining the frequency of splits.

Adjusting these parameters can result in different styles and compositions of the generated artwork.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by the abstract compositions of Piet Mondrian.
- Built using Python and Tkinter.

