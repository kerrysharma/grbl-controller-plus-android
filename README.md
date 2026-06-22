<img width="300"  alt="Screenshot_2026-06-10-09-39-36-795_com kerry grblcontrollerplus" src="https://github.com/user-attachments/assets/d6f998e2-07ee-4779-8f1a-bb2d3a7687d9" />
<img width="300"  alt="Screenshot_2026-06-09-19-57-03-178_com kerry grblcontrollerplus" src="https://github.com/user-attachments/assets/8a8e871c-18fd-43ce-ad44-0d58054d02e5" />
<img width="300"  alt="Screenshot_2026-06-10-10-33-26-916_com kerry grblcontrollerplus" src="https://github.com/user-attachments/assets/bae157ac-2520-4f01-bedb-1272be5752f1"/>

# GRBL Controller Plus: Jog & Positioning

Take full control of your CNC machine with our precision-engineered Jogging interface, designed for workshop efficiency.

### Core Jogging Capabilities
* **Directional Control:** Navigate axes easily using the intuitive multi-directional pad.
* **Granular Step Sizes:** Select from **10mm** down to **0.01mm** for perfect positioning accuracy.
* **Speed Modulation:** Use the **Jog speed** slider to dynamically adjust movement velocity or set a custom max speed up to **5000 mm/min**.
* **Safety Toggles:** Engage **Lock Z** and **Lock diagonals** to prevent accidental axis movement during setup.

### Positioning & Visualization
* **Live Monitoring:** View **MPos** (Machine Position) and **WPos** (Work Position) in real-time.
* **Manual Overrides:** Tap any **WPos** coordinate to manually edit and re-zero your project origin.
* **Toolpath Pointer:** Toggle to the **Toolpath** tab to see your G-code projected visually, with a **real-time pointer** tracking your exact machine location.
* **Quick Commands:** Dedicated buttons to instantly home to **XY0** or **Z0** positions.

### Workshop Features
* **Spindle/Mist Control:** Seamlessly toggle spindle state (CW) and control RPM with the precision speed slider.
* **Optimized UI:** High-contrast buttons and a clean layout ensure readability in diverse workshop lighting environments.


  
<img width="300"  alt="Screenshot_2026-06-10-10-25-43-611_com kerry grblcontrollerplus" src="https://github.com/user-attachments/assets/baf201bf-760c-4218-9811-b26128e2f3a2" />
<img width="300"  alt="Screenshot_2026-06-10-09-40-25-563_com kerry grblcontrollerplus" src="https://github.com/user-attachments/assets/514607f3-7e1d-414a-a027-a2b4b840bfeb" />

# G-Code Sender & File Execution

Experience seamless CNC production with our robust G-Code sender, engineered for reliability, real-time monitoring, and optimized workflow efficiency.

### Real-Time Monitoring & Control
* **Live Toolpath Visualization:** View your G-code project visually as it executes. Watch the real-time pointer track your machine’s exact coordinates across the toolpath.
* **Production Metrics:** Keep track of your project status with dedicated displays for **Run Time**, **Last Run** duration, and precise line-by-line execution counts.
* **Responsive Playback:** Large, touch-friendly **Play** and **Stop** buttons ensure safe and reliable control, even when wearing workshop gloves.

### Advanced Feed & Power Overrides
* **Dynamic Adjustments:** Fine-tune your **Feedrate** and **Spindle/Laser Power** on the fly. Use the quick-step buttons to adjust by **+/- 1%** or **+/- 10%** instantly.
* **Persist Mode (Production Essential):** Enable the **Persist toggle** to automatically save your override settings. The app will remember and re-apply these exact parameters every time you replay the file, significantly streamlining batch production and repetitive jobs.
* **Coolant & Spindle Management:** Easily toggle **Flow**, **Mist**, and **Spindle** states directly from the execution screen.

### Reliable Backend Processing
* **Automatic Error Correction:** The app features an intelligent background process that detects and resolves common GRBL errors automatically, ensuring your job continues without unexpected interruptions for a smoother, professional experience.

