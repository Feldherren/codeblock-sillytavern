# codeblock-sillytavern
A custom 'programming' language JSON for use with Extended Code Highlight in Obsidian to highlight macros.
Eventually I want to graduate to writing a proper Obsidian plugin, so broken macros (typos, wrong brackets, or fewer/more curly braces than needed) can be highlighted, but for now Extended Code Highlight is a good stopgap measure.

# Usage
1. Install Extended Code Highlight to your Obsidian vault; it's available via Community Plugins.
2. (With Extended Code Highlight default settings) go to \.obsidian\plugins\extended-code-highlight inside your Obsidian vault and create a new folder 'languages'
3. Drop st-prompt.json into the new 'languages' folder
4. In Obsidian, with your vault open, open the command palette, enter 'Extended Code Highlight', and select 'Extended Code Highlight: Reload extended highlight languages'
5. At the start of multiline codeblocks, immediately after the trio of backticks, add 'st-script'; eg:

\`\`\`st-script
text goes here
\`\`\`
