PI SOCIAL — starter prototype

WHAT'S INCLUDED
- Responsive mobile-first social feed
- Demo post creation and likes (stored locally in the browser)
- Discover/search sample member profiles
- Demo follow and community join controls
- Profile bio editor
- Pi SDK script and a basic Pi Browser sign-in starter

IMPORTANT LIMITATIONS
This is a front-end prototype, not a production social network. Demo posts/profile data are stored
only in the current browser/device. There is no shared database, secure account system, real-time
messaging, moderation dashboard, image upload, or backend Pi identity verification yet.
The Pi sign-in starter is for sandbox exploration only. Production Pi authentication must send
the access token to a secure backend for verification. Never expose your Pi Server API Key in
browser code. Pi payments are not enabled.

NEXT PRODUCTION STEPS
1. Deploy the public/ folder to HTTPS hosting to obtain a stable app URL.
2. Add a backend/database for accounts, posts, comments, follows, media and messages.
3. Implement server-side Pi user verification using the official Pi Platform API.
4. Add reporting, blocking, moderation, privacy policy and account deletion.
5. Test in Pi Sandbox, then configure production access in the Pi Developer Portal.
6. Submit the hosted URL in App Studio's Convert App form.

Pi developer docs:
https://developers.minepi.com/docs/build-first-app/GettingStarted
https://developers.minepi.com/docs/authenticate-user/Authentication
https://developers.minepi.com/docs/build-first-app/BuildAnApp

App Studio submission text suggestion:
Name: Pi Social
Description: Connect with Pioneers, share updates, discover communities and build meaningful connections in one friendly social space.
Language: English
Category: Social
