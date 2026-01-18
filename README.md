🏢 Org Chart Light
A lightweight organizational chart builder and viewer that runs entirely in your browser. It’s designed for teams that need a quick, no-fuss way to visualize their hierarchy without the overhead of complex HR software or heavy frameworks.

✨ What makes it "Light"?
Zero Dependencies: No React, No D3, no external libraries. It’s just one file that works instantly.

Minimal Setup: Just open the HTML file and start building. No installation or command line required.

Standalone Publishing: Create a "read-only" version of your chart to share with others. It embeds your data and logo into a single portable file.

Fast & Local: All data stays in your browser. Save and load your hierarchy using simple JSON files.

🛠️ Features
Simple Editor: Click any card to update details; hover to add or remove team members.

Drag-and-Drop: Easily reorganize reporting lines by dragging cards to new managers.

Search & Filter: Quickly find people by name, or filter the view by Role, Location, or Skill Tags.

Dark & Light Modes: Easy on the eyes, no matter your preference.

Customizable: Set your own list of roles, locations, and tags via the settings gear.

🚀 Getting Started
Use it immediately
Clone the repository:

Bash

git clone https://github.com/steveashort/orgchart.git
Open index.html in your favorite web browser.

How to manage data
To Save: Click "Save Hierarchy" in the sidebar. This downloads a .json file of your current chart.

To Load: Click "Load Hierarchy" and select your previously saved JSON file.

To Share: Click "Publish to Read-Only". This generates a standalone HTML file that you can email to your team or host internally.

📄 Data Format
If you prefer to edit the data manually or generate it via script, the app uses a straightforward nested JSON structure:

JSON

{
  "id": "root-1",
  "name": "John Smith",
  "role": "Lead",
  "location": "Remote",
  "tags": ["Strategy"],
  "children": [
    {
      "id": "n123",
      "name": "Jane Doe",
      "role": "Contributor",
      "children": []
    }
  ]
}
⚖️ License
This project is open-source and available under the MIT License.
