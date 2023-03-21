# Video-Summarization-for-Football
ACM NITK Project. Highlights of full length Football match.
# Introduction
Due to increase in popularity of Video Streaming websites like Youtube, the number of videos on a particular topic have increased exponentially. An effective way to summarize long videos is required which saves time and effort of the viewer. A video summarization technique is proposed, keeping the game of football in mind. Important events such as goals, missed goals, yellow cards and substitutions are identified in a football match and short clips covering these events are captured. These clips are then concatenated in their order of occurrence to form a summarized video. A 90 minute full match is converted into a 3-4 minute video summary. A mixed approach using Sound Analysis, Transfer Learning and Optical Character Recognition is taken to tackle this problem
# Dataset
# Components
## OCR Module
Optical Character Recognition (OCR) is a technology that allows computers to recognize and interpret printed or handwritten text from images or scanned documents. It can be used in various applications such as document digitization, data entry, and automation.

In the context of a football match, OCR can be used to identify the substitutions made during the game. The word "SUBSTITUTION" is typically displayed by the broadcaster on the screen to indicate that a substitution is being made. OCR technology can capture this information from the screen and convert it into digital text, which can then be used for various purposes such as updating the scorecard, generating statistics, or displaying on-screen graphics.

Tesseract is a popular open-source OCR library developed by Google. It is known for its high accuracy and reliability, especially for recognizing English text. Tesseract can be integrated into various programming languages such as Python, Java, and C++, and can be used for both on-device and cloud-based OCR applications.

In the context of a football match, Tesseract can be used to recognize the word "SUBSTITUTION" from the broadcast screen and extract relevant information such as the player's name and the minute of the substitution. Tesseract can also be trained to recognize other languages and scripts, which can be useful in international football matches where multiple languages may be used.
## Audio Module
## Object Detection Module
