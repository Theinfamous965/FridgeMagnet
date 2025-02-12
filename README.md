# 🧊 Fridge Magnet App

## 📌 Overview
Fridge Magnet App is a SwiftUI-based application designed to help users track the items in their fridge efficiently. It follows an **Agile development approach**, implementing features in sprints to ensure continuous testing and iterative improvements.

## 🚀 Features Roadmap
We are developing this app in multiple sprints to enhance functionality progressively. Below is our Agile development plan:

### 🟢 Sprint 1: Initial Setup & Core Features
**Goal:** Establish the base application with essential functionalities.
- ✅ Create a new SwiftUI project in Xcode.
- ✅ Set up a modular structure: **Models, Views, ViewModels, Services, Utilities, Resources**.
- ✅ Implement `FridgeItem` model.
- ✅ Implement `FridgeViewModel` for state management.
- ✅ Create `FridgeView.swift` UI with a list of fridge items.
- ✅ Implement CRUD operations (Add, Update, Delete fridge items).
- ✅ Use **UserDefaults** (temporary storage) for persistence via `PersistenceManager`.
- ✅ Create `FridgeDetailView.swift` for modifying item details.
- ✅ Implement UI updates with `@StateObject` and `@Binding`.

### 🟢 Sprint 2: Persistence & UI Enhancements
**Goal:** Improve data persistence and user interface.
- ✅ Replace **UserDefaults** with **CoreData** for storage.
- ✅ Implement saving/loading fridge items from **CoreData**.
- ✅ Unit testing for persistence logic.
- ✅ Create custom **SwiftUI components** for list items, buttons, and detail views.
- ✅ Implement **dark mode support**.
- ✅ Improve navigation flow between screens.

### 🟢 Sprint 3: Advanced Features
**Goal:** Enhance functionality and user experience.
- ✅ Implement a **search bar** in `FridgeView` to filter items.
- ✅ Enable sorting by **expiration date, name, or category**.
- ✅ Create `Recipe` model and `RecipeViewModel`.
- ✅ Implement `RecipesView.swift` to manage recipes.
- ✅ Suggest **recipes based on available fridge items**.

### 🟢 Sprint 4: Cloud Sync & Notifications
**Goal:** Improve accessibility and real-time tracking.
- ✅ Implement **CloudKit** support for syncing fridge items across devices.
- ✅ Add authentication for **user-specific data**.
- ✅ Add **local notifications** for expiring items.
- ✅ Implement a **widget** to show upcoming expirations.

### 🟢 Sprint 5: Final Touches & Deployment
**Goal:** Prepare the app for App Store release.
- ✅ Profile performance and optimize **CoreData queries**.
- ✅ Ensure **accessibility compliance** (VoiceOver support).
- ✅ Fix UI/UX inconsistencies.
- ✅ Set up **App Store Connect**.
- ✅ Submit the app for **TestFlight beta testing**.
- ✅ Gather feedback and refine before final release.

## 📷 Screenshots (Coming Soon)

## 🔧 Tech Stack
- **SwiftUI** for UI development
- **CoreData** for persistent storage
- **CloudKit** for cloud sync
- **UserDefaults** (used in early versions)
- **Local Notifications** for expiration alerts
- **TestFlight** for beta testing

## 📦 Installation
To run the project locally:
1. Clone the repository:
   ```sh
   git clone https://github.com/Theinfamous965/FridgeMagnet.git
   ```
2. Open the project in **Xcode**.
3. Build and run on a simulator or a physical device.

## 🚀 Future Enhancements
- 🔹 Barcode scanning for easier item input
- 🔹 AI-based recipe suggestions
- 🔹 Multi-user collaboration

## 🤝 Contribution
We welcome contributions! Feel free to submit issues or pull requests.

## 📄 License
This project is licensed under the **MIT License**.

## 📩 Contact
For any inquiries, please reach out via [GitHub Issues](https://github.com/yourusername/FridgeMagnet/issues).

