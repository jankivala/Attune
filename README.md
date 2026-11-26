# Adaptive Social Presence Chatbot

**README prose word count: 245**

## Status
A local browser prototype comparing low, moderate and high conversational social presence. Adaptive mode starts at moderate and switches to a restrained style when explicit frustration cues are detected. It displays the selected style and reason and allows manual override. A human-adviser handoff state is simulated only; no adviser is contacted. This is not a validated emotion-aware or production chatbot.

## Run and inspect
Open `index.html` in a modern browser. No installation, API key, server or external service is required.

## Technology
HTML, CSS and vanilla JavaScript. Keyword rules select fixed response templates. No LLM, trained classifier, persistent memory, external data, account integration or live human-support service is used.

## Try the interactions
1. In Adaptive mode, send “Can you explain how this service works?” to see the moderate default.
2. Send “I have asked three times and this is really frustrating.” to trigger the restrained style.
3. Change the style manually and compare fixed styles.
4. Select “Request a human adviser” to see the simulated handoff disclosure.
5. Reset the conversation to clear the visible state.

## Limitations
Keyword matching can miss indirect frustration or misread context. Replies are fixed templates. The handoff does not contact a person. Walkthroughs are not a user study and do not establish improved satisfaction or trust.

## Development record
- Translated the Assignment 1 research gap into low, moderate and high style conditions.
- Added adaptive keyword switching, visible reasons and manual override to make inference inspectable and reversible.
- Added a user-initiated simulated handoff; clearly disclosed that no live service is connected.
- Checked neutral, frustration, manual-override and handoff walkthroughs.
- Kept processing local and deterministic. Formal participant evaluation and live agent routing remain planned.

## AI assistance
ChatGPT assisted with code drafting, report wording and illustrative diagrams. The project owner checked the interaction scenarios and should verify source details, references, final code and repository commit before submission. The prototype itself does not call an AI model.

## Additional files
The project report and diagrams are provided in the accompanying submission ZIP. The public repository is https://github.com/jankivala/ToneChatbot. Add the exact submitted commit hash or release tag to the report and submission record.
