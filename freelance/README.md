# Freelance Invoice Dashboard

A modern, responsive React application for managing freelance business operations, featuring a beautiful purple gradient design and intuitive dashboard interface.

## Features

- **Dashboard Overview**: Key metrics at a glance with interactive cards
- **Navigation**: Clean header navigation with active state indicators
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI**: Purple gradient background with clean white cards
- **Routing**: React Router for seamless page navigation

## Dashboard Metrics

- Total Clients: 12
- Active Projects: 5
- Overdue Invoices: 3
- Total Revenue (Paid): $54,320

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone or download the project files
2. Navigate to the project directory
3. Install dependencies:

```bash
npm install
```

### Running the Application

Start the development server:

```bash
npm start
```

The application will open in your browser at `http://localhost:3000`

### Building for Production

Create a production build:

```bash
npm run build
```

## Project Structure

```
src/
├── components/
│   ├── Dashboard.js          # Main dashboard component
│   ├── Dashboard.css         # Dashboard styles
│   ├── Header.js             # Navigation header
│   ├── Header.css            # Header styles
│   ├── Clients.js            # Clients page
│   ├── Projects.js           # Projects page
│   ├── Invoices.js           # Invoices page
│   ├── Payments.js           # Payments page
│   ├── Reports.js            # Reports page
│   └── PageTemplate.css      # Shared page styles
├── App.js                    # Main app component with routing
├── App.css                   # App styles
├── index.js                  # Entry point
└── index.css                 # Global styles
```

## Technologies Used

- React 18
- React Router DOM
- CSS3 (with modern features like Grid and Flexbox)
- Inter font family
- Responsive design principles

## Customization

The dashboard is designed to be easily customizable:

- **Colors**: Modify the gradient colors in `Dashboard.css`
- **Metrics**: Update the data in `Dashboard.js`
- **Navigation**: Add/remove nav items in `Header.js`
- **Styling**: Adjust spacing, fonts, and effects in the respective CSS files

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the MIT License.
