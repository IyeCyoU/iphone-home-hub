SHAKIR HOME HUB v9 — ATHAN INITIALIZATION FIX

Fix:
The previous test could say "Athan audio is not ready" because the JavaScript initialized
the audio player before the HTML audio elements had finished loading.

v9 initializes the audio after the page is fully loaded and also re-checks the player
when Enable Athan or Test Athan is selected.

TEST
1. Replace the current GitHub index.html with this one.
2. Commit and wait briefly for GitHub Pages to update.
3. Refresh Home Hub on the iPhone 5s.
4. Turn media volume up.
5. TOOLS > 4 = Enable Athan.
6. TOOLS > 6 = Test Athan Now.

If Safari blocks the first autoplay attempt, tap Enable Athan once and then Test Athan again.