<img width="300"  alt="Screenshot_2026-06-09-20-50-05-285_com kerry grblcontrollerplus" src="https://github.com/user-attachments/assets/f0ce96e1-010b-496c-8817-ab579f0ff79d" />
<img width="300"  alt="Screenshot_2026-06-10-10-26-58-585_com kerry grblcontrollerplus" src="https://github.com/user-attachments/assets/c3c0c90b-90ca-4f2a-9e96-239db8dee608" />
<img width="300"  alt="Screenshot_2026-06-10-10-27-37-319_com kerry grblcontrollerplus" src="https://github.com/user-attachments/assets/f6cad950-e36c-4668-9941-1869fbf4310f" />

# 3D Toolpath Viewer: Precision Visualization

Gain full confidence in your CNC projects with our integrated 3D Toolpath Viewer. Designed for clarity and performance, it allows you to inspect your G-code before and during execution.

### Key Visualization Features
* **Real-Time Rendering:** Watch your G-code project come to life with a high-fidelity 3D rendering of the toolpath.
* **Interactive Views:** Easily toggle between standard perspectives, including Top, Front, Right, and ISO (Isometric) views to check your geometry from every angle.
* **Smart Navigation:** Use the Fit command to instantly frame your entire design within the viewing area, ensuring nothing is missed.
* **Customizable Overlays:** Toggle the Grid and Axes indicators on or off for a cleaner view or to verify project orientation relative to your machine’s coordinate system.
* **Performance-Optimized:** Handles complex G-code files with ease; the viewer displays both raw point counts and simplified geometry for smooth performance even on large files.

### Workflow Integration
* **Pre-Flight Inspection:** Visualize the complete toolpath before you start, allowing you to catch errors or positioning issues early.
* **Live Status:** Stay informed with clear indicators showing project file names and dimension totals (X, Y, Z) at the top of the screen.

  <img width="300"  alt="Screenshot_2026-06-10-10-32-37-249_com kerry grblcontrollerplus" src="https://github.com/user-attachments/assets/85b38150-4d26-427b-9c79-1974f799151b" />

## Integrated Toolpath Sketcher: CAD on the Go
Design simple projects directly on your Android device.

* **2D CAD Tools:** Create designs from scratch using an easy-to-use sketching interface (lines, circles, custom shapes).
* **Instant G-Code:** Convert designs into G-code with a single tap.
* **No PC Required:** Perfect for quick, "right now" projects and instant prototyping.
* **Future-Ready:** Advanced 3D features are currently in development.

<img width="300"  alt="Screenshot_2026-06-10-10-28-58-004_com kerry grblcontrollerplus" src="https://github.com/user-attachments/assets/cb20b16b-0310-4ea0-812d-f227d98676e3" />

# Integrated G-Code Editor

Take complete control over your CNC projects with our built-in **G-Code Editor**, designed for quick modifications and on-the-spot adjustments without needing a computer.

### Key Editing Features
* **Syntax Highlighting:** The editor features color-coded syntax for easy reading—distinct colors for **Rapid moves**, **Z moves**, **G-Code commands**, **M-Code commands**, and **Comments**.
* **Direct File Modification:** Open, edit, and save your `.nc` files directly within the app. Whether you need to adjust feed rates or fix a coordinate, you can do it instantly.
* **Line Counting & Navigation:** Keep track of your code structure with clear line numbering, making it easy to locate and edit specific sections of your toolpath.
* **Streamlined Production:** Avoid tedious file transfers. Make your changes in seconds, save, and proceed directly to the **File Play** screen to start your job.

### Why the G-Code Editor is Essential
* **Instant Corrections:** Spot an error or need a minor tweak while at the machine? Fix it in real-time.
* **Workshop Mobility:** Removes the dependency on a PC for G-code refinement, allowing for a truly mobile, stand-alone CNC workflow.
* **Optimized for Clarity:** Designed for readability, ensuring you can quickly identify and edit parameters even on a mobile display.

<img width="300"  alt="Screenshot_2026-06-10-10-33-48-670_com kerry grblcontrollerplus" src="https://github.com/user-attachments/assets/49096469-882d-4e30-8ee4-641380faa1f7" />
<img width="300"  alt="Screenshot_2026-06-10-10-34-39-594_com kerry grblcontrollerplus" src="https://github.com/user-attachments/assets/546c6e4f-47ba-4758-b629-3c90c2ad69bd" />
