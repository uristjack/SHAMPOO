# SHAMPOO
_Simulation of characters for narration of serial dramas._

SHAMPOO is a software system which creates soap operas.
Rather than using a author-goal driven system like UNIVERSE, SHAMPOO uses a character-goal driven system.
Characters have personalities, moods, and emotions.
There are many actions that each character can take, and these have different effects on their (and other character's) emotions.
Characters have a very greedy planning system, meaning that they act for personal short-term gain.
This will lead to melodrama as characters' relationships change, and as they murder, cheat, and backstab for personal gain.

Personalities will be simulated using an approach similar to UNIVERSE. 
Characters have basic professions, stereotypes, hobbies, and so forth, which gives them a personality based around these metrics:
- Physique
- Intelligence
- Moodiness
- Guile
- Self-confidence
- Niceness
- Competence
- Promiscuity
- Wealth
- Religion
- Race
- Nationality

Each character will have different "frames" which add up to their total personality, but also dictate how they act during the day (working, usually), the night, evening, and so forth.
Their personalities will also effect their mood and emotional systems.

Emotions will be simulated using a system based upon [Plutchik's wheel of emotions.](http://2.bp.blogspot.com/-2zsSl4tM9xY/VNC4J_p2iwI/AAAAAAAACqI/eyPhNyxAgsE/s1600/IMG_20150203_172727.JPG)
There are 8 basic emotions that characters can have:
- Happiness
- Trust
- Fear
- Surprise
- Sadness
- Disgust
- Anger
- Anticipation

Moods are based upon a reward/punishment system.
For any positive emotions that characters experience, their moods will increase, signalling reward. For any negative emotions, their moods will decrease, signalling punishment. This will also modulate their behaviour.

Relationships will also be simulated using an approach similar to UNIVERSE. 
Each character will hold a model of their relation to other characters on several metrics:
- Positivity / Negativity of relationship
- Intimacy / Distance of relationship
- Dominance / Submission of relationship
- Attractedness to other character

These relationships are not mutual, but are tracked on a per-character basis.
