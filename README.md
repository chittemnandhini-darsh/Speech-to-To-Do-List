# Speech-to-To-Do-List
# 🎤 Speech-to-To-Do List

## 📌 Project Title

**Speech-to-To-Do List – Text and Speech Analysis Application**

## 📖 Description

Speech-to-To-Do List is a simple Text and Speech Analysis application that converts a user's spoken instructions into text and automatically identifies tasks from the speech.

The application uses **Speech Recognition** to convert audio into text and then analyzes the text to find task-related sentences. These tasks are displayed as an organized To-Do List.

### 🔄 Working Flow

**🎤 Audio Input → 🗣️ Speech-to-Text → 🔍 Task Detection → ✅ To-Do List**

---

## 🎯 Objectives

* Convert human speech into text.
* Analyze the converted text.
* Identify sentences containing tasks.
* Automatically create a To-Do List.
* Provide a simple web interface for users.
* Demonstrate speech and text analysis using Python.

---

## ✨ Features

* 🎤 Upload an audio file.
* 🗣️ Convert speech into text.
* 🔍 Automatically detect tasks.
* 📝 Generate an organized To-Do List.
* 🌐 Simple web application interface.
* ☁️ Can be run using Google Colab.
* 📁 Supports audio files such as WAV and MP3.

---

## 🛠️ Technologies Used

| Technology                | Purpose                               |
| ------------------------- | ------------------------------------- |
| Python                    | Main programming language             |
| Google Colab              | Development and execution environment |
| Gradio                    | Web application interface             |
| SpeechRecognition         | Speech-to-text conversion             |
| PyDub                     | Audio conversion                      |
| Regular Expressions       | Task detection and text processing    |
| Google Speech Recognition | Speech recognition service            |

---

## 📂 Input

The application accepts an audio recording containing spoken tasks.

### Example Speech

> "I need to complete my Python assignment. Submit the project tomorrow. Call the team leader. Study computer networks."

---

## 📤 Output

### 🗣️ Converted Speech

```text
I need to complete my Python assignment.
Submit the project tomorrow.
Call the team leader.
Study computer networks.
```

### ✅ Generated To-Do List

```text
☐ 1. I need to complete my Python assignment.
☐ 2. Submit the project tomorrow.
☐ 3. Call the team leader.
☐ 4. Study computer networks.
```

---

## 🔍 Task Detection

The application searches for task-related words and phrases such as:

* need to
* have to
* must
* should
* complete
* finish
* submit
* prepare
* call
* send
* buy
* read
* write
* study
* attend
* meet
* create
* make
* check
* review
* remember to

When one of these words is found in a sentence, that sentence is considered a task.

---

## 🚀 How to Run in Google Colab

### Step 1: Open Google Colab

Create a new Google Colab notebook.

### Step 2: Copy the Python Code

Paste the complete Speech-to-To-Do List code into one Colab cell.

### Step 3: Run the Cell

Click the **Run ▶️** button.

The required Python libraries will be installed automatically.

### Step 4: Open the Gradio Application

After execution, Gradio will provide a web interface.

### Step 5: Upload Audio

Click:

**🎤 Upload Your Voice Recording**

Upload a `.wav` or `.mp3` audio file.

### Step 6: Generate Tasks

Click:

**📝 Generate To-Do List**

The application will display:

1. Converted Speech
2. Detected Tasks

---

## 🧪 Testing Example

### Input

```text
I need to complete my Python assignment.
Submit the project tomorrow.
Call the team leader.
Study computer networks.
```

### Expected Output

```text
☐ 1. I need to complete my Python assignment.
☐ 2. Submit the project tomorrow.
☐ 3. Call the team leader.
☐ 4. Study computer networks.
```

---

## 📁 Project Structure

```text
Speech-to-To-Do-List/
│
├── speech_to_todo.py
├── sample_audio.wav
└── README.md

<img width="935" height="350" alt="Screenshot 2026-10-04 142812" src="https://github.com/user-attachments/assets/a586e12d-131a-4a86-8482-6669dc283e5c" />

<img width="924" height="188" alt="Screenshot 2026-10-04 142836" src="https://github.com/user-attachments/assets/ba5e5878-0a75-4f52-9e8b-94edcadd005e" />

![Uploading Screenshot 2026-10-04 142852.png…]()

