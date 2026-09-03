GRPS Title I Resource Center — Mobile Navigation Patch v72

Fixes the phone header so users can see the primary navigation choices.
On screens 760px wide or smaller, a compact horizontally scrollable navigation strip appears:
Start | What is Title I? | Key Dates | Resources | Help

The persistent bottom-right Home / Quick Help / My Work controls are retained.

Upload the CONTENTS of this patch folder to the root of the existing repository and replace existing files.

Commit message:
Fix mobile header navigation

{
  "mobile_primary_navigation_added": true,
  "mobile_choices": [
    "Start",
    "What is Title I?",
    "Key Dates",
    "Resources",
    "Help"
  ],
  "persistent_bottom_home_retained": true,
  "patch_files": 64,
  "purpose": "Restore visible header choices on phone widths without hiding desktop navigation."
}