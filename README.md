🎵 SoundSage: Music Genre Classifier
This project uses Machine Learning to automatically identify if a song is Rock or Hip-Hop. It analyzes "audio fingerprints" like tempo, danceability, and energy to tell the difference between genres.

✨ What this project does
Cleans Audio Data: Organized a dataset of thousands of songs into a format the computer can understand.

Simplifies Features: Automatically picked out the most important parts of the music to make predictions faster.

Fixes Bias: Made sure the AI saw an equal amount of Rock and Hip-Hop songs so it didn't play favorites.

Compares Models: Tested two different AI "brains" to see which one was better at recognizing music.

🛠️ Tools Used
Python

Pandas

Scikit-Learn

Matplotlib & Seaborn

📊 Final Results
I tested two different methods to see which was more accurate:

Logistic Regression: 85% Accuracy 🏆 (The Winner)

Decision Tree: 81% Accuracy

🚀 How to use it
Input the audio numbers for a song into the classifier, and the AI will detect the genre:

Python

# Example prediction output:
"Predicted Genre: Hip-Hop"
💡 Why this is useful
This kind of technology is used by streaming services to organize libraries and recommend new music based on the "vibe" and audio characteristics of the songs you already like.
