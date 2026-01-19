# Notion Images

Hosting for images used in Notion pages and Markdown documents.

## Convention

Directory structure: `images/YYYY-MM-DD_HHMM_page-name/`

Example:
```
images/
├── 2026-01-17_1652_routing-load-simulation-report/
│   ├── status-pie.png
│   ├── response-histogram.png
│   └── component-breakdown.png
└── 2026-01-18_0930_sprint-review-notes/
    └── diagram.png
```

## Usage in Notion

Use raw GitHub URLs:
```
https://raw.githubusercontent.com/karol-kuc/notion-images/master/images/YYYY-MM-DD_HHMM_page-name/image.png
```

Notion-flavored Markdown syntax:
```markdown
<image source="https://raw.githubusercontent.com/karol-kuc/notion-images/master/images/2026-01-17_1652_routing-load-simulation-report/status-pie.png">Chart caption</image>
```
