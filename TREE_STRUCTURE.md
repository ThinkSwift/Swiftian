# Swiftian Repository Tree Structure
# 기술적 디렉토리 구조

## Complete Directory Tree

```
Swiftian/
├── .git/                          # Git version control
├── .github/
│   └── workflows/
│       └── jekyll.yml             # GitHub Actions CI/CD
├── .gitignore                     # Git ignore rules
├── 404.html                       # 404 error page
├── Gemfile                        # Ruby dependencies
├── Gemfile.lock                   # Locked dependency versions
├── _config.yml                    # Jekyll configuration
├── _data/                         # Site data files
│   ├── languageLabels.yml         # Language labels
│   ├── media.yml                  # Media metadata
│   ├── navigation.yml             # Multi-language navigation
│   └── pages/                     # Page data by language
│       ├── ar.yml ├── cs.yml ├── da.yml ├── de.yml
│       ├── el.yml ├── en.yml ├── es.yml ├── fi.yml
│       ├── fr.yml ├── hu.yml ├── id.yml ├── it.yml
│       ├── ja.yml ├── ko.yml ├── nb.yml ├── nl.yml
│       ├── pl.yml ├── pt.yml ├── ro.yml ├── ru.yml
│       ├── sk.yml ├── sv.yml ├── tr.yml ├── uk.yml
│       ├── zh-hans.yml └── zh-hant.yml
├── _includes/                     # Reusable components
│   ├── footer.html
│   ├── locale.liquid
│   ├── media.html
│   └── video.html
├── _languages/                    # Multi-language content
│   ├── ar/     ├── cs/     ├── da/     ├── de/
│   ├── el/     ├── es/     ├── fi/     ├── fr/
│   ├── hu/     ├── id/     ├── it/     ├── ja/
│   ├── ko/     ├── nb/     ├── nl/     ├── no/
│   ├── pl/     ├── pt/     ├── ro/     ├── ru/
│   ├── sk/     ├── sv/     ├── tr/     ├── uk/
│   ├── vi/     ├── zh-hans/ └── zh-hant/
│   │
│   └── [Each language directory contains:]
│       ├── index.md               # Home page
│       ├── coding/
│       │   └── index.md           # Coding section
│       ├── creators/
│       │   └── index.md           # Creators section
│       ├── footer/
│       │   └── privacy.md         # Privacy policy
│       ├── groove/
│       │   └── index.md           # Groove section
│       └── universe/
│           └── index.md           # Universe section
├── _layouts/                      # Page templates
│   └── default.html               # Default layout
├── assets/                        # Static assets
│   ├── audios/
│   │   └── readme.md
│   ├── images/
│   │   ├── coding_panic.gif
│   │   ├── iFlipbook.gif
│   │   ├── swiftian_groove.gif
│   │   ├── swiftian_logo_1024.png
│   │   ├── swiftian_logo_180.png
│   │   ├── titan_color_800.jpg
│   │   ├── titan_sketch.gif
│   │   └── readme.md
│   └── videos/
│       ├── logo.mp4
│       ├── swiftian_groove_720.mp4
│       └── readme.md
├── coding/
│   └── index.md                   # Coding main page (English)
├── creators/
│   └── index.md                   # Creators main page (English)
├── docs/
│   └── CNAME                      # Custom domain configuration
├── favicon.ico                    # Favicon
├── favicon.png                    # PNG favicon
├── footer/
│   └── privacy.md                 # Privacy policy (English)
├── googlef020d35b429ecf1b.html   # Google site verification
├── groove/
│   └── index.md                   # Groove main page (English)
├── index.md                       # Home page (English)
├── py_scripts/                    # Python automation scripts
│   └── frontmatter/               # Front matter generation
│       ├── ar.yaml    ├── cs.yaml    ├── da.yaml
│       ├── de.yaml    ├── el.yaml    ├── en.yaml
│       ├── es.yaml    ├── fi.yaml    ├── fr.yaml
│       ├── hu.yaml    ├── id.yaml    ├── it.yaml
│       ├── ja.yaml    ├── ko.yaml    ├── nb.yaml
│       ├── nl.yaml    ├── pl.yaml    ├── pt.yaml
│       ├── ro.yaml    ├── ru.yaml    ├── sk.yaml
│       ├── sv.yaml    ├── tr.yaml    ├── uk.yaml
│       ├── zh-hans.yaml └── zh-hant.yaml
├── robots.txt                     # Search engine crawling rules
├── sitemap.xml                    # Site map for SEO
└── universe/
    └── index.md                   # Universe main page (English)
```

## File Count by Category

```
Configuration Files:    5
Jekyll Structure:      30+
Language Content:     135+
Assets (Media):        10+
Automation Scripts:    27
SEO/Deployment:         6
Total Files:          166
Total Directories:    193
```

## Language Support Matrix

```
Supported Languages (27):
┌─────────────┬─────────────┬─────────────┬─────────────┐
│ ar (Arabic) │ cs (Czech)  │ da (Danish) │ de (German) │
│ el (Greek)  │ en (English)│ es (Spanish)│ fi (Finnish)│
│ fr (French) │ hu (Hungarian)│ id (Indonesian)│ it (Italian)│
│ ja (Japanese)│ ko (Korean) │ nb (Norwegian)│ nl (Dutch)  │
│ pl (Polish) │ pt (Portuguese)│ ro (Romanian)│ ru (Russian)│
│ sk (Slovak) │ sv (Swedish)│ tr (Turkish)│ uk (Ukrainian)│
│ vi (Vietnamese)│ zh-hans    │ zh-hant     │             │
│             │ (Simplified)│ (Traditional)│             │
└─────────────┴─────────────┴─────────────┴─────────────┘
```

## Content Architecture

```
Main Sections:
├── 🧑‍💻 coding/     → Swift programming tutorials and projects
├── 🌌 universe/    → Community and ecosystem building
├── 🎵 groove/      → Rhythm-based productivity tools
└── 👨‍🎨 creators/   → Creator resources and showcase

For each section:
├── English version (root level)
└── 27 translated versions (_languages/)
```

## Technical Details

- **Framework**: Jekyll (Ruby-based static site generator)
- **Hosting**: GitHub Pages
- **CI/CD**: GitHub Actions
- **Domain**: Custom domain via CNAME
- **SEO**: Sitemap, robots.txt, meta tags
- **Automation**: Python scripts for frontmatter generation
- **Assets**: Video, images, future audio support