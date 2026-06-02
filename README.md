# ai-engineered-health-tracker-
My first programming project.
# Health Tracker

Live Web App Demo: https://clever-macaron-525560.netlify.app

# Technical Challenges and Solutions

1) Problem: Zero coding knowledge and failing AI tools
I did not know how to code, and there was no AI that could just build the app for me. Arena.ai constantly made mistakes. Because I did not know programming, I did not even know how to write a prompt to fix those mistakes. 
* **Solution:** I changed my strategy. Instead of trying to build the whole app at once, I built a barebones prototype first. Then I used ChatGPT to help me isolate and add features one by one, scaling the project slowly so the AI wouldn't break the codebase.

2) Problem: No background in medical metrics or user psychology
I wanted to build a health tracker that monitored the effects of things like tobacco, but I did not know the science behind how these substances affected health. I also had no idea what colors to use in the UI to make the app look right.
**Solution:** I did independent research on how tobacco and lifestyle habits affect health to build accurate tracking metrics. For the design, I researched color psychology to choose a color palette that felt clean and appropriate for a wellness app, rather than guessing.

3) Problem: App UI and performance failures
The app was laggy, and a major layout bug completely blocked scrolling, making the application unusable.
**Solution:** I debugged the UI by forcing the AI to strip out redundant styling until the layout fixed itself, resolving the scroll issue and optimization lag.

5) Problem: Deployment and distribution walls
Once the code worked locally on my computer, I had no idea how to actually put it on the internet or turn it into a mobile app.
**Solution:** I researched hosting tools and used Netlify to deploy the live web version. To make it a mobile and desktop app, I used PWA Builder to compile the web code into an Android .apk and a Windows build.


 Files in this Repository
* index.html, script.js, style.css: The core source code.
* app-release.apk: Standalone Android build. (Note: Since this is an independent build bypassing the Google Play Store, Android will show an unknown sources warning during installation).
* Windows Build: Executable files for desktop use.
