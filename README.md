/* General styles for all anchor tags */
a {
  color: inherit; /* Inherit the color from the parent element */
  text-decoration: none; /* No underline */
}

/* Ensuring that the anchors do not change on hover or focus */
a:hover, a:focus {
  color: inherit; /* Maintain the same color on hover/focus */
  text-decoration: none; /* No underline on hover/focus */
}

/* Code blocks styling */
pre, code {
  background-color: #333; /* Dark background for code blocks */
  color: inherit; /* Text color for code blocks, inheriting from body */
  font-family: monospace; /* Font family for code elements */
  border-radius: 5px; /* Rounded corners for aesthetics */
  padding: 5px;
}

/* Dark mode specific styles */
body[data-mode="dark"] {
  color: #C0C0C0 !important; /* Text color for dark mode */
  background-color: #282828 !important; /* Background color for dark mode */
}

body[data-mode="dark"] pre, body[data-mode="dark"] code {
  background-color: #444 !important; /* Slightly lighter background for code blocks in dark mode */
  color: #C0C0C0 !important; /* Text color for code elements in dark mode */
}

/* Sepia mode specific styles */
body[data-mode="sepia"] {
  color: #4B382A !important; /* Text color for sepia mode */
  background-color: #F5EFE6 !important; /* Background color for sepia mode */
}

body[data-mode="sepia"] pre, body[data-mode="sepia"] code {
  background-color: #D8C8B8 !important; /* A sepia-toned background for code blocks */
  color: #4B382A !important; /* Text color for code elements in sepia mode */
}

/* ...other styles as previously defined... */
