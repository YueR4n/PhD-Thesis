# PaperE

This folder is for PaperE content.

QR code link: [https://mywebar.com/qr/377568]
AR experience link: [https://mywebar.com/p/Project_0_wvjbly60vv]

# Designed Platform in Chapter 8 Conclusion - Platform Design

## Vibe coding prompts

This part credits to Chengyi Xu - https://github.com/chengyixu

### Tab 1: Explore
Interface: Xiaohongshu (RED)-style two-column waterfall card layout
Card content:

Real-scene photo of the location (cover image)
Sound wave visualization rendered in JS
Title (AI auto-generated or user-customized)
Creator avatar + nickname
Play count + save count

Interactions:

Scroll to browse; when a card enters the viewport, auto-play a 3-second preview (muted; tap the card to turn on sound)
Tap a card → full-screen immersive playback page:

Location photo as a blurred background
Large-scale sound wave visualization
Map marker (showing where this soundscape comes from)
Tags, description, AI style notes
Comment section
Save / Like / Share buttons

### Tab 2: Create
Interface: Large buttons, etc.; tap to expand 5 creation modes
Mode 1: Recording

Press and hold the record button; display the sound wave in real time
Automatically capture location + place name
After recording, AI processes everything automatically

Mode 2: Photo / Image Upload

Take a photo or select one from the album
AI recognizes the scene in the image → infers the sounds of that place → generates a soundscape
Example: upload a photo of a Sham Shui Po wet market → AI generates: vendor calls, chopping sounds, crowd noise, air-conditioner humming

Mode 3: Text Description

Enter any text: scene description, diary, poem, memory
AI extracts the sound elements within → generates a corresponding soundscape
Example: "Grandma's kitchen when I was little—the clatter of the spatula, the radio, the kettle bubbling"

Mode 4: File Upload

Upload an existing audio file
AI analyzes → enhances → expands → adds artistic style

Mode 5: Random

### Tab 3: Discover
Interface: Map as the main view
Map interactions:
Display modes:

Soundscape density heatmap
Cluster markers (showing counts, e.g., "47 soundscapes")
Individual soundscape markers (mini sound wave + play button)

Features:

Tap a marker → pop-up card: cover image, title, sound wave, play button, distance
"Nearby soundscapes" button → shows surrounding soundscapes, sorted by distance
Drag/zoom the map → the list below updates in real time to the soundscapes within the visible area
Top search bar:

Supports natural language: "the feeling of a rainy day," "a quiet park"
AI semantic search
Search results shown on both the map and the list simultaneously

Category filters: Location | Environment type | Mood | AI style

### Experience Link
Panor tech - https://www.panor.tech/voice/
