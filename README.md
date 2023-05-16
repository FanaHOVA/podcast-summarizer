# [WIP] Podcast Summarizer

### Do not try to use this!

I listen to a lot of podcasts, especially while driving, which makes it hard to take notes. This notebook is a WIP environment to build a podcast summarizer. I will then feed these notes into my Obsidian vault.

Stack:
- Optional: ytdl to download the audio from YouTube
- OpenAI Whisper to transcribe it
- LangChain to split up the text and feed it to davinci
- Get the summary
- Bonus: Create a Twitter thread for social sharing

Instructions:
- Download the audio from YT with the ytdl cell by putting it in the URL list, or copy your audio file in `./tmp`
- Run the cells
- Find raw transcript in `podcast-raw-transcripts`
- Find clean transcript in `podcast-clean-transcripts`

TODOs:
- Add Obsidian integration