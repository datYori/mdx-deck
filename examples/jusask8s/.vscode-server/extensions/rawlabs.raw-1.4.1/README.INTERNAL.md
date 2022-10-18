# RAW Labs VS Code extension INTERNAL README
1. Install NodeJS
2. Open the extension directory (raw/vs-code-extension) in raw repository with VS Code
3. Run `npm install` in extension directory.
4. In environment/environment.ts set the devUrl according to your local repose instance.
5. Set isProduction variable to false (this one at some point will become external argument).
6. Save the file
7. In Run & Debug file select Launch Extension and press play.
8. A new VS Code instance will occur with preinstalled the extension.
9. You can do your experiments there.