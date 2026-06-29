3.09.019 (2026-06-29)
* Improve stability
* Connect to the new API server

3.09.018 (2026-06-03)
* Fixed a display bug with large fonts
* Better error handling when downloading a non-existent file
* Added license information to the profile page
* Fixed the issue with adding blocked users to the list

3.09.016 (2026-05-12)
* **Stability improvements**
* **Fixed a bug** that stopped the download of certain sources
* **Fixed SVG display issues** on macOS

3.09.014 BETA (2026-04-02)
* Improve stability

3.09.013 (2026-04-01)
* Fix the file size sort in the shared folder view
  
3.09.012 (2026-03-31)
*   Activate and improve the file uploading system
*   Fix the "play" button when a movie is downloading 

3.09.010 (2026-03-24)
*   Fixed Crashing: Resolved a major issue when modifying shared files
*   Improved Translations: Refined how the app handles web links and settings for different languages.
*   Windows Enhancements: Fixed several Windows-specific crashes and improved how the app identifies file paths.
*   General Stability: Under-the-hood fixes to prevent various unexpected shutdowns.

3.09.009 (2026-03-20)
*   New Feature: Added a setting to choose how often the app automatically rescans your folders.
*   Smarter Settings: Changes to your rescan interval now apply immediately without a restart.
*   UI Improvements: Updated the messaging when connecting to primary users and made the Windows folder selection tool more consistent.
*   Connection Handling: Improved how the app closes connections when using command-line tools.

3.09.008 BETA (2026-03-17)
*   Maintenance: Minor stability improvements and code cleanup.

3.09.007 BETA (2026-03-09)
*   Optimized Scanning: 
    *   Scanning is now faster and uses fewer system resources.
    *   Fixed "freezing" issues by moving file updates off the main processing thread.
    *   The app now prevents multiple scans from running at the same time to save memory.
*   Developer Polish: Improved Windows build support and cleaned up internal file dependencies.
*   Reliability: Added more rigorous testing for folder behavior to prevent future bugs.

3.09.006 BETA (2026-02-16)
- Overwrite dialog optimized — faster, smoother confirmation when replacing files.
- Folder sizes displayed — folder-size now shown where relevant (improves transfer / folder view).
- Faster transfer-list updates — improved responsiveness when parsing traffic files in background.

3.09.005 (2026-02-13)
- Shows app version in your profile — current version is now visible in user profile. 
- Fix — language selector on first launch (no more wrong/default language). 
- Fix — Settings / General & Advanced options — checkboxes and options restored to correct state.
- More robust transfer UI — connection parameter hardened in traffic/transfer items (fewer invalid states/crashes). 


3.09.004 (2026-02-12)
* Version Display: Added a version column in the user list so you can easily see what version others are using.
* Rescan Option: Introduced a rescan action to help refresh shared folders more easily.
* Scanned Status: Added a column showing the scanned status of your shared folders for better visibility.
* Version Colors: Users now display in colors based on their app version, making it easier to spot compatibility.
* File Handling: Enhanced safety in file writing and traffic reading to prevent errors.
* Mac Support: Activated the new file dialog selection specifically for Mac users.
* Options Management: Better handling of options, including resetting shared folder watchers when settings change.
* Crashes: Fixed a crash issue and improved overall app stability.
* Traffic Worker: Fixed an issue with traffic reading to avoid memory problems.

3.09.002 (2026-02-06)

* Network opening now feels clearer thanks to a progress counter, a reliable first-run reset, and a friendlier “need latest version” message.
* Overall stability improves with hardened threading and transfer handling, keeping sessions smooth even under heavy load.
* Folder monitoring was revamped to use fewer disk resources.
* File transfers are more reliable: tunnels start sending as soon as ready, uploads got fixes, and the reading-folder count now shows up.
* A status-bar warning appears when the disk is deemed too slow, helping diagnose performance issues quickly.

3.08.042 BETA (2026-01-16)

- Improved CRC search performance.
- Optimized state file loading for slow drives.
- General performance improvements.


3.08.041 BETA (2026-01-14)

- Multiple optimizations on downloading files.
- General code cleanup.
- General performance improvements.


3.08.040 BETA (2025-12-22)

- Updated logging system.
- Various connection and network tunnel improvements.

3.08.038 (2025-12-18)

