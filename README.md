# ChatGPT for Organize Transcript
This simple tool uses ChatGPT to organize video transcripts into a finished article. It could be from Youtube, Bilibili, or any plain subtitle file without a timecode.
The tool takes a folder of text files as input and outputs processed text files side by side. 

## Inspiration

I use this tool for my personal usage. 
I forked and modified it from https://github.com/Raychanan/ChatGPT-for-Translation

## Simple Example

```
git clone https://github.com/hyyz17200/ChatGPT-for-Organize-Transcript.git
cd ./ChatGPT-for-Organize-Transcript/
pip install -r requirements.txt --quiet
python ChatGPT-transcript.py --input_path=./input/ --openai_key=password 
```

## Prerequisites
You need a OpenAI API key (https://beta.openai.com/signup/)
