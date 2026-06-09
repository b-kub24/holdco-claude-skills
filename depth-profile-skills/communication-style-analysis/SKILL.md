# Communication Style Analysis

**Package:** Depth Profile Skills  
**Version:** 1.0.0  
**Author:** HoldCo Labs

## Description

Analyzes an individual's communication style from writing samples, conversation patterns, or self-reported preferences. Identifies patterns in tone, structure, persuasion approach, listening style, and feedback preferences. Produces actionable communication coaching.

## Trigger Phrases

- "Analyze my communication style"
- "How do I communicate"
- "Communication assessment"
- "Help me understand my communication patterns"
- "What's my communication style"

## Instructions

1. **Data Collection (one or more methods):**
   - Analyze provided writing samples (emails, messages, documents)
   - Conduct a conversational interview about communication preferences
   - Review described scenarios and communication outcomes

2. **Analyze Dimensions:**
   - **Directness:** Direct â Indirect (gets to the point vs builds context first)
   - **Formality:** Formal â Casual (structured vs conversational)
   - **Detail orientation:** Big picture â Detail-focused
   - **Emotional expression:** Reserved â Expressive
   - **Persuasion style:** Logic-led â Relationship-led â Data-led â Story-led
   - **Listening style:** Analytical â Empathetic â Action-oriented
   - **Feedback style:** Direct critique â Sandwich method â Avoidant
   - **Conflict approach:** Confrontational â Collaborative â Avoidant

3. **Produce Communication Profile:**
   - Primary communication style label and description
   - Strengths in communication (what lands well)
   - Blind spots (what might be misinterpreted)
   - Best channels (written vs verbal, sync vs async)
   - How to adapt for different audiences (executives, peers, reports, clients)

4. **Coaching Recommendations:**
   - 3 specific, actionable improvements
   - Scripts or templates for common scenarios
   - Practice exercises

## Configuration Options

```yaml
analysis_source: "interview"    # interview, writing_samples, both
depth: "standard"               # quick, standard, deep
include_coaching: true
professional_context: true      # Focus on workplace communication
```

## Example Prompts

> "Analyze my communication style. Here are 5 recent emails I've sent."

> "I keep getting feedback that I'm too blunt in meetings. Can you assess my communication style and help me adapt?"

> "What's my communication style? Ask me questions about how I communicate at work."

## Edge Cases

- **Non-native speakers:** Separate language proficiency from communication style
- **Code-switching:** Acknowledge different styles for different contexts as a strength
- **Written vs verbal mismatch:** Note the gap and explore why
