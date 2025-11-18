[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=21722225&assignment_repo_type=AssignmentRepo)
# 02.2 - Figure, Mark, Video, Audio tags

## Exercise 1

### Figure & Figcaption

Have you ever had to think really hard of a good caption to put on your Instagram picture? Well, images in HTML can also have captions thanks to the `<figure>` and `<figcaption>` tags!

The following pictures and titles are current songs that are hot on the Billboard 100 week (for the week of November 16, 2025). Using the figure and figcaption tags, we're going to match each album cover with the name of the song and singer as an official caption.

1. Go to the [Billboard website](https://www.billboard.com/charts/hot-100/): [Link](https://www.billboard.com/charts/hot-100/), and copy the image links for each of the songs listed in the `index.html` under the `li` tag in order. Paste them in the  `<img>` src attributes.
2. Add an opening `<figure>` tag before the `<img>` tag, but after the `<li>` tag.
3. Under the img tag, add the `<figcaption>` tag with the closing tag `</figcaption>`.
4. Copy the correct song title from the list below and paste it between our new figcaption tags.

Congrats! You've paired an official caption with an image. Repeat for the other 9 songs.

### Mark

1. We can use the `<mark>` tag to highlight words in HTML. Use the `<mark>` tag to highlight a song that you have heard on this list.

## Exercise 2

### Video

1. Use the [TuberRipper](https://tuberipper.com/14/): [Link](https://tuberipper.com/14/) website to download two music videos songs from YouTube. (Press "Extract Audio" or "Extract Video" button to extract and download Audio or Video file. You can choose MP3 audio file format and desired quality by using "" button dropdown menu.
If for some reason, audio or video track starts to play in your browser instead of downloading, just right-click on it and choose "Save As" from popup menu to store it on your device.)

1. Upload the two music videos to the videos folder of Visual Studio Code.
1. For each respective song, place the videos on top the `<figure>` tag you just created by using the `<video>` tag.

### Audio

1. Use the [TuberRipper](https://tuberipper.com/14/): [Link](https://tuberipper.com/14/save/mp3) website to download the rest of songs from YouTube. (Press "Extract Audio" or "Extract Video" button to extract and download Audio or Video file. You can choose MP3 audio file format and desired quality by using "" button dropdown menu.
If for some reason, audio or video track starts to play in your browser instead of downloading, just right-click on it and choose "Save As" from popup menu to store it on your device.)
1. Move the songs to the songs folder in the Visual Studio Code project files.
1. For each respective song, place the audio on top the `<figure>` tag you just created by using the `<audio>` tag.

Remember to use the correct attributes for each!

## Extension Exercise (mandatory if finished early)

**Answer below**: How could we optimize this assignment if we were to use Javascript? You don't need to write any Javascript, but explain how you would use concepts like array of objects and loops to optimize this code.
