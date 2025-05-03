markdown# 

AI Pitch Coach User Guide

This guide will help you use the AI Pitch Coach system to refine your startup pitch.

## Getting Started

To use the AI Pitch Coach, follow these steps:

1. Start the API server:
python run_api.py

2. In a new terminal window, run the CLI:
python coach_cli.py

## Using the CLI

The CLI provides an interactive interface to work with the AI Pitch Coach:

### 1. Create a New Pitch

Start by creating a new pitch. The AI will analyze your pitch structure, clarity, and persuasiveness, providing feedback on how to improve.

### 2. Refine Your Pitch

After receiving feedback, refine your pitch and submit it for another round of analysis. The system will track your improvements over time.

### 3. Simulate Investor Q&A

Practice answering tough investor questions specific to your startup's industry and funding stage. The AI will generate realistic questions and provide guidance on how to answer effectively.

### 4. View Pitch History

Track your progress over time by viewing the history of your pitch iterations and refinements.

### 5. List All Pitches

View all your saved pitches and load a previous pitch to continue working on it.

## Command Line Arguments

You can also use the CLI with command-line arguments:

- Analyze a pitch:
python coach_cli.py --analyze "Your pitch content here"

- Simulate Q&A:
python coach_cli.py --qa "Your pitch content here"

- View pitch history:
python coach_cli.py --history <pitch_id>

- List all pitches:
python coach_cli.py --list

## API Endpoints

If you prefer to integrate with the API directly:

- `GET /`: Welcome message
- `POST /analyze_pitch`: Submit a pitch for analysis
- `POST /simulate_qa`: Simulate investor Q&A
- `POST /pitch_history`: Retrieve pitch history
- `GET /all_pitches/{user_id}`: List all pitches for a user

## Best Practices

1. **Start Simple**: Begin with a concise one-sentence description of your startup
2. **Iterate Gradually**: Make incremental improvements based on feedback
3. **Practice Q&A Regularly**: Investor questions often reveal weak points in your pitch
4. **Focus on Clarity**: Ensure non-technical investors can understand your value proposition
5. **Track Progress**: Review your pitch history to see how far you've come