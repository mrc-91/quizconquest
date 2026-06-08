# Privacy Policy for QuizConquest

**Effective date:** 2026-06-08
**Developer:** Lost Frogs ("we", "us", "our")
**Contact:** lostfrogs2026@gmail.com
**App:** QuizConquest (Android package: `com.lostfrogs.quizconquest`)

This Privacy Policy describes how QuizConquest handles information when you install and play the game on Android. By installing or using the game you agree to the terms below.

---

## 1. Information we collect

QuizConquest is designed to collect as little personal information as possible. The only data the app processes is what is strictly necessary for gameplay.

### 1.1 Information you enter

- **Display name.** When you set up a match you enter a nickname. This name is stored only on your device and, during an online match, transmitted to the other player and to Unity's matchmaking service so it can appear in the opponent's UI. We do not require this to be your real name.
- **Avatar selection.** You choose an avatar icon from a built-in list. The selected index (a number) is shared with the other player during an online match.

We do **not** collect: email address, phone number, real name, age, gender, location, contacts, photos, files, or any other personal identifier.

### 1.2 Anonymous Unity player ID

The first time you launch the game with an internet connection, **Unity Gaming Services** (Unity Technologies) creates an **anonymous player ID** for your install. This ID is a random identifier — it is not linked to your name, email, phone number, or device identity, and we are not given any way to trace it back to you. The same ID is reused on each launch on that install; uninstalling the app or clearing its data discards it and a future install would receive a new one.

This anonymous ID is what allows the competitive leaderboard (section 1.4) and online matchmaking (section 1.3) to work. It is created at launch even if you only ever play single-player or hot-seat modes. Unity's handling of it is governed by Unity's privacy policy: https://unity.com/legal/privacy-policy.

### 1.3 Information collected during online matches

When you play an online (multiplayer) match, the following technical data is processed by **Unity Gaming Services** so that two devices can find and talk to each other:

- The **IP address** of your device, used to route gameplay traffic through Unity Relay servers. Unity does not expose your IP to the other player.
- **Lobby and match metadata** (lobby ID, join code, host/client role, the display name and avatar index you entered for the current match). This is deleted shortly after the match ends.

We do not operate our own servers. The above is handled by Unity.

### 1.4 Competitive leaderboard (online ranked matches)

The game includes an optional competitive rank ladder. When you finish an **online** match, your updated skill rating (an ELO number) is stored on Unity's Leaderboards service against your anonymous player ID, together with the **display name** you chose for the match. Unlike the lobby/relay data above, this leaderboard entry **persists** so the ladder can show standings over time.

- Your display name on the leaderboard is **visible to other players** who view the ladder. Because of this, please do not enter your real name or any personal information as your display name — use a nickname.
- Only your rating and display name are stored. No quiz answers, contacts, location, or other personal data are sent.
- Single-player, hot-seat, and Daily Challenge results are **not** submitted to the leaderboard; they stay on your device.

This data is stored by Unity Gaming Services (Leaderboards and Cloud Code), governed by Unity's privacy policy linked above. We do not operate our own servers and keep no separate copy.

### 1.5 Local data

Match settings (volume, last-used avatar, tutorial-hint flags) and your local progress (Knowledge Rank, match history) are stored on your device via Android's local app storage (`PlayerPrefs` and local files). This data never leaves your device. Uninstalling the app removes it.

### 1.6 We do **not** use

- Third-party advertising SDKs.
- Third-party analytics SDKs.
- Crash-reporting services.
- Social-network sign-in.
- In-app purchases.
- Push notifications.

---

## 2. How we use the information

The data above is used only to:

1. Run a multiplayer match between two players (matchmaking + peer-to-peer relay).
2. Display each player's chosen name and avatar inside the game.
3. Maintain the competitive rank ladder (your skill rating and the standings shown on the leaderboard) for online matches.
4. Save your local preferences and progress so the app behaves the same the next time you open it.

We do not sell, rent, or trade your information. We do not use it for advertising or profiling.

---

## 3. Permissions the app requests

| Permission | Reason |
|------------|--------|
| `INTERNET` | Required to play online matches via Unity Relay/Lobby. The app does not transmit any data while playing single-player or hot-seat. |
| `VIBRATE` | Used for short haptic feedback when answering questions and during battles. |

The app does not request access to contacts, storage, microphone, camera, location, or any other sensitive permission.

---

## 4. Data retention

- **On your device:** local preferences and progress persist until you uninstall the app or clear its data.
- **Unity Lobby data:** automatically expires shortly after a match ends (Unity deletes inactive lobbies within minutes).
- **Unity Relay session data:** discarded by Unity when the match disconnects.
- **Competitive leaderboard entry:** your rating and display name persist on Unity's Leaderboards service until you request deletion of your anonymous Unity account (see section 6) or Unity removes the data.

We do not keep any database of players on our own systems; the leaderboard is hosted by Unity Gaming Services.

---

## 5. Children's privacy

QuizConquest is a quiz game and does not knowingly collect personal data from children under 13 (or the equivalent minimum age in your jurisdiction). If you are a parent or guardian and believe your child has provided us with personal data, please contact us at the email above and we will delete any such information.

---

## 6. Your rights

Because we do not store personal data on our own systems, there is generally nothing for us to delete on request. You can:

- **Reset local data:** Settings → Apps → QuizConquest → Clear data, or uninstall the app.
- **Stop online data sharing:** play only the single-player, hot-seat, or Daily Challenge modes — these never contact the leaderboard or matchmaking services.
- **Request information about, or deletion of, Unity-held data** (including your anonymous player ID and your competitive leaderboard entry): see Unity's privacy policy linked above for instructions, or email us at lostfrogs2026@gmail.com and we will help you make the request to Unity.

If you have any other request, email us at lostfrogs2026@gmail.com.

---

## 7. Security

Online traffic between players is relayed through Unity's servers and uses Unity's transport-level security. No game data is sent in cleartext over the public internet (`android:usesCleartextTraffic="false"`).

---

## 8. Third-party services

The only third-party data processor used by the app is:

- **Unity Gaming Services** (Unity Technologies) — anonymous authentication, Lobby, Relay, Leaderboards, and Cloud Code (the server logic that computes competitive ratings). https://unity.com/legal/privacy-policy

---

## 9. Changes to this policy

If we change this policy we will update the "Effective date" above and, where the change is significant, prompt you the next time the app starts. Continued use after a change means you accept the updated policy.

---

## 10. Contact

Questions or requests about this policy:

**Lost Frogs**
Email: lostfrogs2026@gmail.com
