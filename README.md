# ⭐ Holonlab - PWA to support card collectors

A Progressive Web App built with **VueJS**, **Vuetify**, **Express**, and **Firebase**, designed to help card collectors with a smoother user experience and weekly monitoring of [PCA](https://pcagrade.com/fr/) graded Pokémon cards.

Thanks to the collaboration of [collectors](https://holonlab.vercel.app/about), we are able to retrieve and update data for more than 900 cards every week!

>The application was discontinued once PCA improved the visibility of data on its official platform.<br> *Before its shutdown, Holonlab had reached 50 registered accounts, 500 unique users, and over 5,000 monthly page views.*

## 📸 Preview
<img width="400" height="auto" alt="Holonlab list view" src="https://github.com/user-attachments/assets/529ff4fc-0b47-4a44-a3cd-e90054cb3fef" />
<img width="400" height="auto" alt="Holonlab detailed view" src="https://github.com/user-attachments/assets/57624684-1ef5-4301-9f04-b112278c8334" />
<img width="400" height="auto" alt="Holonlab favorites view" src="https://github.com/user-attachments/assets/0e622d44-4174-4c63-9c3f-bf5a9ad3850e" />
<img width="400" height="auto" alt="Holonlab notifications view" src="https://github.com/user-attachments/assets/c0fdce28-2bf9-4170-93fc-89027a512021" />

---

## 🚀 Features

- 📋 Cards list with infinite scrolling.
- 🔍 Search cards by name, set, or rarity.
- 📈 Data history on the detailed view.
- ❤️ Favorites mode to easily track selected cards.
- 🔔 Notification system to alert you whenever a favorite card’s amount changes.
- 👥 Role-based access control to manage permissions and let collaborators contribute card data directly.
- ℹ️ About view to thank friends and collectors who contributed to the project.
- 📴 Mobile app & offline support through PWA.
- 🌙 Dark mode for a comfortable viewing experience.

---

## 🎨 Design system

- **UI / UX**: myself

---

## 🛠️ Tech Stack

- **Framework**: [VueJS 2](https://v2.vuejs.org/)
- **Store**: [VueX](https://vuex.vuejs.org/)
- **Component framework**: [Vuetify](https://vuetifyjs.com/en/)
- **Auth & identity**: [Firebase](https://firebase.google.com/)
- **BDD (noSQL)**: [Firestore](https://firebase.google.com/docs/firestore)
- **Serveler Functions & CRON jobs**: [Google Cloud Platform](https://cloud.google.com/)
- **Scrapper**: [Puppeteer](https://pptr.dev/)

---

## 📦 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/v-p-l/holonlab.git
   cd holonlab
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the application**:
   ```bash
   npm run serve
   ```
