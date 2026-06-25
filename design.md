---
colors:
primary: "#1A1C1E" # ink — all headlines
secondary: "#5B6470" # muted supporting text
tertiary: "#B8422E" # the ONE interactive accent
background: "#F7F5F2" # warm limestone canvas
surface: "#FFFFFF"
on-surface: "#1A1C1E"
typography:
heading:
fontFamily: "Space Grotesk"
fontSize: "32px"
fontWeight: 600
lineHeight: "1.15"
body:
fontFamily: "Public Sans"
fontSize: "16px"
fontWeight: 400
lineHeight: "1.6"
spacing:
unit: "8px"
card-gap: "16px"
rounded:
DEFAULT: "0.5rem"
lg: "1rem"
full: "9999px"
components:
button-primary:
backgroundColor: "{colors.tertiary}"
textColor: "{colors.background}"
rounded: "{rounded.DEFAULT}"
typography: "{typography.body}"
---
# Overview
[Your brand in one line. The feeling in three words.]
# Colors
Primary ink (#1A1C1E) carries every headline. Boston Clay (#B8422E) is the
single interactive accent — use it for the most important action on a screen,
never for decoration.
# Typography
Space Grotesk for labels and headings; Public Sans for body. Generous line
height keeps long reading calm.
# Do's and Don'ts
- DO reference tokens with {curly.braces}; never paste a raw hex into a component.
- DON'T introduce a color, radius, or font that isn't a token.