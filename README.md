# audiostreamer-meta
Automatically exported from code.google.com/p/audiostreamer-meta

Mon 30th March 2015

Did the basic conversions to make it work on iOS 8.2, for the latest group of iPhones.
However. If you want the metadata, which I'm intersted in, it works best on MP3, aka Shoutcast and Icecast
It does work from some other stream types, but not all types. I havent yet got it working with OGG for example, 
but that may just be me. 
It's close - but no cigar....
2015-03-30 13:38:55.569 iPhoneStreamingPlayer[40159:4825618] Stream Content-Type: application/ogg
AudioQueueStop err \316\377\377\377 -50
AudioQueueReset err \316\377\377\377 -50
2015-03-30 13:38:55.569 iPhoneStreamingPlayer[40159:4825618] Audio Type Hint: application/ogg
2015-03-30 13:38:55.569 iPhoneStreamingPlayer[40159:4825618] Stream Bitrate: Quality 4.00
2015-03-30 13:38:55.571 iPhoneStreamingPlayer[40159:4825618] Stream Bitrate: Quality 4.00
2015-03-30 13:38:55.572 iPhoneStreamingPlayer[40159:4825618] mFormatID: 2
2015-03-30 13:38:55.581 iPhoneStreamingPlayer[40159:4825618] 13:38:55.580 ERROR:     >aq> 323: AudioConverterNew from AudioQueueNew returned 'fmt?'
io:     2 ch,  16000 Hz, Float32, non-inter
client:    2 ch,  16000 Hz, '.mp2' (0x00000000) 0 bits/channel, 0 bytes/packet, 1152 frames/packet, 0 bytes/frame
AudioQueueNewOutput err ?tmf 1718449215
2015-03-30 13:38:55.581 iPhoneStreamingPlayer[40159:4825618] BITRATE: 144000


So in short - While it works fine for mp3 streams, and even aac streams - some. If you are streaming other stuff, 
it will need a lot of work yet. But close.

