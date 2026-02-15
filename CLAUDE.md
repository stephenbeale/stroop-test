# Stroop Test Project

A web-based implementation of the Stroop effect cognitive test with multilingual support and various game modes.

## Session Notes

### 2026-02-15 - Roadmap Updates and Feature Planning

**Work Completed:**
- Updated ROADMAP.md with completed features (start time slider marked as DONE)
- Documented language selection as partially complete
- Committed changes on feature/6-language-selection branch

**Features Added to Roadmap:**
- Color improvements: Use brown instead of cyan, pink over purple, remove purple
- UI enhancement: Multi-column answer button layout (3x3 grid for 9 colours on wide screens)
- Time slider visibility: Make slider color more prominent
- Voice mode: Ignore invalid answers with warning message
- Custom mode: Fix toggle logic when voice mode is active

**Bug Reports Documented:**
- Spanish voice input stops after first correct answer
- Welsh voice input not working (may lack speech-to-text engine support)
- Desktop browser voice input issues (works on mobile but not desktop)

**Next Steps:**
- Continue work on language selection feature
- Address voice input bugs across different languages
- Implement UI improvements for better wide-screen support
- Investigate speech-to-text engine availability for Welsh

**Technical Notes:**
- Voice mode requires careful language-specific testing
- Need to verify speech-to-text engine support for each language
- Multi-column layout should maintain mobile responsiveness
