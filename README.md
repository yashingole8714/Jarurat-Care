# Patient Records Dashboard - Jarurat Care

A modern, responsive React application for managing patient records, built as an internship assignment for Jarurat Care.

## Features

- **Landing Page**: Beautiful hero section with company branding and navigation
- **Patient Management**: View, search, and manage patient records
- **Search Functionality**: Filter patients by name in real-time
- **Detailed Patient View**: Modal displaying comprehensive patient information
- **Add New Patient**: Form to add new patient records locally
- **Responsive Design**: Mobile-first design using Tailwind CSS
- **Loading & Error States**: Smooth user experience with proper feedback
- **Modern UI**: Clean, professional interface with gradient accents

## Tech Stack

- **React 18** with TypeScript
- **Vite** for fast development and building
- **Tailwind CSS** for styling
- **Lucide React** for icons
- **React Hooks** (useState, useEffect) for state management

## Project Structure

```
src/
├── components/          # Reusable components
│   ├── Header.tsx       # Navigation header
│   ├── PatientCard.tsx  # Patient card component
│   ├── SearchBar.tsx    # Search input component
│   ├── Modal.tsx        # Patient details modal
│   └── AddPatientForm.tsx  # Add patient form
├── pages/              # Page components
│   ├── Home.tsx        # Landing page
│   ├── Patients.tsx    # Main patients page
│   └── About.tsx       # About page
├── data/               # Mock data
│   └── patients.json   # Patient records
├── App.tsx             # Main app component with routing
└── main.tsx           # App entry point
```

## Installation & Setup

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Steps

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd project
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open in browser**
   Navigate to `http://localhost:5173` (or the port shown in terminal)

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
- `npm run typecheck` - Run TypeScript type checking

## Key Features Explained

### 1. Patient Search
The search bar allows real-time filtering of patients by name. Simply type in the search field to instantly filter the patient list.

### 2. View Patient Details
Click the "View Details" button on any patient card to open a modal showing complete patient information including:
- Name and Age
- Contact information
- Email and Address
- Blood Group
- Medical History
- Last Visit Date

### 3. Add New Patient
Click the "Add New Patient" button to open a form where you can add new patient records. The data is stored locally in the application state.

### 4. Responsive Design
The application is fully responsive and works seamlessly on:
- Mobile devices (320px+)
- Tablets (768px+)
- Desktops (1024px+)

## Mock Data

Patient data is stored in `src/data/patients.json` and includes 10 sample patient records with realistic Indian names and locations.

## Deployment

### Deploy to Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel`
3. Follow the prompts

Or use the Vercel GitHub integration for automatic deployments.

### Deploy to Netlify

1. Build the project: `npm run build`
2. Drag and drop the `dist` folder to [Netlify Drop](https://app.netlify.com/drop)

Or connect your GitHub repository to Netlify for automatic deployments.

## Screenshots

### Home Page
Beautiful landing page with hero section and feature highlights.

### Patients Page
Grid layout displaying all patients with search functionality.

### Patient Details Modal
Comprehensive view of patient information in an elegant modal.

### Add Patient Form
User-friendly form to add new patient records.

## Code Quality

- TypeScript for type safety
- Component-based architecture
- Reusable and maintainable code
- Clean separation of concerns
- Inline comments explaining key logic
- Consistent naming conventions
- ESLint configuration for code quality

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Future Enhancements

- Backend integration with API
- User authentication
- Data persistence with database
- Advanced filtering options
- Patient appointment scheduling
- Export patient data to PDF/Excel
- Dark mode support

## License

This project is created for educational purposes as part of an internship assignment.

## Contact

For questions or feedback, please contact: contact@jaruratcare.com

---

Built with ❤️ for Jarurat Care
