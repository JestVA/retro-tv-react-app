# retro-tv-react-app
blackbox project

I was studying sequential logic in digital circuitry on Wikipedia and found this little snippet below. 
Instantly knew what I was going to do next. My own React app called "Retro TV".

I wrote a detailed Linkedin article about the process and a link can be found here: https://www.linkedin.com/pulse/so-you-want-github-famous-how-do-dorin-stefan-dumitrascuta/

//MVP INSTRUCTIONS
A familiar example of a device with sequential logic is a television set with "channel up" and "channel down" buttons.
[1] Pressing the "up" button gives the television an input telling it to switch to the next channel above the one it is currently receiving. If the television is on channel 5, pressing "up" switches it to receive channel 6. However, if the television is on channel 8, pressing "up" switches it to channel "9". In order for the channel selection to operate correctly, the television must be aware of which channel it is currently receiving, which was determined by past channel selections.
[1] The television stores the current channel as part of its state. When a "channel up" or "channel down" input is given to it, the sequential logic of the channel selection circuitry calculates the new channel from the input and the current channel.


