🍁 Sugar Maple Tree (Acer saccharum): Museums & 6D Thermal Matrix

An interactive, multi-dimensional web application that bridges botanical science, regional museum heritage, and thermal/spectral visualization. Explore the geography, anatomy, and syrup-producing mechanics of the Sugar Maple (Acer saccharum) through a dynamic 3D globe and interactive tree model.

🌟 Key Features

3D Interactive Globe Stage:

Map out primary maple syrup production regions and living museum collections across Quebec, Ontario, Vermont, New York, Maine, New Brunswick, and Nova Scotia.

Visualize freeze-thaw gradient paths and historical syrup trade routes.

6D Multispectral Anatomical Engine:

3D Space: Interactive controls for rotation, pitch, and cutaway depth.

4D Time: Seasonal slider modeling freeze-thaw cycles, sap flow pressure, leaf canopy evolution, and winter dormancy.

5D Light (Spectral Bands): Multispectral visualization modes including Visible, Near-Infrared (NIR), Thermal, UV Fluorescence, and X-Ray.

6D Sap Chemistry: Interactive focus on key chemical constituents (Sucrose, Glucose, Fructose, Phenols, and Minerals).

Multi-Tiered Audience Experience:

Expert Mode: In-depth technical readouts, precise spectral indices, and scientific terminology.

Simple Mode: Accessible summaries and clear explanations of key forestry and sugaring terms.

Kids Mode: Interactive gamification featuring sap-catching minigames, trivia quizzes, achievement badges, animated effects, and simplified explanations.

🛠️ Technology Stack & Architecture

This project is built as a zero-build, single-file web application using modern browser standards and minimal external dependencies:

3D Graphics & Rendering Engine:

Three.js (r128): Powers WebGL rendering for the interactive 3D globe stage, vector arcs, point-cloud terrain mapping, instanced leaf geometry (THREE.InstancedMesh), and local hardware-accelerated clipping planes (THREE.Plane).

Fonts & Typography:

Google Fonts Integration: Uses Cormorant Garamond, Hanken Grotesk, IBM Plex Mono, Atkinson Hyperlegible, Baloo 2, and Young Serif to deliver distinct typographic experiences across Expert, Simple, and Kids reading modes.

UI & Styling:

Native HTML5 & Modern CSS3: Dynamic theme switching using CSS custom properties (:root variables), CSS Grid, Flexbox, dynamic responsive layouts (clamp(), env()), and custom UI micro-animations (@keyframes).

Animation & Canvas Graphics:

HTML5 2D Canvas API: Powers particle burst animations, leaf confetti engine, and dynamic map projections.

Inline Scalable Vector Graphics (SVG): Interactive game scene rendering with responsive viewport scaling.

Browser & Web APIs:

Pointer Events API with Pointer Capture (setPointerCapture) for smooth touch/drag interactions on 3D stages.

RequestAnimationFrame API for dual 60fps render loop execution.

History API (history.replaceState) and hashchange events for seamless stateful URL routing.

System Accessibility APIs (prefers-reduced-motion) to respect user motion preferences.

📜 Historical Note

Maple sugaring originated with the Indigenous peoples of northeastern North America, whose traditional ecological knowledge of the sugar maple long predates modern museum collections and commercial production.

🔒 Copyright & Rights Reserved

© 2026 Asia Khan. All Rights Reserved.

No part of this software, code, interactive 3D models, or written content may be reproduced, distributed, modified, or used in any commercial or non-commercial work without prior written permission from the copyright holder.
