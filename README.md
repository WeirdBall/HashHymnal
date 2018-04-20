# BoulderH3 Hash Hymnal
A collection of songs heard and sung by the Boulder Hash House Harriers.

Be warned, this is a collection of dirty drinking songs.  Many of them are obscene, scatological, offensive, and in poor taste.  If this bothers you, please just give this collection a pass.

## The Hash House Harriers
 
 The Hash House Harriers are a number of social drinking and running clubs (called kennels) throughout the word.  Some members (the hares) lay a trail of markings in flour, chalk, etc, which the rest of the members (the pack of hounds) need to search for and follow—something of a scavenger hunt leading to beer.
 
At the end of the run, the hashers all gather in a circle to drink some beer, take turns calling people out into the circle for recognition or accusations, and sing a bunch of dirty drinking songs.

## The Songs

The songs sung at the hash come from a variety of sources—many plundered from rugby, classic dirty or drinking songs, parodies composed by hashers…  There is a large element of oral tradition, as new hashers learn the songs they hear during the circle, and hashers visiting or moving to other kennels learn and transmit new songs or variations.  Consequently, songs tend to be misremembered, tweaked for local taste, and evolve.  While different kennels often sing many of the same songs, visitors and transplants will sometimes find songs to vary slightly, have a different tune, or even be completely different from kennel to kennel.  These songs are largely transcribed from memory to capture the way they are currently sung after trails of the Boulder Hash House Harriers.

Another side effect of the distributed oral tradition and casual transmission of hash songs is that their origin becomes murky.  I've annotated the source of those I know, but many of the songs are just "someone brought it back from the SF hash" or "the one that old guy used to sing".  If you know who composed a particular song (not just who you learned it from), feel free to let me know or submit a pull request.

## Contributing



### Corrections

This is a collection of songs mainly transcribed from memory.  I'm sure it's riddled with typos, errors, and misunderstandings.  Any editing or corrections are welcomed.  However, if you've learned these songs at a different kennel's circle or many years ago, it may just be that the Boulder H3 sings the song differently these days.

### New Songs

Have a song I forgot?  Feel free to write it down.  The songs are all text files in the `songs` directory.  Each song should begin with a number of metadata lines, with `Title:` and `Tags:` required and optionally `Tune:`, `AKA:`, `See:`, `Source:`, `Copyright:` if known or relevant.  Then a blank line, followed by the song's lyrics as [Markdown](http://daringfireball.net/projects/markdown/syntax)-formatted text, with the extension that single line-breaks remain as `<br>` tags in the output (while double line-breaks still make new paragraphs), making it easier to correctly format lyrics.

### Website generation

The songs are used to render the [Jinja](http://jinja.pocoo.org/docs/dev/templates/) templates in the `templates` directory, and combined with the files in the `static` directory to create the final website using the [songbook.py](http://github.com/JiBB/songbook/) script.  
