# H2E:A Multi-purpose Hindi-to-English Dataset

## Overview

This dataset is designed for multiple purposes, including projects involving the dubbing of movies from Hindi to English, active speaker recognition, lip synchronization, and text-to-speech (TTS) systems. The dataset includes video clips, original subtitles in Hindi, translated subtitles in English, and annotations for speakers, making it suitable for training machine learning models in various fields like automatic dubbing, speech recognition, active speaker recognition, lip-sync modeling, and TTS.

## Dataset Structure

The dataset is organized into the following directories:

```
/dataset/ 
├── /videos/              │ video001.mp4
                          │ video002.mp4
                          │ ...
├── /hindi_subtitles/     │ hindi001.srt
                          │ hindi002.srt
                          │ ...
├── /english_subtitles/   │ english001.srt
                          │ english002.srt
                          │ ...
└── /annotations/         │ annotations001.srt
                          │ annotations002.srt
                          │ ...

```
### Directory Descriptions

- **videos/**: Contains video clips of the movie scenes that require dubbing or lip synchronization.
- **hindi_subtitles/**: Contains the original Hindi subtitles in SRT format. These can be used for training lip synchronization models.
- **english_subtitles/**: Contains the translated English subtitles in SRT format, useful for dubbing and subtitle synchronization tasks.
- **annotations/**: Contains SRT files with speaker tags, useful for active speaker recognition tasks and character-based TTS systems.

## File Formats

- **Video Clips**: MP4 format.
- **Subtitles**: SRT (SubRip Subtitle) format, which includes timestamps and text.
- **Speaker Tags**: SRT format, with speaker identifiers for active speaker recognition.

## Multi-Purpose Usage

1. **Active Speaker Recognition**: The annotation files can be used to identify who is speaking in each video, making this dataset suitable for training models that need to recognize active speakers.
   
2. **Lip Synchronization**: The Hindi subtitle files, paired with video clips, can be used for training lip synchronization models. This is particularly useful for creating realistic lip movements in video retalking or dubbing systems.

3. **Text-to-Speech (TTS) Systems**: The subtitle files, both in Hindi and English, along with speaker annotations, can be used to train character-based TTS models that generate speech based on text and speaker identity.

## Usage Instructions

1. **Download the Dataset**: Access the dataset from the provided source.
2. **Access Video Clips**: Navigate to the `videos/` directory to find the video files.
3. **Use Subtitles**: Open the `hindi_subtitles/` and `english_subtitles/` directories to access the respective subtitle files. Load these files into your application for processing or display.
4. **Analyze Speaker Tags**: Review the speaker tags in the English subtitle files or annotations to identify who is speaking during the corresponding scenes.
5. **Train Models**: Use the video files, subtitles, and annotations to train models for active speaker recognition, lip synchronization, or TTS systems.

## License

This dataset is provided for research and educational purposes. Please ensure proper attribution and compliance with any usage restrictions specified by the original content creators.

## Contact

For questions or issues regarding the dataset, please contact dataset.flame@gmail.com
