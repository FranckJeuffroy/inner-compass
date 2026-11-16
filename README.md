# Inner Compass workshop prototype

Open ../Inner-Compass.html directly in a modern browser, or serve dist/ with any static web server.

The nine original screenshots are the content basis. They contain eight motivation categories (rather than seven) and 49 named values plus blank Other Values entries. All categories are retained, with custom values supported. Reflection prompts and mission models are preserved in English.

Features: editable Life View and Work View answers and free writing; independent past/current 1–10 scores; automatic top-five rankings with stable source-order ties; High/Medium/Low sorting, unordered five-value selection followed by drag or keyboard/button ordering and automatic top-three highlighting; two editable purpose/mission models; consolidated workbook; text export and browser printing.

Guidance is rule-based. There is no AI service, no API key, and no AI interpretation. Mission statements concatenate the participant’s own entries. Responses are stored in browser localStorage and never uploaded. Browser storage may be unavailable for local files or in private browsing; export a backup. The optional Google Fonts stylesheet loads fonts only, without reflection data.

Validation: JavaScript syntax checked; all six screens rendered; ranking, ties, selection consistency and selection limits checked; reflection navigation, ratings, search and priority controls exercised in the browser.

Hosting: static site deployed on GitHub Pages.


Latest revision: guided reflection now ends with an optional additional-thoughts question and a dedicated writing step. Answers are compiled verbatim on first entry to an empty draft; existing drafts are preserved. Structured recap answers can be edited, and missing notes added explicitly. Work writing continues to Life View, then integration. Motivation rankings are hidden during rating and revealed on a review/takeaway screen. Past/current definitions and scoring guidance have been clarified. Integration starts with personal reflection and uses fixed optional follow-up prompts, without automated contradiction analysis. Purpose/mission includes examples and a rough-ideas space.

Dictation: optional browser SpeechRecognition, where supported. No microphone starts automatically. The start control explains that the browser may transmit audio to its speech service; text is editable. No speech recognition service is bundled. Live microphone access has not been tested. AI summarising, adaptive questioning and polishing remain unconnected and are labelled as unavailable.


Current revision: dictation and speech recognition have been removed from every screen. Both Work View and Life View now offer an explicit replacement button to collect all current prompt answers into the editable free-writing block. Existing text requires confirmation before replacement; Undo last replacement restores the prior draft. Adding only missing answers remains available.
