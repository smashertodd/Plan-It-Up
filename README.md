# Assessment Planner --- Hybrid v1.3

A single-file, browser-based assessment planner that helps students
break down assignments into manageable, time-sliced stages --- without
the stress.

Built with accessibility, neurodivergent-friendly design, and
pedagogical scaffolding at its core.

------------------------------------------------------------------------

## ✨ Features

### 🎯 Core Planning

-   **5 assessment types** --- Essay, Literature Review, Report, Poster,
    Presentation
-   **Weighted scheduling engine** --- distributes stages across your
    available study days, giving heavier stages (drafting, writing) more
    time
-   **3 scaffolding modes** --- Essentials (minimal), Guided
    (recommended), Coach (academic depth)
-   **Learning Outcome parser** --- paste LOs in any format;
    auto-detects Bloom's taxonomy verbs and maps them to relevant stages
-   **Reflow from today** --- fallen behind? One click reschedules
    remaining work across your remaining study days

### 👤 Quick-Start Profiles

One-click setup for different student needs:

  -----------------------------------------------------------------------
  Profile                             What it sets
  ----------------------------------- -----------------------------------
  🌱 **New to uni**                   Guided mode, all tips on, plain
                                      English

  🔄 **Returning student**            Writing and referencing focus

  🎓 **Postgrad**                     Coach mode, research and
                                      self-review

  🧠 **ND-friendly**                  Dyslexia spacing, structure,
                                      wellbeing check-ins

  ⚡ **Just the basics**              Essentials mode, no extras
  -----------------------------------------------------------------------

### 💡 Tip Categories

Students choose what help they want --- each injects relevant tasks into
the plan:

-   ✍️ Writing tips
-   🔍 Research tips
-   ⏱️ Time management (Pomodoro prompts)
-   📖 Referencing reminders
-   🔎 Self-review prompts
-   💚 Wellbeing check-ins
-   🤖 AI use guidance

### 🎨 Colour Palette Themes

8 one-click visual themes: Default, Ocean, Forest, Sunset, Lavender,
Slate, Night Owl, and High Contrast. Plus advanced custom colour pickers
and typography controls.

### ♿ Accessibility

-   Skip-to-content link and full keyboard navigation
-   ARIA roles, labels, and live regions
-   `prefers-reduced-motion` support
-   Neurodivergent-friendly mode (shorter sentences, visual anchors,
    reduced density)
-   Dyslexia-friendly spacing
-   Plain English mode
-   High contrast theme
-   Print-optimised stylesheet

### 📤 Export and Sharing

-   **ICS calendar export** --- import into Google Calendar, Outlook,
    Apple Calendar
-   **Shareable link** --- encodes plan config as a URL
-   **Print** --- clean print layout with all tasks expanded
-   **localStorage persistence** --- plan survives page refresh

------------------------------------------------------------------------

## 🚀 Getting Started

### Option A: Just open it

1.  Download `index.html`
2.  Double-click to open in any modern browser
3.  Done --- no server, no install, no dependencies

### Option B: GitHub Pages (live URL)

1.  Fork this repository
2.  Go to **Settings → Pages → Source: main branch**
3.  Your planner is live at
    `https://yourusername.github.io/assessment-planner/`

### Option C: LMS embed

Upload `index.html` to your Canvas/Moodle/Blackboard course as a file
resource.

------------------------------------------------------------------------

## 📖 How to Use

### For Students

1.  **Pick a profile** --- choose the one that sounds most like you
2.  **Set your assessment details** --- title, type, dates
3.  **Choose your help** --- tick the tip categories you want
4.  **Pick a theme** --- choose colours that work for you
5.  **Paste Learning Outcomes** (optional) --- mapped to plan stages
    automatically
6.  **Click "Create my plan"** --- your personalised schedule appears
7.  **Work through tasks** --- tick them off; progress bars update
    automatically
8.  **Fallen behind?** --- click "Reflow from today" to reschedule

### For Staff

1.  **Set up a template plan** --- fill in title, type, dates, LOs, and
    mode
2.  **Click "Copy share link"** --- encodes your setup as a URL
3.  **Share the link with students** --- they click, setup pre-fills,
    they create their plan
4.  Students can still customise profile, tips, and theme to suit their
    needs

------------------------------------------------------------------------

## 🛠️ Technical Details

  Detail                 Value
  ---------------------- ------------------------------------
  **Architecture**       Single self-contained HTML file
  **Dependencies**       None --- zero external libraries
  **Framework**          Vanilla HTML, CSS, JavaScript
  **Storage**            Browser localStorage
  **Browser support**    All modern browsers
  **File size**          \~30 KB
  **Hosting required**   No --- works from local filesystem

------------------------------------------------------------------------

## 📁 Repository Structure

    assessment-planner/
    ├── index.html          # The complete application
    ├── README.md           # This file
    └── LICENSE             # MIT License

------------------------------------------------------------------------

## 🗺️ Roadmap

-   [ ] Faculty-specific tip bundles and checklists
-   [ ] Drag-and-drop stage reordering
-   [ ] Multiple concurrent plans
-   [ ] JSON export/import for full plan backup
-   [ ] Collaborative mode (shared progress via URL)
-   [ ] Integration with institutional calendars

------------------------------------------------------------------------

## 🤝 Contributing

Contributions are welcome!

1.  Fork the repository
2.  Create a feature branch (`git checkout -b feature/your-idea`)
3.  Make your changes
4.  Test locally by opening `index.html` in a browser
5.  Submit a pull request with a clear description

### Reporting Issues

Use the Issues tab to report bugs or suggest features. Please include: -
What you expected to happen - What actually happened - Your browser and
operating system

------------------------------------------------------------------------

## 📄 License

This project is licensed under the MIT License. You are free to use,
modify, and distribute this tool for any purpose.

------------------------------------------------------------------------

## 🙏 Acknowledgements

-   Bloom's taxonomy verb mapping adapted from Anderson and Krathwohl
    (2001)
-   Accessibility patterns informed by the GOV.UK Design System
-   Neurodivergent-friendly design principles informed by current
    inclusive education research

------------------------------------------------------------------------

**Built with ❤️ for students who want to plan without the panic.**
