
app:
  name: "StudyFolio"
  description: "Your personal AI study studio"
  platform: "Android"
  type: "AI-powered student learning app"

  theme:
    style: "Modern, minimalist, educational"
    primary_color: "#063D2D"
    secondary_color: "#A1E8CD"
    background_color: "#D5E8DF"
    card_color: "#082D23"
    text_color: "#FFFFFF"
    font: "Modern Sans Serif"
    border_radius: "16px"

  home_screen:
    header:
      logo: "StudyFolio icon"
      title: "StudyFolio"
      subtitle: "Your personal AI study studio"

    hero_section:
      image: "3D illustrated books, documents, and study materials"
      headline: "Master your coursework faster."
      description: >
        Turn PDFs, PowerPoint slides, documents,
        and lecture notes into an interactive AI study partner.

    features:
      - title: "Source-Grounded Q&A"
        description: >
          Ask questions and get clear explanations
          with inline citations.
        icon: "sparkles"

      - title: "Study Guides & Flashcards"
        description: >
          Auto-build structured revision briefs
          and interactive flip decks.
        icon: "book-open"

      - title: "Practice Exams"
        description: >
          Test your mastery with source-backed
          multiple-choice quizzes.
        icon: "clipboard-check"

      - title: "AI Audio Discussions"
        description: >
          Listen to two hosts break down
          your lessons aloud.
        icon: "audio-lines"

    authentication:
      provider: "Google"
      button_text: "Sign in with Google"
      button_color: "#91E5C5"

  core_features:
    document_upload:
      supported_formats:
        - PDF
        - PPT
        - PPTX
        - DOC
        - DOCX
        - TXT

    ai_assistant:
      capabilities:
        - Answer questions from uploaded sources
        - Summarize lessons
        - Explain difficult concepts
        - Generate study guides
        - Create flashcards
        - Generate practice exams
        - Create AI audio discussions

    study_tools:
      - AI Study Reviewer
      - Flashcard Generator
      - Practice Quiz Generator
      - Lesson Summarizer
      - AI Tutor
      - Audio Learning

  navigation:
    - Home
    - My Materials
    - Study Guides
    - Flashcards
    - Practice Exams
    - Profile

  design_requirements:
    - Mobile-first responsive layout
    - Dark green feature cards
    - Mint green accent colors
    - Clean typography
    - Smooth transitions
    - Simple navigation
    - User-friendly interface
