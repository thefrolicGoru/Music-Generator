# Music-Generator
This music generator utilizes a Long Short-Term Memory (LSTM) neural network to compose new music based on existing MIDI files. The code, written in Python, employs the TensorFlow library along with music21 for MIDI file parsing. After mounting Google Drive (if using Google Colab), the script processes MIDI files, extracts musical elements like notes and chords, and trains the LSTM model with a sequence length of 100 and 200 epochs. The model architecture involves three LSTM layers, dropout layers, and dense layers. Once trained, the generator randomly selects a starting point and predicts the subsequent notes, creating a unique musical sequence. The resulting composition is saved as a MIDI file for playback and further exploration.






