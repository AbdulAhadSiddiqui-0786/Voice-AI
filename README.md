# Voice-AI
For this assignment, I built a Call Quality Analyzer using Python and Hugging Face’s pyannote.audio. The system takes a sales call recording and first splits it into 30-second chunks for easier processing. It then identifies who is speaking and for how long, allowing us to calculate each speaker’s talk-time ratio and the longest monologues.

I also detect the number of questions asked and analyze the overall sentiment of the call to understand whether it was positive, negative, or neutral. Based on these results, the system generates a simple actionable insight, like whether the sales rep dominated the conversation or if the customer seemed dissatisfied.

To keep the Hugging Face API token secure, it isn’t stored in the notebook; it can be entered at runtime. This approach also makes it possible to handle larger calls efficiently while giving a clear picture of call quality.
