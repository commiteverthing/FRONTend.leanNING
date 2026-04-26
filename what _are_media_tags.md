--------> HTML <audio> Tag

Definition and Usage

The <audio> tag is used to embed sound content in a document, such as music or other audio streams.

The <audio> tag contains one or more <source> tags with different audio sources. The browser will choose the first source it supports.

The text between the <audio> and </audio> tags will only be displayed in browsers that do not support the <audio> element.

There are three supported audio formats in HTML: MP3, WAV, and OGG.

 
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio> 


--------> Attributes

Attribute 	Value 	Description
autoplay 	autoplay 	Specifies that the audio will start playing as soon as it is ready
controls 	controls 	Specifies that audio controls should be displayed (such as a play/pause button etc)
loop 	loop 	Specifies that the audio will start over again, every time it is finished
muted 	muted 	Specifies that the audio output should be muted
preload 	auto
metadata
none 	Specifies if and how the author thinks the audio should be loaded when the page loads
src 	URL 	Specifies the URL of the audio file



--------> HTML <video> Tag

The <video> tag is used to embed video content in a document, such as a movie clip or other video streams.

The <video> tag contains one or more <source> tags with different video sources. The browser will choose the first source it supports.

The text between the <video> and </video> tags will only be displayed in browsers that do not support the <video> element.

There are three supported video formats in HTML: MP4, WebM, and OGG.

<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video> 



------> Optional Attributes

Attribute 	Value 	Description
autoplay 	autoplay 	Specifies that the video will start playing as soon as it is ready
controls 	controls 	Specifies that video controls should be displayed (such as a play/pause button etc).
height 	pixels 	Sets the height of the video player
loop 	loop 	Specifies that the video will start over again, every time it is finished
muted 	muted 	Specifies that the audio output of the video should be muted
poster 	URL 	Specifies an image to be shown while the video is downloading, or until the user hits the play button
preload 	auto
metadata
none 	Specifies if and how the author thinks the video should be loaded when the page loads
src 	URL 	Specifies the URL of the video file
width 	pixels 	Sets the width of the video player