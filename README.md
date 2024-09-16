This project helps visualize the waypoints of the **September'24 DeepRacer Student League track**. Understanding the track and its waypoints can assist you in drafting an effective reward function for your AWS DeepRacer model.

## Overview

The provided code allows you to:
- Clone the AWS DeepRacer community's race data repository.
- Visualize the waypoints, left, and right boundaries of a given track.
- Label waypoints at regular intervals to understand their distribution and use them to improve your model's reward function.

The code is implemented in `Track_Waypoints_display.ipynb`, a Jupyter Notebook, and it specifically visualizes the waypoints of the "Austin" track from the community data repository.

## Prerequisites

Before running the notebook, ensure you have the following installed:
- **Python 3.x**
- **NumPy** (`pip install numpy`)
- **Matplotlib** (`pip install matplotlib`)
- **Git** (to clone the repository)

## Installation

1. Clone this repository or download the `.ipynb` file.
2. Install the required Python libraries by running:
    ```bash
    pip install numpy matplotlib
    ```

3. Clone the AWS DeepRacer Community Data repository (the code will automatically clone it if it doesn't exist):
    ```bash
    !git clone https://github.com/aws-deepracer-community/deepracer-race-data.git
    ```

## Usage

To run the notebook, open it in a Jupyter environment and execute the code cells. The main function, `track_show()`, visualizes the track waypoints, allowing you to analyze the track layout.

## Sample Output

Below is a sample visualization of the Austin track's waypoints:

![Austin Track Waypoints](images/austin_track.png)
