# Release Files

- `ChatGPTAssistantPanel-portable-lite.zip`: Windows portable package (recommended).

## Usage

1. Download `ChatGPTAssistantPanel-portable-lite.zip`
2. Extract the whole zip to a folder
3. Run `ChatGPTAssistantPanel.exe` inside extracted folder

## Notes for Lite Package

- `portable-lite` does **not** bundle Playwright browser binaries to keep file size small.
- If browser launch fails, either:
  - use local Chrome fallback in the panel/script settings, or
  - run Playwright browser install on that machine (`playwright install chromium`) before use.

Do not run a single copied `ChatGPTAssistantPanel.exe` without `_internal`, or you will get:
`Failed to load Python DLL ...\_internal\python313.dll`.
