# Semester2-FinalSprint - Dog Store


Dog Store is a React application designed to provide a user-friendly interface for browsing and purchasing dog-related products. This project follows the design principles taught by Levin in UI/UX and Noman in JavaScript and React, ensuring a reasonable user experience with attention to the aesthetics of the page.

## Table of Contents

- [Design](#design)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Design

The design for the Dog Store was created using Figma, adhering to the principles of good UI/UX. The layout provides an intuitive navigation experience, and the visual elements are crafted to be aesthetically pleasing and functional.

## Features
- Home Page: Introduction to the Dog Store.
- Product List: Displays all available dog products.
- Product Detail: Detailed view of a single product.
- Cart: View and manage items in the cart.
- Checkout: Handles the checkout process.

- Proper Semantic HTML tags for accessibility.
- Well-commented code for clarity and maintainability.
- CSS and React code that closely approximates the Figma design.
- Uses React Router for navigation.
- Unit tests for key components.
- Mock JSON server for UI testing.

## Installation

1. **Clone the repository**:
```bash
git clone https://github.com/stezzly/Semester2-FinalSprint.git
cd dog-store
```
2. **Install Dependencies:** 
```bash
npm install
```

3. **Start the mock JSON server:**
```bash
npm install -g json-server
json-server --watch db.json --port 5000
```

4. **Start the React application:**
```bash
npm start
```

## Usage

1. Open your browser and navigate to `http://localhost:3000` to view the Dog Store application.
2. Browse through the products, view product details, add items to the cart, and proceed to checkout.

## Testing

1. **Run unit tests**:
   ```bash
   npm test
   ```
Unit tests are provided for the following components:

- Header
- Footer
- ProductCard

## Technologies Used

- React
- React Router
- JSON Server
- Jest (for unit testing)
- Figma (for design)
- CSS

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## License

This project is licensed under the MIT License.
