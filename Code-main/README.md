In multilingual environments classrooms, research labs, field interviews experts often record spoken notes in their native tongue. Converting those rich audio logs into concise summaries in both the original language and English enables faster review, wider sharing, and easier integration with downstream NLP pipelines. 

Our Audio Summarizer & Translator GUI provides a one-click desktop interface to:
1. Transcribe: Leverage OpenAI Whisper to convert speech (Hindi, English, or any
supported Indian language) into UTF-8 text.
2. Summarize: Use a BART-based model fine-tuned on IIITH Hindi Dataset Corpus to
generate succinct Hindi summaries.
3. Translate: Run those Hindi summaries through a custom GRU-Seq2Seq translator
fine tuned on IITB Hindi to English Data Corpus, producing fluent English
equivalents.
4. Interact: Offer intuitive buttons (“Generate Summary” / “Generate Summary in
English”) and scrolling text boxes within a lightweight Tkinter GUI.

This modular pipeline supports easy extension to additional languages and models, and
bridges the gap between local audio capture and multilingual text understanding.
