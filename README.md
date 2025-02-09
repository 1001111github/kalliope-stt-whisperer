# Whisperer STT
Whisper STT Module for Kalliope Refer to [here](https://github.com/openai/whisper) for details.

## Installation
```bash
kalliope install --git-url https://github.com/github10011111/kalliope_stt_whisperer.git
```

## Parameters

| parameter    | required | type    | default | choices                     | comment                                                                                          |
|--------------|----------|---------|---------|-----------------------------|----------------------------|
| language     | No       | string  |'English'|                             | 
| model        | No       | string  |'base'   |'tiny','base','small','large'| Model size, resource needs

## Example settings

```yaml
#

default_speech_to_text: "whisperer"
speech_to_text:
  - whisperer:
      language: "English"
      model: "small"
```
