# youtube-parser
## Installation:
This program takes in a YouTube channel name as input and outputs an excel sheet with all their video information.
Install dependencies -- make sure xlwt is installed in the same directory as the virtual environment from pipenv.
You can create a separate python file with:
```shell
from ytparser import *

yt_data("YOUTUBE_API_KEY_HERE", "CHANNEL_NAME_HERE")

```

## Running:
A valid channel name is the text in the YouTube URL following youtube/c/{CHANNEL_NAME}
Some channels only have channel ID available, and this program is easily edited to take channel ID instead of channel name.
Channel ID is the text following youtube/channel/{CHANNEL_ID}.
One way to run it is to go to powershell while in the directory and run:

```shell
python -m pipenv shell # or any equivalent command to start the virtual environment
python -m main # main is just the separate python file name from above, make sure the correct python interpreter is selected
```

