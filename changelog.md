> Release Date: 21/02/2026

# MANDATORY UPDATE

- Force pushed: any previous version will no longer work


## Added option to fix LSPosed prop detection

- (dalvik.vm.dex2oat-flags)


## Bump SECURITY_PATCH

- Updated SECURITY_PATCH to 2026-02-01

  
## Update Integrity Downloader

- Added support for core patch, Android Faker, Thor, and updated ZN hash


## Update Local Fingerprint

- Updated local fingerprint configuration


## Enhance Integrity Profile Menu UI

- Updated UI to iOS-style design with blur effects, gradients, new color system, and smoother animations
- Updated layout spacing, rounded corners, and typography for a cleaner look
- Updated header title with icon
- Added segmented header section above title
- Updated profile descriptions and icons for Supreme, Legacy, and Meta
- Added active state checkmark indicator with animation
- Improved loader with blur background, fade animation, and dynamic status text
- Updated popup styling with better colors, shadow, and smoother transition
- Added custom loader messages for profile switch and data clearing
- Updated action buttons with primary/danger styles and new labels
- Improved APK button logic and added popup on click
- Updated notes section styling to list format with improved visuals
- Improved responsive behavior for small screens
- Added animation delay effect when rendering profile items


## Enhance Risky App Detection UI

- Updated UI to a cleaner Material Design look with new colors and shadows
- Replaced header bar with icon, title, and subtitle
- Redesigned main card with blurred background and rounded corners
- Updated buttons to Material-style with icons, hover effects, and press animation
- Added circular progress indicator with live status text
- Added stats bar showing scanned apps, risky apps, and spoofed apps
- Reworked logs into cards with app icons, names, packages, and colored status chips
- Replaced old toast messages with snackbar and fallback popups
- Renamed `addBubble` to `addStatusCard` with app icon support and live counters
- Added live counters for scanned, risky, and spoofed apps
- Added `escapeHtml` for safe display of app names and packages
- Improved scanning loops with progress updates and shorter delays
- Added error handling to show snackbar on scan failure
- Cleaned up code for readability and maintainability


## Enhance TrickyStore UI

- Updated app theme to darker shades with subtle gradient highlights
- Enlarged header title, added gradient text, and floating icon effect
- Cards now feature blur effect, smoother hover shadow, and glow animation
- Improved search bar with darker background, inner shadow, and better placeholder styling
- Updated list items with smoother hover, staggered animations, and gradient for blacklisted apps
- Increased app icon size with rounded corners, shadow, and hover scale effect
- Enhanced toggles with gradient when active, smoother transitions, and clearer disabled style
- Added hover rotation and pulse animation for blacklisted app icon buttons
- Updated buttons with gradient backgrounds, shadows, and improved hover effects
- Restyled toast notifications with icons, blur background, and clearer error styling
- Made scrollbar thinner with gradient thumb
- Tweaked animations for slide, float, shimmer, shake, and pulse
- Adjusted mobile layout with smaller paddings and font sizes
- Enhanced popup system fallback
- Updated blacklist logic to automatically remove target when added to blacklist
- Lazy-loaded icons now scale in smoothly; broken icons fade out
- Minor padding, gap, and border-radius refinements for a cleaner layout


## UI & Interaction Improvements

- Redesigned buttons with hover effects, radial highlights, and icon rings
- Adjusted card and button padding, border radius, and shadows for a modern look
- Added subtle animations for title and card entrance
- Resized and restyled toast messages and loader spinner
- Added responsive layout adjustments for smaller screens
- Implemented mouse position tracking on buttons for hover effects

- Updated card with fade-in animation on load
- Added slide-down animation for the header
- Row icons now scale slightly on hover
- Adjusted row hover and active states for smoother feedback
- Refined popup notifications to reuse a single element
- Popups now show and hide with smooth transitions
- Tweaked transition timings for sliders, knobs, and rows
- Minor spacing and padding adjustments for cleaner layout
- Refined box-shadow and hover effects for better visual feel


## Enhance Main WebUI UX

- Added subtle pulsing animation
- Main content now fades and slides in smoothly on page load
- Dashboard section now slides in with a stronger glowing background effect
- Status cards now appear sequentially with a soft pop-in effect
- Added glowing accent line on hover for status cards
- Improved hover effects on status cards
- Status labels slightly grow and glow on hover
- Buttons animate into view with smooth upward motion
- Improved button hover responsiveness and visual feedback
- Added subtle animated glowing border effect on buttons
- Button icons gently float and briefly spin on hover
- Button text slightly lifts and glows on hover
- Adjusted button press effect for quicker responsiveness

- Implemented full animated modal system:
  - Background fades and blurs on open
  - Modal scales and slides into view smoothly
  - Header and content animate separately
  - Modal title features soft glow animation
  - Close button rotates and glows on hover
  - Modal scrollbar has subtle pulse effect
  - Fullscreen mode includes smooth expand animation

- Slowed spinner rotation slightly for smoother appearance
- Title section now gently floats
- Main title has soft glowing pulse effect
- Subtitle includes subtle shimmer animation
- Improved hover and focus effects
- Removed unused stylings
