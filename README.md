cat <<EOF > ~/.config/zusqii-startpage/README.md
# 🌑 zusqii-startpage

A minimalist, high-performance glassmorphic startpage. Designed for Zen Browser and optimized for Hyprland/Linux rices.

## 🛠 Features
- **Modular Architecture:** Organized CSS structure.
- **Performance-First:** Localized fonts (Noto Sans).
- **Ghost Search:** Invisible search bar that autofocuses on load.
- **Dynamic Clock:** 24h format with tabular-numeric alignment.

## 📂 Project Structure
\`\`\`text
zusqii-startpage/
├── index.html         # Core structure & JS logic
├── css/
│   ├── main.css       # Master import hub
│   ├── glass.css      # Frosted glass & layout
│   ├── typography.css # Font mappings
│   └── components.css # Pills, search, & headers
└── fonts/             # Cleaned Noto Sans (Thin, Regular, Black)
\`\`\`

## 🚀 Installation

1. **Clone the repository:**
   \`\`\`bash
   git clone https://github.com/zusqii/zusqii-startpage.git ~/.config/zusqii-startpage
   \`\`\`

2. **Set as Homepage in Zen Browser:**
   Set the URL to: \`file:///home/zusqii/.config/zusqii-startpage/index.html\`

## 🤝 Credits
Created by [Zusqii](https://github.com/zusqii)
EOF
