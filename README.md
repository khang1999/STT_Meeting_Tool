# STT_Meeting_Tool

This meeting tool will be used to collect and parse audio from meetings for future analysis.

# Planning
There are two different variations that can be implemented:
1. A single stream of audio of meeting
2. Multiple streams of audio of meeting

Components:
- Audio collector:
	1. One single audio stream with buttons assigned to each person
	2. Multiple audio streams from different people that will be parsed together

- Tagger:
	1. Each button will have a tagger associated with metadata for each person
	2. Each audio stream will have a tagger associated with the metadata for each person

- Timestamps:
	1. Timestamps will be implemented when a button is pressed
	2. Timestamps will be recorded for pauses in a person's speech pattern

- Transcription:
	1. The audio will be transcribed using the most successful Deepspeech Model
	2. The audio will be transcribed using the most successful Deepspeech Model

- Post Processing:
	1. The audio will be broken down into intervals based on who was speeaking, using the timestamps from the tags
	2. The audio will be broken down into intervals based on pauses

