# Synapse - Visual Mind Mapping Tool

**Version:** 0.1.7  
**Designed by:** [Samolevsky.com](https://samolevsky.com/)

## Overview

Synapse is a powerful, browser-based visual thinking tool that helps you organize ideas, brainstorm concepts, and create beautiful interactive diagrams. Perfect for planning projects, taking notes, or exploring complex topics with an intuitive drag-and-drop interface.

## Key Features

- **Unlimited Nodes & Connections** - Create as many nodes and connections as you need
- **Multiple Connection Styles** - Choose from curved, straight, orthogonal, rounded, and smooth connection lines
- **Flexible Line Patterns** - Solid, dashed, dotted, arrow, and reverse arrow patterns
- **Customizable Appearance** - Adjust colors, themes, opacity, stroke thickness, and more
- **Rich Text Notes** - Add detailed notes to nodes with formatting support
- **Export & Import** - Save and load entire projects as JSON files
- **Image Export** - Export your mind maps as PNG or SVG files
- **Auto-Save** - Your work is automatically saved to browser local storage
- **Multi-Selection** - Select and manipulate multiple nodes at once
- **Zoom & Pan Controls** - Navigate large mind maps with ease
- **Dark & Light Themes** - Switch between themes for comfortable viewing
- **Grid Options** - Choose from dot grid, square grid, or no grid
- **Search Functionality** - Quickly find nodes by searching their text
- **Fullscreen Mode** - Focus on your work without distractions

---

## Getting Started

### Opening the Application

1. Open `index.html` in a modern web browser (Chrome, Firefox, Safari, or Edge recommended)
2. The application will load with a default mind map structure
3. Your work is automatically saved to your browser's local storage

### Basic Concepts

- **Nodes**: The building blocks of your mind map - boxes containing text
- **Connections**: Lines that link nodes together to show relationships
- **Canvas**: The workspace where you create and organize your mind map

---

## Step-by-Step User Guide

### 1. Creating and Managing Nodes

#### Adding a New Node
- **Method 1**: Click on an existing node, then click the green **+** button that appears in the top-right corner
- **Method 2**: Select a node and click the **Add Child Node** button in the floating panel at the bottom
- **Method 3**: Hover over a connection line and click the green **+** button to insert a node between two connected nodes

#### Editing Node Text
- **Double-click** on any node to enter edit mode
- Type your text and press **Enter** to save
- Press **Escape** to cancel editing

#### Moving Nodes
- **Click and drag** any node to reposition it on the canvas
- Selected nodes will show a white outline
- Multiple nodes can be moved together (see Multi-Selection below)

#### Deleting Nodes
1. Click on a node to select it
2. Click the **Delete** button (trash icon) in the floating panel at the bottom
3. Confirm the deletion when prompted

### 2. Working with Connections

#### Creating Connections
1. Select a node by clicking on it
2. Click the **Connect** button (link icon) in the floating panel
3. Click on another node to create a connection between them

#### Deleting Connections
- **Method 1**: Select a node that has connections, click the **Disconnect** button (broken link icon) in the floating panel, then click on a connected node to remove that specific connection
- **Method 2**: Click directly on a connection line to select it (it will glow brighter), then press **Delete** or **Backspace** to remove it

#### Customizing Connection Appearance
Open the **Settings** panel (gear icon in the top-right) and navigate to **Connection Properties**:

- **Line Color**: Choose from multicolor, gradient, or single color
- **Line Style**: Arc, straight, right-angled, rounded right-angled, or smooth curves
- **Line Pattern**: Solid, dashed, dotted, arrow, or reverse arrow
- **Stroke Thickness**: Adjust line width (1-8 pixels)
- **Opacity**: Control connection transparency (0-1)

### 3. Adding Notes to Nodes

1. Select a node by clicking on it
2. Click the **Note** button (document icon) in the floating panel
3. A rich text editor will open where you can:
   - Type formatted text
   - Create bulleted or numbered lists
   - Add bold, italic, or underlined text
   - Insert links
   - Add code blocks
4. Click **Save** to attach the note to the node
5. Nodes with notes display a small orange indicator dot

### 4. Multi-Selection

#### Selecting Multiple Nodes
- **Method 1**: Hold **Shift** and click on multiple nodes
- **Method 2**: Click and drag on the canvas to create a selection box (marquee)
- **Method 3**: Hold **Ctrl** (or **Cmd** on Mac) and click nodes to add/remove from selection

#### Selecting Multiple Connections
- **Method 1**: Hold **Shift** and click on multiple connections
- **Method 2**: Hold **Shift** and drag a selection box (marquee) over connections to select them

#### Working with Multiple Nodes
- Drag any selected node to move all selected nodes together
- Use the floating panel buttons to perform actions on all selected nodes
- Press **Escape** to deselect all nodes

### 5. Navigation and View Controls

#### Zoom Controls
- **Zoom In**: Click the magnifying glass with **+** icon in the toolbar
- **Zoom Out**: Click the magnifying glass with **-** icon in the toolbar
- **Mouse Wheel**: Scroll up to zoom in, scroll down to zoom out
- **Trackpad**: Pinch to zoom in/out

#### Panning the Canvas
- **Click and drag** on empty canvas space to pan around
- **Two-finger drag** on trackpad to pan

#### Reset View
- Click the **Reset View** button (circular arrow icon) to return to the default zoom and position

#### Fullscreen Mode
- Click the **Fullscreen** button (expand icon) in the toolbar
- Press **Escape** or click the button again to exit fullscreen

### 6. Searching for Nodes

1. Open the **Settings** panel (gear icon)
2. In the **Search Nodes** section, type your search query
3. Matching nodes will be highlighted with a pulsing blue glow
4. The search results count shows how many nodes match
5. Click the **X** button to clear the search

**Keyboard Shortcut**: Press **Ctrl+F** (or **Cmd+F** on Mac) to focus the search box

### 7. Customizing Appearance

#### Changing Node Properties
In the Settings panel under **Node Properties**:
- **Border Radius**: Adjust the roundness of node corners (0-20)

#### Adjusting Grid Display
In the Settings panel under **View Options**:
- **Grid Style**: Choose dot grid, square grid, or no grid
- **Grid Opacity**: Control grid visibility (0-1)

#### Switching Themes
- Click the **Theme** button (sun/moon icon) in the toolbar
- Toggle between light and dark themes
- Your preference is saved automatically

### 8. Saving and Loading Projects

#### Auto-Save
- Your work is automatically saved to browser local storage
- Changes are saved in real-time as you work
- No manual save action required

#### Exporting a Project
1. Open the **Settings** panel
2. Navigate to **Data Management**
3. Click **Export Project**
4. A JSON file will be downloaded containing your entire mind map

#### Importing a Project
1. Open the **Settings** panel
2. Navigate to **Data Management**
3. Click **Import Project**
4. Select a previously exported JSON file
5. Your mind map will be loaded (this will replace your current work)

#### Clearing All Data
1. Open the **Settings** panel
2. Navigate to **Data Management**
3. Click **Clear All Saved Data** (red button)
4. Confirm the action to delete all saved data from browser storage

### 9. Exporting Images

#### Export as PNG
1. Open the **Settings** panel
2. Navigate to **Export Options**
3. Click **Export as PNG**
4. A high-quality PNG image of your mind map will be downloaded
5. Ideal for presentations, documents, and sharing

#### Export as SVG
1. Open the **Settings** panel
2. Navigate to **Export Options**
3. Click **Export as SVG**
4. A scalable vector graphic file will be downloaded
5. Perfect for editing in design tools and maintaining quality at any size

---

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| **Ctrl+F** (Cmd+F on Mac) | Focus search box |
| **Double-click** node | Edit node text |
| **Enter** | Save node text while editing |
| **Escape** | Cancel editing / Deselect all |
| **Shift+Click** | Multi-select nodes |
| **Ctrl+Click** (Cmd+Click on Mac) | Add/remove node from selection |
| **Delete** / **Backspace** | Delete selected node(s) or connection |
| **Click** on connection line | Select connection for deletion |
| **Mouse Wheel** | Zoom in/out |

---

## Tips and Best Practices

1. **Start Simple**: Begin with a central idea and branch out gradually
2. **Use Colors**: Customize connection colors to categorize relationships
3. **Add Notes**: Use the notes feature to add detailed information without cluttering the visual
4. **Regular Exports**: Export your projects periodically as backup files
5. **Organize Spatially**: Arrange related nodes close together for better visual clarity
6. **Experiment with Styles**: Try different connection styles to find what works best for your use case
7. **Use Multi-Selection**: Select multiple nodes to reorganize large sections quickly
8. **Search Feature**: Use search to quickly locate specific nodes in large mind maps

---

## Browser Compatibility

Synapse works best on modern browsers:
- ✅ Google Chrome (recommended)
- ✅ Mozilla Firefox
- ✅ Safari
- ✅ Microsoft Edge
- ✅ Opera

**Note**: Internet Explorer is not supported.

---

## Data Storage

- All data is stored locally in your browser's local storage
- No data is transmitted to external servers
- Your privacy is protected - your mind maps stay on your device
- Clearing browser data will delete your saved mind maps (export regularly!)

---

## Troubleshooting

### My work disappeared
- Check if you accidentally cleared browser data
- Try importing a previously exported project file
- Ensure you're using the same browser where you created the mind map

### Nodes won't move
- Make sure you're not in edit mode (double-click exits edit mode)
- Try refreshing the page
- Check if the node is selected (should have a white outline)

### Export not working
- Ensure pop-ups are not blocked in your browser
- Try a different browser
- Check that you have write permissions in your downloads folder

### Performance issues with large mind maps
- Try reducing the number of visible connections
- Disable grid display for better performance
- Use a more powerful device or close other browser tabs


---

## Contact & Support

For questions, feedback, or support:
- Visit: [Samolevsky.com](https://samolevsky.com/)
- Discover more design tools and resources

---



Enjoy creating with Synapse! 🧠✨
