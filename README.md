# Mivi Web Accessibility Lite

A lightweight, floating accessibility widget for WordPress that gives your visitors control over how they experience your content — with font size, bold text, link highlighting, line height, and word spacing controls.

No external dependencies. No data sent to any server. Fully self-contained.

---

## Features

| Feature | Description |
|---------|-------------|
| **Font Size Adjustment** | 5-step slider from 100% to 200% so visitors can scale text to their comfort level |
| **Bold Text Toggle** | Apply bold weight across all page elements for improved readability |
| **Highlight Links** | Make all links visually distinct with a highlighted background and outline |
| **Line Height Adjustment** | Increase line spacing for easier reading |
| **Word Spacing Adjustment** | Add extra space between words to improve readability |

All visitor preferences are stored locally in the browser via `localStorage` — no cookies, no tracking, no server calls.

---

## Requirements

- WordPress 5.8 or higher
- PHP 7.4 or higher

---

## Installation

### Option 1: Install from WordPress.org (Recommended)

<!-- TODO: Update this section once approved on WordPress.org -->

> **Status:** Pending approval on WordPress.org. This section will be updated with the direct install link once the plugin is listed.

1. In your WordPress dashboard, go to **Plugins → Add New**
2. Search for **"Mivi Web Accessibility Lite"**
3. Click **Install Now**, then **Activate**
4. Go to **Settings → Mivi Accessibility Lite** to configure the widget

<!--
Direct link (available after approval):
https://wordpress.org/plugins/mivi-web-accessibility-lite/
-->

### Option 2: Manual Upload

1. Download the latest release from this repository (or grab the `.zip` from the [Releases](../../releases) page)
2. In your WordPress dashboard, go to **Plugins → Add New → Upload Plugin**
3. Choose the `mivi-web-accessibility-lite.zip` file and click **Install Now**
4. Click **Activate**
5. Go to **Settings → Mivi Accessibility Lite** to configure the widget

### Option 3: Via FTP / File Manager

1. Download and unzip the plugin
2. Upload the `mivi-web-accessibility-lite` folder to `/wp-content/plugins/`
3. In your WordPress dashboard, go to **Plugins** and activate **Mivi Web Accessibility Lite**
4. Go to **Settings → Mivi Accessibility Lite** to configure the widget

---

## Configuration

Once activated, navigate to **Settings → Mivi Accessibility Lite** in your WordPress admin. Three options are available:

| Setting | Description | Default |
|---------|-------------|---------|
| **Enable Widget** | Show or hide the widget on the frontend | Enabled |
| **Widget Position** | Corner placement — bottom-right, bottom-left, top-right, or top-left | Bottom Right |
| **Primary Color** | Accent color for the widget button and UI elements | `#1e1e5a` |

---

## How It Works

The plugin adds a small floating button to your site. When clicked, a side panel opens with accessibility controls your visitors can toggle on or off. Settings persist across page loads using the visitor's local browser storage.

The widget uses Shadow DOM for complete style isolation — it won't conflict with your theme or page builders.

---

## Pro Version

The Lite version covers the essentials. The full **Mivi Web Accessibility Widget** unlocks 20+ additional features:

- **Accessibility Profiles** — Seizure Safe, Vision Impaired, ADHD Friendly, Cognitive Disability
- **Color Adjustments** — Contrast, Saturation, Dark Mode
- **Content Tools** — Dyslexia Font, Highlight Headings, Letter Spacing, Text Alignment
- **Navigation Tools** — Reading Guide, Stop Animations, Big Cursor, Keyboard Navigation, Focus Mode, Hide Images, Reading Mask, Mute Sounds

**[Learn more about the full version &rarr;](https://mivibzzz.com/services/accessibility/wordpress-accessibility-plugin)**

---

## Frequently Asked Questions

**Does this affect site performance?**
Minimal impact. The widget is a single lightweight JavaScript file with no external dependencies.

**Does it work with page builders?**
Yes — Elementor, Divi, WPBakery, Gutenberg, and others. The Shadow DOM encapsulation prevents style conflicts.

**Where is user data stored?**
Only in the visitor's browser (`localStorage`). Nothing is sent to any server or third party.

**Can I change the widget color?**
Yes, via the color picker in **Settings → Mivi Accessibility Lite**.

---

## License

GPL-2.0-or-later. See [LICENSE](LICENSE) for details.

---

## Links

- [Full Version — Mivi Web Accessibility Widget](https://mivibzzz.com/services/accessibility/wordpress-accessibility-plugin)
- [Author — Mivi](https://mivibzzz.com)
