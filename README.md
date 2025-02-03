# kalliope-stt-whisperer
Whisper STT Module for Kalliope

Refer to https://github.com/openai/whisper for details

<b>Installation:</b>
<p>
pip install openai-whisper<br/>
Create a directory whisperer in kalliope/stt<br/>
Copy all the .py files into kalliope/stt/whisperer<br/>
<br/>
In settings.yml add the following to the speech to text section</p>
<pre>
default_speech_to_text: "whisperer"
speech_to_text:
  - whisperer:
      language: "English"
      model: "small"
</pre>
The small english model will run on a machine with 8GB without swapping 
