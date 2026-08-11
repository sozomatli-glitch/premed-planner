# premed-planner
Transfer Planner — User Manual
What is this?
The Pre-Med Transfer Planner is a free, browser-based tool designed for California Community College (CCC) students planning to transfer to a UC. It helps you track your courses, Cal-GETC requirements, major prerequisites, and (optionally) pre-med requirements — all in one place.

No account needed. No data sent anywhere. Everything saves in your browser.

⚠️ Important — Your Data Lives in Your Browser
This app stores all your data in your browser's local storage. This means:

✅ No account or login required
✅ Your data is private — nothing leaves your device
❌ Clearing your browser history/cache will erase your plan
❌ Data does not sync between devices or browsers
❌ Opening the app in a different browser starts fresh
👉 Export your plan regularly as a backup. This is the most important habit to build.

Navigating the App
The sidebar on the left has these pages:

Page	Purpose
📅 Planner	Add and manage your courses by term
📋 Cal-GETC	Track your GE requirements
🩺 Pre-Med	Track pre-med prerequisites (if enabled)
🧠 Major Prereqs	Track major-specific prerequisites
🏫 Schools	Manage your UC/university list
📊 GPA	GPA calculator (if enabled)
⚙️ Settings	Customize the app
Click ☰ to collapse the sidebar for more screen space.

📅 Planner
The Planner is your home base. Each column is a term (semester or quarter).

Adding a term
Click + Add Term to add a new semester or quarter.

Adding a course
Click + Add Course inside any term. A modal will open with these fields:

Field	What to enter
Course Code	e.g. BIO 001A
Units	Number of units
Course Title	e.g. General Biology
Status	Planned / In Progress / Completed
Grade	e.g. A, B+ (completed courses)
Transfers to UC(s)	Check which UCs this course articulates to
Cal-GETC Area	Which GE area this satisfies
Pre-Med Category	Which pre-med requirement this covers
Science (BCPM)	Check if this is a science course
Has Lab Component	Check if this course has a lab
Prerequisites	e.g. BIO 001A
Notes	Anything extra
Course status colors
🟢 Completed — course is done
🔵 In Progress — currently taking
🟡 Planned — future course
Filtering by UC
Use the UC filter dropdown in the toolbar to see only courses that transfer to a specific UC. The unit counter in the top bar updates to show transferable units to that school.

Drag and drop
Courses can be dragged between terms to reorganize your plan.

📋 Cal-GETC Tracker
Cal-GETC is the statewide GE pathway for CCC → UC/CSU transfers (replaced IGETC for Fall 2025+). Completing Cal-GETC means your lower-division GE is certified for any UC.

How it works
Each area card shows:

How many courses are done (green) and planned (blue)
A progress bar
Which specific courses are filling that requirement
Tagging a course to Cal-GETC
When adding or editing a course, select the Cal-GETC Area from the dropdown. The course will automatically appear in that area's card.

AP Exam Credits
If you have AP exam credit that satisfies a Cal-GETC area, add it in Settings → 🎓 AP Exam Credits. AP credits appear inside the relevant area card with a 🎓 tag.

Note: UC campuses typically require a score of 3 or higher for AP credit — check with each campus for exact policies.

Area 5 Lab
A separate Area 5 Lab card tracks whether you have a lab science course. To mark a course as satisfying the lab requirement, edit the course and check 🧪 Has Lab Component.

AP credits do not satisfy the Area 5 Lab requirement — you need an actual lab course.

The 🎓 All UCs badge
Courses tagged to a Cal-GETC area automatically show a 🎓 All UCs badge — because Cal-GETC certification transfers to all UCs. Hover or tap the badge to see the full UC list.

🩺 Pre-Med Mode
Pre-Med Mode is on by default. If you are not pre-med, you can turn it off in Settings → 🩺 Pre-Med Mode and all pre-med specific UI will be hidden.

When Pre-Med Mode is ON
The Pre-Med page tracks nine standard pre-med prerequisites:

Requirement	Courses Needed
General Biology + Lab	2
General Chemistry + Lab	2
Organic Chemistry + Lab	2
Physics + Lab	2
Biochemistry	1
Math / Statistics	2
English / Writing	2
Psychology	1
Sociology	1
Tagging a course as pre-med
When adding or editing a course, select the Pre-Med Category it satisfies. It will automatically count toward that requirement.

Customizing requirements
Go to Settings → 🩺 Customize Pre-Med Requirements to:

Adjust how many courses each requirement needs
Add custom requirements
Remove requirements that don't apply to you
Pre-Med badges on course cards
When pre-med mode is on, courses tagged to a pre-med category show a Pre-Med badge on their card in the planner.

Science / BCPM
Checking Science (BCPM) on a course marks it as a Biology, Chemistry, Physics, or Math course. This feeds into the GPA calculator's science GPA if enabled. It also tracks your Area 5 lab eligibility — keep this checked for all science courses regardless of pre-med mode.

🧠 Major Prereqs
Track the specific courses required for your intended major at each UC.

Manual sets
Click + Add Prereq Set to create a set for a school/major combination (e.g. UCLA Neuroscience). Add the course codes required by that major.

Universal prereqs
Add prereqs that apply to all your target schools (e.g. MATH 1A) using the Universal Prereqs section. They automatically appear in every manual set marked with 🌐.

Templates
If you have an ASSIST-derived JSON template, you can import it for automatic articulation matching.

Matched vs missing
Each prereq row shows:

✓ Done — you have a completed course matching this code
◔ Planned — you have a planned course matching this code
Missing — no matching course found yet
🏫 Schools
Manage your list of target UC and private universities.

Your UC list feeds into the UC filter on the planner and the Cal-GETC "All UCs" tooltip
Private schools can be added with custom notes (e.g. application requirements, deadlines)
UC themes let you color-code the app per school
💾 Exporting and Importing Your Plan
This is the most critical feature to understand. Since data lives in your browser, exporting is your only backup.

Exporting
Go to the Planner page
Click ⬇ Export
A file called premed-plan.json downloads to your computer
Save it somewhere safe (cloud storage, external drive, etc.)
Export regularly — especially before:

Clearing your browser history or cache
Switching computers
Updating the app
Importing
Go to the Planner page
Click ⬆ Import
Select your .json file
Your full plan loads instantly
Switching devices or browsers
Export on your current device
Open the app on the new device/browser
Import your file
Everything is restored exactly as you left it
Tip: Keep your latest export in Google Drive or iCloud so you can always access it from any device.

⚙️ Settings
Setting	What it does
🎨 Theme	Color themes based on UC schools or custom colors
🩺 Pre-Med Mode	Toggle pre-med tracking on/off
🎓 AP Exam Credits	Add AP scores that count toward Cal-GETC
📊 GPA Calculator	Enable/disable GPA tracking
📆 Term System	Switch between Semester and Quarter
🩺 Customize Pre-Med Reqs	Edit pre-med requirement counts
🏷️ App Title	Rename the app
⚠️ Reset	Erase all data and start fresh
💡 Tips
Export before resetting — the reset button permanently erases everything
Use the search bar on the Planner to quickly find a course
Double-click any course card to open it for editing
Drag courses between terms to reorganize your plan
Check ASSIST.org for official articulation agreements between your CCC and target UCs
🐛 Found a Bug?
Report it at:
github.com/sozomatli-glitch/premed-planner/issues

Click New Issue, describe what happened and what you expected, and it will be looked into.

Pre-Med Transfer Planner · v5 · Local-only, no account required
