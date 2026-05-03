# 🔗 NEXUS · Encrypted Realtime Messenger

> *A cyberpunk communication hub with end-to-end encryption, ranks, achievements, voice/video calls, and a fully animated UI.*

NEXUS is a feature‑rich, real‑time chat application built with **Firebase** and **WebRTC**. Every message is encrypted, and the interface adapts with themes, background effects, interactive messages, user ranks, and a full owner portal.

---

## ✨ Core Features

| Area            | Features                                                                                                                                                                                                                                 |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Messaging**   | Text, image, file, voice‑note & reply threads — reactions, read receipts, inline previews, message editing, deletion, and infinite scroll with “Load older”.                                                                            |
| **Chats**       | Direct Messages (DM) + Group creation with invites — live typing indicators, online/offline status with idle/dnd presets, per‑chat background images, and “clear for me”.                                                                |
| **Calls**       | WebRTC audio, video & screen‑share calls — camera flip on mobile, mute/unmute, call timer, and Firestore signaling (works even behind restrictive NATs).                                                                                |
| **Users**       | Custom username + emoji/upload profile picture, profile banner (preset or custom image), bio, message‑based ranking (50 → 10k+ → 🌈 rainbow), and user fonts for display names.                                                          |
| **Ranks & Roles** | Message count drives colored ranks (grey → vivid → rainbow).<br> Special roles: **OG**, **Tester**, **Bug Finder**, **Feedback**, **Owner**, and the secret **🐣 Easter Egg** role (unlock via the hidden cannon game).               |
| **Achievements**| 20+ achievements (First Message, Tic‑Tac‑Toe Master, Night Owl, Egg Hunter, etc.) — each grants bonus message counts. Retroactive unlock scanning works on existing accounts.                                                           |
| **Owner Portal** | Only the account `owner` can access: manage all users, assign roles, reset passwords, wipe all chats, send global announcements, reply to help tickets, impersonate any user, and view live changelog from GitHub deployments.          |
| **UI / Themes** | 6 neon themes (NEXUS, Nebula, Matrix, Amber, Crimson, Arctic) + 12 dynamic background effects (stars, aurora, lightning, portal, sakura, neon‑grid, etc.) + per‑user chat background images. Mobile sidebar slides in/out.              |
| **Modals**      | Users list, Inbox (accept/decline invites), Group creation, Settings (profile, emoji picker, font picker, banner picker, background effect picker), Credits, Help, Feedback (star rating), and Achievements.                              |
| **Security**    | Email/password authentication (username@nexus.local), Firestore security rules (to be implemented server‑side), and end‑to‑end encryption indicated on the registration screen.                                                          |
| **Fun extras**  | Built‑in Tic‑Tac‑Toe game (challenge friends inside a DM), voice recording with waveform animation, file/image sharing with previews & download, and a **Easter Egg cannon game** to unlock the secret role.                             |

---

## 🖥️ Tech Stack

- **Frontend:** HTML5, CSS3 (CSS Grid, Flexbox, custom scrollbars, mobile overlay), Vanilla JS (ES Modules)
- **Backend & Realtime:** Firebase Auth, Firestore (live listeners for messages, users, calls, invites)
- **Real‑time Communication:** WebRTC (`RTCPeerConnection`) with STUN/TURN servers — audio, video + screen‑share
- **Hosting / Assets:** GitHub Deployments (changelog fetches from GitHub API), FontAwesome (via emoji icons)

---

## 📸 Screenshots / Concept

| Login / Register | Chat View | User Profile |
|------------------|-----------|---------------|
| Neon glow panel with tab switching, T&C checkbox, and encryption badge. | Sidebar with active/unread dots, message bubbles with reactions, reply previews, and call buttons. | Banner + avatar, rank + role badges, bio, block button, and achievements strip. |

*(Add your own screenshots here or embed a demo GIF!)*

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/CameronCodesStuff/nexus.git
cd nexus
