## List Fixer Roadmap

### Phase 1: The "Sandbox" (Completed)
* [x] Basic web page to paste and drag items.
* [x] Verified SortableJS works on iOS/iPadOS.

### Phase 2: iOS & UI Refinement (Current)
* [x] Remove manual text area for a cleaner "List Fixer" UI.
* [x] Implement "One-Tap" clipboard import.
* [x] Fix multi-line paste issues for iOS Safari.
* [x] Add "Sticky" headers and "Copied!" feedback.
* [x] Add a visible Version Number (e.g., v1.0.1) to track GitHub refreshes.
* **[Next] Add a "Delete" icon to each individual list item.**
* **[Next] Add an "Add Item" button to manually insert a new bullet.**
* [ ] **User Testing:** Use for daily reorganization to find friction points.

### Phase 3: Section Management
* [ ] **Identify Headers:** Program the tool to recognize `###` and style them as distinct "Section Headers."
* [ ] **Section Sorting:** Ensure headers can be moved and items can be dragged between them.
* [ ] **User Testing:** Use for daily reorganization to find friction points specifically with nested/sectioned data.

### Phase 4: Integration
* [ ] **One-Tap Export:** Explore **Obsidian URI** to send the fixed list directly back to a specific note.
* [ ] **Apple Shortcuts:** Create a shortcut to launch the "List Fixer" directly from the iOS Share Sheet.

### Phase 5: Code Cleanup & Refactoring
* [ ] **Linting & Formatting:** Ensure consistent code style.
* [ ] **Modularity:** Separate CSS, JavaScript, and HTML logic into cleaner blocks.
* [ ] **Optimization:** Streamline the SortableJS logic for mobile performance.

### Phase 6: The Voice Layer
* [ ] Introduce Web Speech API for hands-free commands.
* [ ] **Define Command Set:** Develop commands based on user testing (e.g., "Move top to bottom," "Delete first item," etc.).
* [ ] **User Testing:** Test voice reliability in different environments and find friction points.

### Phase 7: Final Polish & Cleanup
* [ ] Final bug hunt and performance audit.
* [ ] Final refactoring of the voice integration logic.
* [ ] Documentation for personal use/future maintenance.
