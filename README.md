# OpenAI-like Markdown Rendering Style

Use this CSS to give rendered Markdown a clean, readable look similar to OpenAI’s typography.

```css
.markdown-body {
  font-family: "Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  line-height: 1.62;
  max-width: 700px;
  margin: 0 auto;
  color: #111827;
  font-size: 16px;
}

.markdown-body p {
  margin: 0 0 1.3em;
}

.markdown-body h1,
.markdown-body h2,
.markdown-body h3,
.markdown-body h4,
.markdown-body h5,
.markdown-body h6 {
  letter-spacing: 0.01em;
  line-height: 1.25;
  margin: 1.5em 0 0.6em;
}
```

## Notes

- **Line height** is set to `1.62` (inside your `1.6–1.65` target).
- **Content width** is capped at `700px`.
- **Heading letter-spacing** is slightly increased with `0.01em`.
- **Paragraph spacing** is `1.3em` (inside your `1.2–1.4em` target).

If you want, I can also add a full theme with code blocks, blockquotes, tables, and dark mode.
