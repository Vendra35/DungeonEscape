# Dungeon Escape | Unreal Engine 5.6 (C++ Project) 🎮

A puzzle-based third-person game prototype built in Unreal Engine 5 with C++. The goal is to solve multiple dungeon puzzles using triggers, collectible items, and interactable locks to ultimately reach the exit.

## 🎯 Gameplay

Explore the dungeon and solve 3 unique puzzles.

Collect items and place them into locks to unlock doors.

Reach the final exit by interacting with the environment and using logic to progress.

## 🛠 Features Implemented

Trigger System: Doors are activated through triggers connected to puzzle objects.

Collectible Items: Implemented using Sphere Sweep by Channel in the player’s forward direction, detecting items with the CollectableItem tag.

Custom Collision Channel (Interact): Created a dedicated collision type for interactions (ignored by default, blocked when interactable).

Inventory System: Collected items are stored in a TArray and can be placed into puzzle locks.

Lock Mechanism: When an item is placed in a lock (tagged Lock), it becomes visible at the lock position and triggers connected movers (e.g., doors).

Movers: Dynamic objects (such as doors) that move when the corresponding trigger is activated.

## 📹 Demo Video

## 👉 Watch on YouTube: https://youtu.be/QqlkdXE9Go8?si=1ojWiVI1HXoEyfLj

## 💻 Technologies Used

Unreal Engine 5

C++ (Core gameplay mechanics)

Blueprint (for minor setup and debugging)

## 🚀 What I Learned

Using triggers and movers for dynamic level design.

Implementing item interaction systems with collision channels and sweep detection.

Handling inventory logic with TArray in C++.

Combining gameplay programming with level design for puzzle-based mechanics.
