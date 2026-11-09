# Project Orbit smoke-test checklist

Run these checks in the browsers/devices you intend to support. Speech recognition and media playback vary by browser, permissions, and user-gesture requirements. A passing desktop test does not establish that the site is fully hands-free or accessible to every user.

## Navigation and appearance

- [ ] Use the header links and project-card buttons to navigate to their sections.
- [ ] Ask the chatbot to open the dashboard, assignments/projects, shop, media, privacy section, and homepage.
- [ ] Ask for dark mode, light mode, blue background, and the beach-inspired background. Confirm that each changes the page; verify the beach option is a color theme, not a photograph.
- [ ] Reload and check that the most recent theme is restored where local storage is available.
- [ ] Test a narrow mobile viewport and keyboard focus visibility.

## Assistant and assignments

- [ ] Send a supported command and confirm both the page action and confirmation message.
- [ ] Ask “Explain Assignment 5” and ensure the answer is understood to be sample content until replaced with actual course requirements.
- [ ] Try an unsupported command and confirm the assistant offers supported examples rather than claiming success.
- [ ] Verify chatbot actions also work with the visible buttons and text input.

## Shopping

- [ ] Search for a wireless keyboard and confirm matching catalog results are shown.
- [ ] Add the second catalog product to the cart by chatbot command; verify count, item, and total.
- [ ] Remove a cart item and verify the total updates.
- [ ] Use simulated checkout and confirm no payment information or real purchase is requested.

## Media and voice

- [ ] Start and stop generated music after a user gesture; check the status text.
- [ ] Play, pause, resume, and stop the embedded video. Confirm the public-domain sample can load in the target network/browser.
- [ ] If speech recognition is supported, grant microphone permission, speak a navigation/theme/shop/media command, verify the recognized-command feedback, then stop listening.
- [ ] Deny microphone access or test an unsupported browser; ensure text and visible controls remain usable.
- [ ] Do not claim completely hands-free operation unless all essential tasks have been tested without mouse/keyboard interaction, including initial browser permission and playback enablement.
