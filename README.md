# YouTube Video Manager

## Overview

This Python script serves as a basic YouTube video manager, allowing users to perform various operations on a list of videos. The video information is stored in a JSON file named "youtube.txt."

## Functionalities

1. **List All Videos:**
   - Displays a numbered list of all videos with their names and durations.

2. **Add a Video:**
   - Takes user input for a new video's name and duration, appending it to the existing list.

3. **Update Video Details:**
   - Lists all videos, enabling users to choose a video by number.
   - Allows users to update the video's name and duration.

4. **Delete a Video:**
   - Lists all videos, prompting users to choose a video by number.
   - Deletes the selected video from the list.

5. **Exit the App:**
   - Allows users to gracefully exit the application.

## Implementation

- Utilizes a JSON file for persistent storage of video data.
- Exception handling manages cases where the data file is not found.
- The main function (`main()`) runs a continuous loop, prompting users for choices until they decide to exit.

## Usage

1. Clone the repository.
2. Run the script.
3. Follow the on-screen prompts to manage your list of YouTube videos.

## Dependencies

- Python 3.x

## How to Run

```bash
python youtube_manager.py

2. Video2, Duration: 05:45
3. Video3, Duration: 15:20
4. New Video, Duration: 08:15
**********************************************************************

...
This script provides a simple and intuitive command-line interface for managing a collection of YouTube videos.
