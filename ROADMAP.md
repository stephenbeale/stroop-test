# Stroop Test - Product Roadmap

## Feature 1: No-Colour-Fill Button Toggle

Add a toggle that removes the colour background from buttons, leaving only the text label. This forces players to read the word on each button rather than relying on the button colour as a visual cue.

## Feature 2: Difficulty Levels (Easy / Medium / Hard)

Replace individual toggles with three preset difficulty levels that group settings together.

### Easy

- Colour-filled buttons (background matches label)
- Labels shown on buttons
- No button shuffling
- 10-second starting timer
- Timer reduces by 1s every 10 correct answers (minimum 2s)

### Medium

- Colour-filled buttons
- Labels hidden
- Shuffle buttons every 10 answers
- 8-second starting timer
- Timer reduces by 1s every 10 correct answers (minimum 2s)

### Hard

- No colour fill on buttons (plain/neutral background)
- Labels shown (text only, no colour cue)
- Shuffle button order after every correct answer
- 6-second starting timer
- Timer reduces by 1s every 10 correct answers (minimum 1s)

### Custom (optional)

- Allow manual toggle configuration for players who want to mix and match settings outside the presets

## Feature 3: Audio Response Mode

Add a mode where the player's microphone is the only input method. The player must say the colour name out loud instead of clicking a button. Uses the Web Speech Recognition API to capture and evaluate spoken answers in real time.

### Considerations

- Browser support (Web Speech API is primarily Chrome/Edge)
- Microphone permission handling and clear UI feedback
- Tolerance for accent/pronunciation variation
- Visual feedback when speech is detected vs recognised
- Fallback or error messaging for unsupported browsers
- May need a short cooldown between rounds to avoid picking up residual audio
