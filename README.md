I've created a comprehensive Call Quality Analyzer optimized for Google Colab's free tier that will process your sales call in under 30 seconds. Here's what the system does:
🎯 Core Features

Talk-Time Ratio: Calculates speaking percentage for each participant
Question Counter: Uses regex patterns to identify and count questions
Longest Monologue: Finds continuous speech segments by speaker
Sentiment Analysis: Uses VADER sentiment analyzer for real-time processing
Actionable Insights: Generates specific coaching recommendations
Bonus: Identifies sales rep vs customer using speech patterns and keywords

⚡ Colab Optimizations

Whisper "tiny" model: Fastest transcription while maintaining accuracy
Efficient audio processing: 16kHz mono, limited duration for memory constraints
Simple speaker diarization: Energy-based detection instead of heavy ML models
VADER sentiment: Lightweight, rule-based sentiment analysis
Smart cleanup: Removes temporary files to free memory

🔧 How It Works

Downloads audio from YouTube using yt-dlp with optimized settings
Transcribes speech using Whisper with word-level timestamps
Identifies speakers using silence detection and speech patterns
Analyzes metrics through text processing and audio features
Generates insights based on sales call best practices
Creates visualizations showing talk distribution and timeline

🎪 Special Features for Poor Audio Quality

Whisper's robust noise handling
Dynamic threshold adjustment for voice detection
Multiple question detection patterns to catch unclear speech
Fallback processing methods

📊 Output Includes

Detailed breakdown of all 5 required metrics
Speaker role identification (sales rep vs customer)
Visual charts showing talk distribution and sentiment
Processing time tracking to ensure <30 second target
Comprehensive error handling and progress indicators

