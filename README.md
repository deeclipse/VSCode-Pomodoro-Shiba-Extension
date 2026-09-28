# VSCode-Pomodoro-Shiba-Extension

Hey, this is a small VS Code extension that shows a friendly Shiba Inu picture in the Explorer view and provides a tiny built-in countdown (pomodoro-style), Claude AI-assisted with the implementation of the image function, and Copilot with the automated README. Next, I plan to add more features.

<img width="519" height="614" alt="image" src="https://github.com/user-attachments/assets/e98f2d55-33ad-4b9f-9218-451f7284f921" />

Key behaviors:
- Adds a webview contribution under the Explorer sidebar named "Shiba Doggo" that displays media/picture.png.
- Pomodoro Timer to track your Work

Contributing
- Contributions are welcome. Please open issues and submit pull requests.
- If present, follow the repository's `CONTRIBUTING.md` (add one if you plan to accept contributions).

Maintainers
- Maintainer and contact information is not currently set in `package.json`. Add the `author` and `repository` fields to `package.json` to make maintainers visible.

Notes and next steps
- Activation: the extension currently has no activationEvents configured in `package.json`. Consider adding activation events (e.g., onView:Shibba.view or onCommand:shiba-inu-pet.helloWorld) to control activation behavior.
- Improve accessibility: add alt text for images and keyboard support for UI controls in the webview.
- If you want CI badges (build, marketplace version, license), add a repository, CI config, and a LICENSE file so badges can be generated.

References
- VS Code Extension docs: https://code.visualstudio.com/api
- https://github.com/microsoft/vscode-extension-samples/tree/main/webview-view-sample

--
Happy hacking! Contributions or suggestions are welcome via issues or pull requests.
