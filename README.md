# AuraMetrics
Engineering serenity in the face of complex AI telemetry. 

A high-performance AI Observability platform featuring a GPGPU-driven neural lattice simulation. Built with Next.js 14, Three.js, and GLSL to demonstrate advanced front-end orchestration and performant 3D rendering.


🚀 Key Features

• Serene Neural Lattice Simulation: A custom-built WebGL background utilizing GPGPU (General-Purpose Computing on GPU) logic to simulate thousands of organic, swaying data points.

• Context-Aware Layout: An asymmetric cinematic grid designed for high readability, featuring CSS-masked canvas overlays to ensure zero interference with typography.

• Scroll-Linked Camera Orchestration: Seamless transitions between "Overview" and "Deep-Dive" states using non-linear interpolation and scroll-velocity tracking.

• Adaptive Performance Scaling: Real-time monitoring of frame rates with automatic geometry LOD (Level of Detail) adjustment for lower-end devices.

• Micro-Interaction Lens: A virtual focal point that reacts to user movement, providing a "highlight" effect on the underlying data structures.


🛠️ Technical Flexes (The "Senior" Details)

• Custom GLSL Shaders: Moved complex particle math from the CPU to the GPU using vertex shaders to achieve a stable 120 FPS.

• Modular Component Architecture: Implemented a strict separation of concerns between the Three.js rendering engine and the React UI layer.

• Optimized Asset Pipeline: Utilized code-splitting and dynamic imports to ensure a sub-1.2s Largest Contentful Paint (LCP) despite heavy 3D assets.

• Declarative Animation State: Managed complex animation timelines via Framer Motion integrated directly with the Three.js requestAnimationFrame loop.


📦 Quick Start
# Clone the repository
git clone https://github.com/YOUR_USERNAME/aura-metrics.git

# Install dependencies
npm install

# Run the development server
npm run dev


💡 Why this exists?
AuraMetrics was built to bridge the gap between abstract AI telemetry and human-centric design. It challenges the industry standard of cluttered dashboards by providing a weightless, serene environment for data observability.
