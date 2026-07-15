# What's New in v1.1

This update focuses on improving the core app experience and introducing several new capabilities:

**Drag & Drop Improvements**
- **Rebuilt Engine**: The drag-and-drop system has been rebuilt. Reordering bookmarks on the grid is now much more responsive, with icons shifting out of the way smoothly as items are dragged around.
- **Cancel via Right-Click**: A drag operation can now be instantly aborted by right-clicking, which flawlessly reverts the grid layout and animates the icon back to its exact origin slot.
- **Focus Desaturation**: When holding an item over a folder to auto-open it, the main background now smoothly desaturates to grayscale to focus entirely on the drop target.

**Folder Enhancements**
- **Nested Folders**: Folders can now be created inside of other folders. Just drag and drop a bookmark onto another one, even when already inside a folder view.
- **Unpack Folder Action**: A new "Unpack Folder" option has been added to the right-click menu. Clicking this instantly moves all the bookmarks out of a folder and deletes the empty folder.

**Custom Color Picker & EyeDropper**
The standard system color picker has been replaced with a brand-new, built-in color picker. It features precision dragging (hold `Shift` to slow down the slider) and a native EyeDropper tool to sample colors directly from your screen.

**Better Animations**
Smoother transitions have been added for dropping items, opening folders, and canceling a drag, making the interface feel more natural.

**Custom Modals**
Standard browser popups have been replaced with custom, built-in dialogs. When deleting a folder or typing an invalid link, the alerts now match the app's clean design.

🔒 **Privacy & Security**
- **Local Network Shielding**: High-quality icons for normal public websites are still fetched securely from Google/DuckDuckGo. However, to protect privacy, bookmarks pointing to private/local network addresses (like `localhost` or `192.168.x.x`) are now shielded and will skip external icon requests entirely.
- **Uninstall Feedback**: An uninstall redirect page has been added to gather feedback on why users leave and how the extension can be improved.

🎉 **New Features & Onboarding**
- **Welcome Walkthrough**: A new first-launch welcome page features an automated 4-step carousel walkthrough with visual pointers, showing exactly where to find and pin the extension.
- **Starter Setup**: If installed for the very first time with fewer than 5 bookmarks, the grid automatically populates with a starter pack of top sites and a Google Apps folder to avoid a blank screen.
- **New Settings Defaults**: Fresh installations now default to a 4-column layout with a balanced label size for a better initial appearance.

🎨 **UI & Animation Polish**
- **Dynamic Theme Generation**: The entire UI (Settings Panel, modals, context menus) now mathematically derives its colors and borders from the 4 base theme choices, automatically maintaining readable WCAG 2.1 contrast ratios.
- **Marquee Text**: Long bookmark names now use a smooth, fixed-speed "ping-pong" animation (scrolling left, pausing, then scrolling right) instead of abruptly snapping back.
- **Simplified Icon Shapes**: The "Rounded" icon shape option has been retired to streamline choices. Existing configurations using "Rounded" are automatically migrated to "Squircle."

**Bug Fixes**
- Fixed a bug causing labels to hide improperly in certain views.
- Fixed an issue where folder thumbnails wouldn't always update immediately after adding or removing items.
- Improved overall performance and stability.
