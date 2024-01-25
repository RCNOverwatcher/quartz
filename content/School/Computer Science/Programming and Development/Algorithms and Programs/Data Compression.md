---
banner: "![[computerscience.jpg]]"
---
# Data Compression

> [!Info] Intro
> - Files can be compressed using different 'codecs'. A codec is simply a program that takes a stream of digital data and applies a maths formula to it. These maths formulas are called codecs (short for 'coder-decoder') and they compress the data stream file so that it is smaller. There are two different approaches to using codecs to compress files. These are 'lossy compression' and 'lossless compression'. Lossy compression is often used for sound, video and picture work whereas lossless is more often used with text and data files.
![[Lossy.gif]]

> [!Info] Lossy Compression
>-  In 'lossy compression', a maths formula is used to remove the parts of a file which are deemed relatively unimportant before compressing it. The parts that are removed are not normally noticeable by most people.
> - In a sound file, for example, there are some sounds that are out of the range of the human ear so these might reasonably be removed. Some popular lossy codecs for sound include MP3 and OGG (Ogg Vorbis). When a file is saved as an MP3 file, a tiny bit of sound quality is lost. Most people wouldn't notice, although a musician or sound engineer might. They might prefer to save files using lossless compression, such as FLAC or ALAC.
> - JPG is an example of a lossy picture codec. Each time you save a picture as a JPG, a little bit of information is lost, although it would be hard for most people to tell the difference. Of course, if you worked in graphics design, losing this information might be very important so you might prefer to use a lossless method such as PNG.
> - Lossy movie compression formats include MPEG4 and WMV files. These squash raw movie files down, removing the parts that you probably wouldn't miss or notice when watching a film. If you needed to retain all the data in a film after compression, so you could get back the original completely (perhaps for further editing purposes) then you would need to use a lossless video compression format, such as Huffyuv.

> [!Info] Lossless Compression
> - In 'lossless compression', the codecs keep all of the information about a file. The compressed file, once decompressed, can be reconstructed so it is exactly like the file before it was compressed, with no loss of any information at all. This would be very important if you needed to get access to the highest quality file possible, the original file, without any loss of data.
> - In a sound file, for example, all of the information that makes up the file is kept if it is stored using a lossless codec. The file format WAV is an example of a lossless codec. Lossless sound codecs give you a smaller file than the raw sound file but give you a very high quality sound. Lossy sound codecs, on the other hand, give you a much smaller sound file but with some loss of quality (although most people would struggle to notice the difference).
> - GIF and PNG files are examples of codecs which take a bitmap and compress it without discarding any of the original picture information. Huffyuv is a codec that can be used to save raw movie data so that it can be reconstructed without any loss of data in the future.

> [!Example]- Questions
> **Q1.** What is meant by a zip file?  
**Q2.** Are compressed files bigger or smaller than the original contents?  
**Q3.** What unit is used to measure file size?  
**Q4.** Describe with an example how file compression is achieved.  
**Q5.** You want to save lots of photos and videos on your pen drive but they won't fit. What could you do about this problem?  
**Q6.** What is meant by 'video streaming'?  
**Q7.** Why are videos compressed during the streaming process?  
**Q8.** What is meant by open source software?  
**Q9.** State one open source application for compressing files.

> [!Tip]- Answers
> 1. A zip file is a way of compressing folders. Common formats are .zip, .rar and .7z.
> 2. Compressed files are smaller than the originals.
> 3. Bytes
> 4. If a bit of text appears more than once, the compression software gives the data a key. This key can be referenced and since the key is shorter than the original block of text, it reduces the overall file size.
> 5. Compress the files
> 6. Downloading certain parts of a file temporarily from a server to allow for less disk space used up on the client side.
> 7. It takes less time to transfer the data to the client.
> 8. Non-properiatry and free software that has no trackers and the source code is publicly avaliable.
> 9. 7Zip

