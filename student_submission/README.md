# Audio Modem - Ex1 Submission

## What I Did

- Cloned the `amodem` project from GitHub
- Installed the library using `pip install amodem`
- Encoded the message "hello world" into audio using:
  `echo "hello world" | amodem send -o message.wav`
- Played the audio file
- Decoded the audio back into text using:
  `amodem recv -i message.wav`

## Files

- `message.wav`: Audio file with the encoded message
- `README.md`: This file

## Notes

No hardware was used. All audio processing was done using my computer’s speaker and software only.
I used in this assignment the assistance of chatGPT.
