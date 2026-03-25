# Emojino - Remove emojis from text

Just say no to emojis.

## Features

- **Emojis are Gone now**: You had a text file, output from that LLM you like, and it's brimming with rediculous green check marks. Not anymore.
- **Text for Grownups**: Input ai slop, output mildly legible literature.

## How to Use

0. Download/clone me
0.1 chmod 744 emojino
1. emojino filename.txt   or   echo "string of emojis"|emojino
2. Add me to your path for text devoid of emojis but now full of value and joy

### Format / Performance Notes

It works with text files and strings of text. Really large files will depend on your system's ulimits, memory, and buffers and follow O(n). If you're using this in your advanced SaaS ETL pipeline for multiple terabytes of data then you may ask yourself how you got here and if there's a better alternative. 

### Dependencies

- **Python**: Prolly going to need that one and noted libraries

## Security/Privacy

- Runs local. Does not share/expose your work. It's the simplest of scripts.

## License

MIT License - As is, do what thou wilt.

## Thank you!

Yes, emojino is wee, yes you could ai this right out in a few minutes, but if you like and use it, please contribute via the Sponsor <3 button on the right or at the top of the page. Thank you!