- Fixed Windows installer issues.
- Added macOS URL open event handling (gigatribe:// protocol).
- Multiple small bug fixes.
- [Mac version](https://www.gigatribe.com/software/macx/GigaTribe-3.08.038.dmg)

3.08.035 (2025-11-26)

- We've focused on making GigaTribe smarter, safer, and faster in this update.
- **Easier Access with Links (Deep Linking):** You can now open GigaTribe directly to the right content simply by clicking special gigatribe: links you find in your browser, emails, or chat messages.
- **Improved Security & Reliability:** We've strengthened the way GigaTribe handles links and external parts of the application, especially on Windows, making it more secure and stable overall.
- **Smoother Performance:** We've updated the application's core code to ensure it runs well and stays fast on the newest computer operating systems.

3.08.034 (2025-11-18)

- Application signing for windows system

3.08.031 (2025-11-05)

- This update makes the app more stable and reliable.
- **Runs Smoother:** Fixed issues that could cause the app to slow down or crash.
- **Better Dark Mode:** Made chat messages easier to read when using dark mode.
- **Memory usage:** Fix a memory leak when in direct connection.
- **General Fixes:** Improved connections, search, and file transfers.

3.08.030 (2025-10-30)

- A minor update to improve the update process itself.
- **Smarter Updates:** Made the automatic update feature more reliable for Windows users.

3.08.029  (2025-10-29)

- This update makes the app more user-friendly.
- **Clearer Device Names:** Your devices now show friendly names (like "John's smartphone") instead of technical codes.
- **Easier to Read:** Improved text colors in chat for both light and dark modes.
- **Sounds Fixed:** Fixed a bug that stopped notification sounds from playing correctly.
- **Other Fixes:** Improved the update process for Mac users and fixed other small bugs.

3.08.028  (2025-10-28)

- This was a maintenance update to improve how you get new versions.
- **Better Updates:** Improved the automatic update system for all users.
- **Smoother Installation (Windows):** The Windows installer now works better on more computers.

3.08.027  (2025-10-27)

- A big update focused on stability and security.
- **More Stable Connections:** Made network connections stronger and fixed issues that could cause crashes during file transfers.
- **Security Boost:** Added extra checks to keep your connections secure.
- **Faster Performance:** Made the app run more efficiently in the background.

3.08.024  (2025-10-27)

- A maintenance update to improve the experience on Windows.
- **Better Windows Installation:** The installer now works better on more Windows computers.
- **Fewer False Alarms:** Removed confusing error messages that popped up when nothing was wrong.

3.08.023  (2025-10-22)

- This update makes email notifications easier to understand.
- **Clearer Email Alerts:** The app now clearly tells you if your email notifications are off because your email address isn't verified.
- **Helpful Settings:** The settings page is now easier to understand.

3.08.022  (2025-10-21)

- A quick fix for a visual bug.
- **Device Names Fixed:** Fixed a bug that stopped your custom device names from showing up correctly.

3.08.021  (2025-10-21)

- This update focused on improving your chat experience across devices.
- **Chat Sync Across Devices:** Your chat messages now sync perfectly across all your devices (phone, computer, etc.).
- **Better Chat History:** Improved how your chat history is saved and displayed.

3.08.007-BETA (2024-05-31)

- Introduced multi-connection mode
- Optimized transfer algorithm
- Improved connectivity with VPN

3.06.015 (2024-03-06)

- Improved translations

3.06.014 (2024-02-27)

- Improved translation of recommendations.

3.06.013 (2024-02-19)

- Fixed a missing translation in French.
    
3.06.012 (2024-02-13)

- Added a notification option in the profile settings 
- Improved Spanish translation

3.06.011 (2024-02-08)

- Improved GDPR compliance.
- Fixed a bug on the Linux version.

3.06.010 (2021-08-30)

- Added fixes from the BETA version into the Release version.

3.07.009-BETA (2021-08-30)

- Fixed an issue with icon display on retina screens under Mac.
- Removed the update button on Mac (there is no automatic update under Mac/beta).
- Fixed bugs in chat history.

3.07.005-BETA (2021-06-08)

- Improved error handling when reading chat history.

3.07.004-BETA (2021-06-07)

- Fixed another bug in chat history.
- Improved user profile when the email address is not validated.
- "Delete unnecessary transfers" becomes "Delete completed transfers."

3.07.003-BETA (2021-05-20)

- Fixed bugs in chat history.
- Added a bug reporting form directly in the chat.


3.06.007 (2020-06-22)

- Fix chat on Windows (char encoding error)

3.06.006 (2020-06-19)

- Backport from the beta of the fix on the chat history

3.07.001-BETA (2020-06-12)

- Improve the chat history file storage

3.06.005 (2020-06-03)

- Fix the play video during download feature
- Improve the windows installer

3.06.004 (2020-05-18)

- Add the Reset menu

3.06.003 (2020-04-24)

- Fix the distant folder update
- Design fix with the big font options
- Improve the Mac installer (dmg)

3.06.002 (2020-04-08)

- Fix design when configuring shared folders
- Improve the account informations display (display non validated emails and add a validate email button)
- The news page become the home page
- Add a hashtag search option in the search dialog
- Select subfolder by default when sharing a folder

3.06.001 (2020-03-31)

- Minor update on wording
