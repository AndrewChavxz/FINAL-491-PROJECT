# Code Colony

Code Colony is an educational programming game designed to teach coding concepts through interactive gameplay. Built using HTML, CSS, JavaScript, and Google's Blockly library, the game allows players to construct visual code blocks to control a character, harvest resources, complete quests, and build a colony.

## Features

- **Visual Programming**: Uses Google's Blockly to provide a drag-and-drop coding interface. Players can use loops, conditionals, math operations, and custom commands.
- **Interactive World**: A grid-based map where players can navigate their character, gather resources (Trees and Rocks), and check the state of the environment.
- **Resource Management & Shop**: Collect resources to exchange for Gold in the Shop. Gold can be used to purchase buildings (Cabins, Houses, etc.).
- **Inventory System**: Place purchased buildings from your inventory onto the game map to expand your colony.
- **Quest System**: Complete specific challenges and objectives to earn rewards. Quests teach fundamental programming concepts while providing gameplay goals.
- **Dynamic Action Execution**: The game engine executes blocks step-by-step, allowing the character to perform real-time checks on the game world and inventory.

## How to Run

Because Code Colony is a static client-side web application, you do not need to install complex dependencies or a backend server. 

### Method 1: Direct File Open (Simplest)
1. Navigate to the project folder on your local machine.
2. Double-click on `index.html` to open it in your default web browser.

*(Note: Some browsers may restrict loading local images or scripts due to CORS policies. If you experience issues with assets not loading, please use Method 2).*

### Method 2: Local Web Server (Recommended)
Running the game via a local web server ensures all assets and scripts load correctly.

**Using VS Code:**
1. Open the project folder in Visual Studio Code.
2. Install the **Live Server** extension.
3. Right-click on `index.html` and select **"Open with Live Server"**.

**Using Python:**
If you have Python installed, you can start a simple HTTP server from your terminal or command prompt:
1. Open your terminal and navigate to the project directory:
   ```bash
   cd path/to/project
   ```
2. Run the server:
   - For Python 3: `python -m http.server`
   - For Python 2: `python -m SimpleHTTPServer`
3. Open your web browser and go to `http://localhost:8000`.

**Using Node.js:**
If you have Node.js installed, you can use `npx serve`:
1. Open your terminal and navigate to the project directory.
2. Run the command:
   ```bash
   npx serve
   ```
3. Open the local address provided in the terminal (usually `http://localhost:3000`).

## Controls

- **Manual Movement**: Use the `W`, `A`, `S`, `D` keys to move the character around the map manually (only when a script is not running).
- **Run Script**: Click the **Run** button to execute the Blockly program you have assembled.
- **Stop Script**: Click the **Stop** button to halt execution.
- **Reset**: Click the **Reset** button to return the character to the starting position and reset the execution state.
- **UI Navigation**: Use the on-screen HUD buttons to access your **Inventory**, **Quests**, and the **Shop**.
