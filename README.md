# Video Subtitle
Adding English subtitles for a Mandarin video
This script first transcribes the video using the OpenAI Whisper API to srt file. It then uses the translate API to translate the srt file into the langauge of choice.
Lastly, using Moviepy, the srt are burned into the original video. 
