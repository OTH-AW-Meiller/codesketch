# codesketch

Codesketch is a tool that adds live preview capabilities to the Moodle CodeRunner plugin, specifically designed for web-based programming exams. It enables students to interactively test their HTML, CSS, and JavaScript code in real-time, while still preserving the automated server-side evaluation provided by CodeRunner. This improves the overall exam experience by offering immediate feedback, enhancing grading transparency, and allowing students to debug their code more effectively.

## Features
- **Live Preview:** Students can see the results of their HTML, CSS, and JavaScript code instantly in an embedded preview window.
- **Interactive Testing:** Allows students to test their code interactively during exams without affecting the server-side evaluation.
- **Seamless Integration:** Works alongside Moodle CodeRunner, ensuring compatibility with existing workflows.

## Installation
1. Copy the code from `codesketch.html` into the **Global extra** field in the Moodle CodeRunner plugin settings.
2. Ensure that the required permissions are set for students to use the live preview feature during exams.

## Usage
- Students can write their HTML, CSS, and JavaScript code in the provided text areas.
- The live preview updates automatically as they type, showing the combined output of their code.
- Errors in the code are handled gracefully to avoid disrupting the exam experience.

## Simple Version
For simpler use cases, a version of Codesketch with only basic textareas (no advanced editors) is available in `codesketch_textarea.html`. This version is ideal for minimal setups or when advanced features like syntax highlighting are not needed.

## Preview
You can see a quick demonstration of Codesketch in action [here](https://oth-aw-meiller.github.io/codesketch/test.html).

## Credits
Codesketch is based on the idea of [Tommy Hodgins](https://github.com/tomhodgins) and his project [LiveEditor](https://github.com/tomhodgins/liveeditor). We thank him for his work and inspiration, which made this project possible.


