# Project Orbit — Lab 8–9

A responsive single-page student portfolio concept that brings project showcases, sample assignment content, a data dashboard, an interactive website-control panel, a simulated shop, media controls, and privacy notes into one application.

## Run it

Open `index.html` in a modern browser, or publish the repository root with GitHub Pages. No build step or API key is required.

## Included interactions

- Navigate between integrated sections with the navigation, project buttons, or chatbot.
- Ask the local command router to change themes/background colors, open sections, explain the sample Assignment 5, search the sample catalog, modify the simulated cart, and control media.
- Optional browser speech recognition with visible status and a stop control. Speech recognition support and permissions vary by browser. Text and buttons remain available alternatives.
- Original synthesized music via Web Audio and an embedded CC0 flower video sample.
- Simulated shopping only; there is no payment collection or real checkout.

The assistant routes a bounded set of commands to JavaScript functions. It does not call a hosted generative AI model. Assignment content is representative placeholder material and should be replaced with the student's actual prior assignments and requirements. Dashboard values are illustrative.

## Customize the coursework

The repository does not yet include your previous assignment files or their exact requirements. Use [`ASSIGNMENTS.md`](ASSIGNMENTS.md) to record the real course work before replacing the sample cards and assignment explanation in `index.html`. Do not present the demo content as completed class assignments unless it matches your actual work.

## Test checklist

Use [`TESTING.md`](TESTING.md) to verify chatbot actions, responsive layout, simulated shopping, and optional voice/media behavior in your target browser.

## Privacy and limitations

Text commands are processed locally in the page. Browser speech-recognition services may process audio according to the browser vendor's terms. The site discloses this and does not request payment information. A browser may require a user gesture before media playback. Test voice and media in the target browsers before describing the experience as hands-free.

## Customize the demo

Update the project cards and `explainAssignment()` in `index.html` with actual class assignments and details. Update the local `catalog` array for demo products. The product catalog is sample data and has no seller or payment connection.
