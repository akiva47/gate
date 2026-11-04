# השער

A one-button web app that opens the parking gate.

The button calls the gate link (a call2all `RunTzintuk` URL) and shows
"השער נפתח בהצלחה" only when the answer is OK (`responseStatus: "OK"`, or the
plain text `OK`); any other answer, a network error or a 30-second timeout
shows "נראה שמשהו השתבש הפעם".

**The gate link is not in this repository.** Whoever has it can open the
gate, and this repository is public. The app asks for the link on first use
and keeps it only in that phone's browser storage (the ⚙️ button changes it).

Hosted with GitHub Pages: Settings → Pages → Deploy from a branch → `main`,
`/ (root)`. Add it to the home screen from Safari's Share menu.
