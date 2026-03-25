  ---
  📋 About

  60db Flow is a Windows desktop application that automatically records meetings and generates AI-powered transcriptions. It
   captures both your microphone audio AND system audio (other participants), so you never miss any part of the
  conversation.

  ---
  ✨ Features

  ┌─────────────────────────┬─────────────────────────────────────────────────────────────────────┐
  │         Feature         │                             Description                             │
  ├─────────────────────────┼─────────────────────────────────────────────────────────────────────┤
  │ 🎙️ Dual Audio Recording │ Captures both your microphone AND system audio (other participants) │
  ├─────────────────────────┼─────────────────────────────────────────────────────────────────────┤
  │ 🤖 AI Transcription     │ Automatic speech-to-text transcription using advanced AI            │
  ├─────────────────────────┼─────────────────────────────────────────────────────────────────────┤
  │ 📝 Meeting Notes        │ Generates summaries, key points, and action items                   │
  ├─────────────────────────┼─────────────────────────────────────────────────────────────────────┤
  │ 🔍 Auto-Detection       │ Detects active meetings from Zoom, Teams, Google Meet, etc.         │
  ├─────────────────────────┼─────────────────────────────────────────────────────────────────────┤
  │ 🎯 Global Shortcut      │ Quick access with keyboard shortcuts                                │
  ├─────────────────────────┼─────────────────────────────────────────────────────────────────────┤
  │ 💾 Local Storage        │ All recordings saved locally on your computer                       │
  ├─────────────────────────┼─────────────────────────────────────────────────────────────────────┤
  │ 🔒 Privacy First        │ No data sent to third parties without your consent                  │
  └─────────────────────────┴─────────────────────────────────────────────────────────────────────┘

  ---
  🖥️ Requirements

  - OS: Windows 10 or Windows 11 (64-bit)
  - RAM: 4GB minimum
  - Storage: 500MB free space
  - Microphone: Required for recording your voice
  - Speakers/Headphones: Required for system audio capture

  ---
  📥 Download

  Download the latest release from the ../../releases page:

  ┌───────────────────────────────┬──────────────────────┐
  │             File              │     Description      │
  ├───────────────────────────────┼──────────────────────┤
  │ 60db-flow_0.1.0_x64_en-US.msi │ Windows installer    │
  ├───────────────────────────────┼──────────────────────┤
  │ 60db-flow-public.cer          │ Security certificate │
  └───────────────────────────────┴──────────────────────┘

  ---
  🚀 Installation

  Step 1: Install Certificate

  This app uses a self-signed certificate. Install it once to trust the app:

  1. Download 60db-flow-public.cer
  2. Right-click the file → Install Certificate
  3. Select "Local Machine" → Click Next
  4. Select "Place all certificates in the following store"
  5. Click Browse → Select "Trusted Root Certification Authorities"
  6. Click OK → Next → Finish
  7. Click Yes on the security prompt

  Step 2: Install Application

  1. Download 60db-flow_0.1.0_x64_en-US.msi
  2. Double-click to run the installer
  3. Follow the installation wizard
  4. Launch 60db Flow from Start Menu

  ---
  🎯 How to Use

  Record a Meeting

  1. Open 60db Flow
  2. Click "Start Recording" or use the global shortcut
  3. The app captures:
    - ✅ Your voice (microphone)
    - ✅ Other participants (system audio)
  4. Click "Stop Recording" when done

  View Transcription

  1. Go to "Meeting Notes" section
  2. Click on any recording to view:
    - Full transcript
    - AI-generated summary
    - Key points and action items

  ---
  ⚙️ Configuration

  ┌─────────────────┬───────────────────────────────────────────┐
  │     Setting     │                Description                │
  ├─────────────────┼───────────────────────────────────────────┤
  │ Global Shortcut │ Set keyboard shortcut for quick recording │
  ├─────────────────┼───────────────────────────────────────────┤
  │ Auto-Detect     │ Enable automatic meeting detection        │
  ├─────────────────┼───────────────────────────────────────────┤
  │ Audio Quality   │ Choose recording quality (Standard/High)  │
  ├─────────────────┼───────────────────────────────────────────┤
  │ Save Location   │ Custom folder for recordings              │
  └─────────────────┴───────────────────────────────────────────┘

  ---
  🔧 Troubleshooting

  "Windows protected your PC" warning

  Make sure you installed the certificate (60db-flow-public.cer) following Step 1 above.

  Only my voice is recorded

  - Ensure speakers/headphones are connected
  - Check Windows volume is not muted
  - Verify the meeting audio is playing through speakers

  App not detecting meetings

  - Make sure the meeting app (Zoom, Teams, etc.) is running
  - Enable "Auto-Detect" in settings

  ---
  📂 File Locations

  ┌────────────┬─────────────────────────────────┐
  │    Data    │            Location             │
  ├────────────┼─────────────────────────────────┤
  │ Recordings │ %APPDATA%\60db-flow\recordings\ │
  ├────────────┼─────────────────────────────────┤
  │ Database   │ %APPDATA%\60db-flow\            │
  └────────────┴─────────────────────────────────┘

  ---
  🛡️ Privacy & Security

  - All recordings are stored locally on your computer
  - Audio is sent to AI services only for transcription (when you request it)
  - No data is collected or shared without your explicit action
  - Your meeting content remains private

  ---
  📝 License

  For internal use.
