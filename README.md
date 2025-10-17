# 🎶 AI Music Generation

This project uses a Long Short-Term Memory (LSTM) neural network to generate new musical sequences based on classical MIDI input data. It was developed as part of the CodeAlpha internship tasks.

---

## 📘 Project Overview
The model learns from MIDI files and predicts new note sequences, creating an AI-composed piece of music.

**Steps:**
1. Collected and preprocessed MIDI data.
2. Extracted and tokenized note sequences.
3. Built and trained an LSTM model using Keras.
4. Generated a new sequence of notes.
5. Saved the final composition as a `.mid` file.

---

## 🧠 Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Music21  
- PrettyMIDI  

---

## Output
The generated music file: `AI_Composition.mid`

You can open or play it with any MIDI player or DAW (like FL Studio, GarageBand, or MuseScore).

---

## 📂 How to Run
1. Open the Colab notebook.
2. Upload your MIDI training dataset.
3. Run all cells to train and generate music.
4. Download and play the final output.

---

## 🏁 Status
✅ Completed successfully  
Model trained for 50 epochs and generated a valid musical sequence.

---

**Author:** Blessing Jimoh  
**Internship:** CodeAlpha – Task 3: AI Music Generation
