# PutMeInDior: Threat Intelligence & Geospatial Visualization

![PutMeInDior Preview](https://github.com/user-attachments/assets/placeholder-image.png)

## ⚠️ Problem Statement
Traditional disaster monitoring systems often lack the spatial depth and real-time interactive context required for effective emergency response. When dealing with dynamic threats like floods and landslides, stakeholders need more than just static markers on a flat map; they require an immersive, high-resolution visualization that bridges the gap between global trends and hyper-local impact.

## 🚀 Solution & Features
**PutMeInDior** is a next-generation geospatial dashboard designed to visualize environmental threats with cinematic precision. By combining planetary-scale data with the 3D rendering power of CesiumJS, it provides:

*   **🏙️ 3D Urban Simulation**: High-fidelity 3D modeling of environments using OSM Buildings with custom GLSL shaders for emissive glow and depth-aware transparency.
*   **📡 Dynamic Threat Intelligence**: Interactive visualization of flood and landslide hotspots using probabilistic modeling and multi-factor driver analysis (Rainfall, Slope, Soil Wetness).
*   **🗺️ Animated Evacuation Mapping**: Real-time pathfinding interpolation that visualizes precise evacuation routes from impact zones to safe havens.
*   **🌍 Global-to-Local Narrative**: A seamless transition experience from an interactive 3D globe (Cobe) to a high-detail regional dashboard.
*   **📰 Live Intelligence Feed**: Integrated news panel and real-time ticker for tracking active MetMalaysia alerts and NADMA announcements.
*   **🖥️ Sci-Fi Operational HUD**: A premium, high-contrast interface designed for maximum situational awareness and critical data legibility.

## 🛠️ Tech Stack
*   **Framework**: [Next.js](https://nextjs.org/) (React 19)
*   **3D Geospatial Engine**: [CesiumJS](https://cesium.com/platform/cesiumjs/)
*   **Interactive Earth**: [Cobe](https://github.com/shuding/cobe)
*   **Geospatial Data**: [Google Earth Engine](https://earthengine.google.com/)
*   **Styling**: [Tailwind CSS 4](https://tailwindcss.com/)
*   **Iconography**: [Lucide React](https://lucide.dev/)
*   **Engine Tools**: D3-geo, TopoJSON, World Atlas

## 🛤️ User Flow
1.  **Phase I: Planetary Intro**: Landing on a minimalist, interactive 3D Earth to establish global context.
2.  **Phase II: Geographic Selection**: Transitioning to a topological world map to pinpoint regional interests.
3.  **Phase III: Operational Dashboard**: Entry into the 3D Command & Control center focused on Malaysia.
4.  **Phase IV: Threat Analysis**: Interactive probing of tactical markers to reveal underlying environmental stressors.
5.  **Phase V: Response Execution**: Generation of animated evacuation routes for active threat mitigation.

## 🚥 Getting Started

### Prerequisites
*   **Node.js**: version 20.x or higher
*   **Cesium ION**: A valid access token for 3D tilesets

### Installation
1.  **Clone the repository**:
    ```bash
    git clone https://github.com/username/putmeindior.git
    cd putmeindior
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    ```

3.  **Environment Setup**:
    Create a `.env.local` file in the root directory:
    ```env
    NEXT_PUBLIC_CESIUM_ION_TOKEN=your_cesium_ion_token_here
    ```

4.  **Deployment**:
    ```bash
    npm run dev
    ```

## 📜 Available Scripts
*   `npm run dev`: Boots the development environment and syncs Cesium assets.
*   `npm run build`: Compiles the optimized production application.
*   `npm run lint`: Executes ESLint for code quality assurance.
*   `npm run postinstall`: Automatic utility to maintain Cesium asset integrity in the public directory.

---
Built with ❤️ for Geospatial Excellence.
