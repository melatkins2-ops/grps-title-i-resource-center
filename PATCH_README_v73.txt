GRPS Title I Resource Center — Mobile Landscape Navigation Patch v73

Fixes the issue where the header navigation disappears when a phone is rotated horizontally.

Upload the CONTENTS of this patch folder to the root of the existing repository and replace existing files.

Commit message:
Fix mobile landscape header navigation

{
  "landscape_phone_breakpoint": "max-width 1024px + landscape",
  "short_viewport_fallback": "max-width 1180px + max-height 620px",
  "mobile_nav_retained": true,
  "persistent_home_retained": true,
  "patch_html_files": 64,
  "purpose": "Keep the mobile primary navigation visible when a phone rotates to landscape."
}