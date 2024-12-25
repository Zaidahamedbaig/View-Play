# online video explorer

completely developed website by using  backend

-[Model link](https://app.eraser.io/workspace/YtPqZ1VogxGy1jzIDkzj)


# ViewPlay

ViewPlay is a platform designed to explore the world online. It is a comprehensive solution featuring both frontend and backend development for a seamless user experience.

## Features
- Secure user authentication using `bcrypt` and `jsonwebtoken`.
- Media management with `cloudinary` and `multer`.
- Cross-origin support via `cors`.
- Robust data handling and storage using `mongodb` and `mongoose`.

## Getting Started

### Prerequisites
- Node.js (>=16.20.1)
- MongoDB database

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd viewplay
   
2. Install dependencies:
      npm install

4. Create a .env file in the project root and configure the required environment variables:
      PORT=3000
      MONGODB_URI=your_mongodb_uri
      JWT_SECRET=your_secret_key
      CLOUDINARY_URL=your_cloudinary_url
   
5. Run the application in development mode:
      npm run dev
