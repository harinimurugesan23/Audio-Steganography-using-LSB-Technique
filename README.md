# Audio-Steganography-using-LSB-Technique
Developed an Audio Steganography application using the LSB technique to securely hide and extract secret messages in audio files. Features include user authentication, message embedding and retrieval, audio playback, and secure data transmission while maintaining audio quality.

### Live Access Link

https://smart-network-monitoring-and-traffic.onrender.com/

### Overview
Advanced Audio Steganography is a secure data-hiding application that uses the Least Significant Bit (LSB) technique to embed secret text messages within audio files. The project enables users to hide sensitive information in audio files without noticeably affecting audio quality.

### Features
1. User Registration and Login
2. Hide Secret Messages in Audio Files
3. Extract Hidden Messages from Audio Files
4. Audio Playback Support
5. Email Notification Feature
6. User-Friendly Interface
7. Secure Message Transmission
   
### Technologies Used
1. Python
2. Tkinter (GUI)
3. Wave Module
4. SMTP (Email Service)
5. LSB Steganography Technique
   
## How It Works
### Message Embedding
1. User selects an audio file.
2. A secret message is entered.
3. The application converts the message into binary format.
4. The Least Significant Bits of audio samples are modified to store the message.
5. A new stego-audio file is generated.
### Message Extraction
1. User selects the stego-audio file.
2. The application reads the modified bits.
3. Hidden data is reconstructed and displayed.

## Project Modules
### Authentication Module
1. User Registration
2. User Login
3. Credential Verification
### Hide Message Module
1. Select Audio File
2. Enter Secret Message
3. Generate Stego Audio File
### Extract Message Module
1. Load Stego Audio File
2. Recover Hidden Message
3. Email Module
4. Send confirmation emails
5. Notify users after successful operations

## Project Outcome

The project successfully demonstrates secure information hiding within audio files using the LSB technique while maintaining the integrity and quality of the original audio.
