# AudiobookMaker
Create a high quality .mp3 audiobook from a source .txt document using TTS from OpenAI

Work in progress looking at open source text from sources like the Gutenberg Project https://www.gutenberg.org/

First tested here with the Autobiography of Ben Franklin
https://www.gutenberg.org/ebooks/20203

and specificlly looking at the .txt file here - https://www.gutenberg.org/cache/epub/20203/pg20203.txt

Had to do some parsing to remove captions, preamble, introductions, etc. and get to just the raw autobiography

Eventually I want to have it narrated in the voice of Benjamin Franklin, I found this voice actor reading and want to use 
a service like elevenlabs.io to clone the voice and run the audio. Stopping here for now though.

<https://youtu.be/BIblI9nAk24> - voice model source for training
