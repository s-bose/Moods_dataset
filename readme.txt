Meaning of the tags in Moodo dataset:
Age - The participant's age.
Gender - The participant's gender {Male, Female}
Living - Is participant living in the countryside or in city? {city, countryside}
YearsOfMusicEducation - How many years has or had the participant attended music school?
YearsOfInstrumentPlaying - How many years has or had the participant been playing an instrument or singing?
MusicListeningPerDay - How many many hours per day is the participant listening to the music?
	1 - Up to 1 hour per day
	2 - Between 1 and 2 hours per day
	3 - Between 2 to 3 hours per day
	4 - More than 3 hours per day
TakeMoodDrugs - Is participant prescribed any medicine which could influence mood at the time of taking the questionnaire? {yes, no}
UnderInfluenceOfDrugs - Is participant under influence of drugs at the time of taking the questionnaire? {yes, no}
PreferredGenres - Which are the most preferred genres by the participant? The participant was able to choose at least one and up to three most preferred genres, where Rank=1 is most preferred. {classical, opera, country, folk, latin, dance/disco, electronic, RnB/soul, hip hop/rap, reggae, pop, rock, alternative, metal, blues, jazz, vocal, easy listening, new age, punk}
CurrentMoodVA - What is the participant's current mood in the valence-arousal space? (V - valence [-1,1], A - arousal [-1,1])
CurrentMoodColor - What is the participant's current mood in HSV space? (H - hue [0,1], S - saturation [0,1], V -value [0,1])
CurrentMoodA - How significantly are the emotions expressed in the participant at the time of taking the questionnaire? [0,1] (0 - completely absent, 1 - significantly expressed)
EmotionVA - What is the valence-arousal space position of an emotion in participant's perception/opinion? (valence [-1,1], arousal [-1,1])
EmotionHSV - What is the participant's perception of best-matching color of an emotion/mood? (H - hue [0,1], S - saturation [0,1], V -value [0,1])
Songs - The participant's mood/color/emotion perception of songs
    SongID - ID (also filename) of song in our dataset
    Induced - A list of emotions which the song induced in the participant
        V, A - The position of the chosen induced emotion in the valence-arousal space [0,1]
    Perceived - A list of emotions which the song perceived by the participant
        V, A - The position of the chosen perceived emotion in the valence-arousal space [0,1]
    SongColor - The participant's choice of best-matching color of a song in the HSV space (H - hue [0-1], S - saturation [0-1], V -value [0-1])
