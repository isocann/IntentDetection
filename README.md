# IntentDetection
Intent detection is a crucial task in the field of natural language processing (NLP) and speech recognition. It involves identifying the underlying intention or purpose of a spoken or written statement. This task is particularly important in the development of voice assistants and other audio-based applications, as it allows the system to understand and respond appropriately to the user’s requests and commands.

# Objective
For a given an input audio sample, the goal is to predict both the action requested and the object that is affected by the action (e.g., if the action is “increase” and the object is “volume”, the corresponding intent will be “increasevolume”).

# Dataset
The dataset consists in a collection of audio file in a WAV format. There are 9854 sound files created by 87 different speakers in the dataset. There are 1455 audio data in the Evaluation set. 
• path: the path of the audio file.
• speakerId: the id of the speaker.
• action: the type of action required through the intent.
• object: the device involved by intent.
• Self-reported fluency level: the speaking fluency of the speaker.
• First Language spoken: the first language spoken by the speaker.
• Current language used for work/school: the main language spoken by the speaker during daily activities.
• gender: the gender of the speaker.
• ageRange: the age range of the speaker.

# Evaluation metric
Accuracy



