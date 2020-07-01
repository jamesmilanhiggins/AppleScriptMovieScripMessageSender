
# iMessage Script
> This script takes 2 arguments. A phone number, and a text file. The script will reads each line of the file, and sends it as an individual iMessage to the phone number.


## Installation

OS X only.

```sh
git clone https://github.com/jamesmilanhiggins/AppleScriptMovieScripMessageSender.git
```
After cloning the project, navigate inside the directory

```sh
cd AppleScriptMovieScripMessageSender
```

And then, within the directory run:
```sh
osascript MessageSender.scpt [insert phone number here. Starting with +1...] [movie script you want to send]
```


Example:
```sh
osascript MessageSender.scpt [+18008675309] nattytreasure.txt
```
