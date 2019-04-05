# Real-time Captions for Time-based Media (RCTM) project 
The RCTM project delivers synced captions of Time-based Media artworks (i.e. video art) through a mobile website enabling audiences who are deaf, hard of hearing, or non-native english speakers to experience the piece. The project is funded by the Smithsonian Instition's Office of Accessibility through the Smithsonian Accessibility Innovation Fund. It is a joint effort with developers, technologists, and other museums professionals across the Smithsonian Institution who meet quarterly through the SI-Dev meetup group.

## The Problem
![Grid showing Hirshhorn Museum's existing transcript system](https://s3.amazonaws.com/saif-rctm/caption-challenge.png)

Time-based media artwork aren't always captioned, and often museums are retricted from adding captions. Printed transcripts provided to audiences can be cumbersome to use. Communicating the availability of transcripts, making them available on demand, and making them easy to use are challenging. Visitors reading through long transcripts often have little to no cues either on the transcript or the artworks, making it difficult to follow along.

## The Proposed Solution
By using HTTP methods the timeline of video art can be syncced to a server with REST APIs, which in turn can deliver captions through a web page syncced to the artwork.
![Tune project flow](https://s3.amazonaws.com/saif-rctm/tune-flow.png)

## The Components
There are two primary components of the project:
* [Tune: The server](https://github.com/ericpugh/tune)
* [Tune-pi: The Raspberry Pi-based synccing device](https://github.com/hmsgwebmaster/tune-pi)
