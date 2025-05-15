# Open House Manager

A simple and efficient web application for managing open house visitor sign-ins. Perfect for real estate agents who want to digitally collect and manage visitor information during open houses.

## Features

- Create and manage multiple open house properties
- Digital sign-in form for visitors
- Collect essential visitor information:
  - Name and contact details
  - Agent representation status
  - Interest in off-market listings
  - Additional comments
- View and manage visitor records
- Export visitor data to CSV format
- Mobile-responsive design optimized for tablets
- Offline-capable with local data storage

## Technology Stack

- HTML5
- CSS3 (Bootstrap 5)
- JavaScript (Vanilla)
- IndexedDB for local data storage
- Bootstrap Icons

## Getting Started

1. Clone the repository:
   ```bash
   git clone [repository-url]
   ```

2. Open the project:
   ```bash
   cd open-house-manager
   ```

3. Serve the files using a local web server. For example, using Python:
   ```bash
   python -m http.server 8000
   ```
   Or using Node.js's `http-server`:
   ```bash
   npx http-server
   ```

4. Open your browser and navigate to `http://localhost:8000` (or the appropriate port)

## Usage

1. Add a new property by clicking "Add New Property"
2. Enter the property details:
   - Property address
   - Open house date
   - Time slot
3. For each visitor:
   - Fill in their contact information
   - Record their agent status
   - Note their interest in off-market listings
   - Add any additional comments
4. View visitor records by clicking "Show Visitors"
5. Export visitor data to CSV as needed

## Data Storage

The application uses IndexedDB for local storage, which means:
- All data is stored locally in the browser
- No server required
- Works offline
- Data persists between sessions

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 