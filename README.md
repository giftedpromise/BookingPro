# BookingPro

## A Multi-Step Booking Form for Cargo Shipments

This project is a **multi-step booking form** built using **React.js** and **Tailwind CSS**. The form allows users to schedule cargo shipments, with features like input validation, dynamic pricing updates, and a fully responsive design. The **Context API** is used to manage and share state across the form's steps efficiently.

## Features

- **Multi-Step Form**: Users can easily navigate through multiple steps to book their cargo shipment.
- **Input Validation**: Ensures users enter valid data in all required fields.
- **Dynamic Pricing Updates**: Automatically adjusts pricing based on user inputs, such as shipment weight, distance, or additional services.
- **Responsive Design**: Works seamlessly across desktop, tablet, and mobile devices.
- **Global State Management**: Utilizes the Context API to share state between form steps without prop drilling.

## Technologies Used

- **React.js**: Front-end library for building the user interface.
- **Tailwind CSS**: Utility-first CSS framework for styling and responsive design.
- **Context API**: For global state management across components.

## Installation and Setup

Follow these steps to set up and run the project locally:

1. **Clone the repository**:

```bash
git clone <repo-url>
```

2.  Install dependencies: Make sure you have Node.js and npm installed, then run:
    npm install

3.  Start the development server:
    npm run dev

        State Management with Context API

    Global State: The form uses the Context API to manage data like user inputs, current step, and calculated pricing. This avoids prop drilling and keeps the codebase clean.
    Provider Setup: A context provider wraps the application, allowing all steps to access shared state.
    Usage: Components consume the context using useContext for seamless data flow.

License
This project is licensed under the MIT License. See the LICENSE file for details.
