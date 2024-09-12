# Custom Phone Case Shop

A Next.js application for creating and ordering custom phone cases.

## Features

- Upload and customize images for phone cases
- Support for various iPhone models
- Real-time case preview
- User authentication
- Responsive design

## Tech Stack

- Next.js 14
- React 18
- TypeScript
- Tailwind CSS
- Prisma
- PostgreSQL
- Uploadthing for image uploads
- Kinde for authentication

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn
- PostgreSQL database

### Installation

1. Clone the repository:

   ```
   git clone https://github.com/0xtomotech/custom_phone_case_shop.git
   cd custom_phone_case_shop
   ```

2. Install dependencies:

   ```
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add the following:

   ```
   DATABASE_URL="your_postgresql_connection_string"
   UPLOADTHING_SECRET="your_uploadthing_secret"
   UPLOADTHING_APP_ID="your_uploadthing_app_id"
   KINDE_CLIENT_ID="your_kinde_client_id"
   KINDE_CLIENT_SECRET="your_kinde_client_secret"
   KINDE_ISSUER_URL="your_kinde_issuer_url"
   ```

4. Run database migrations:

   ```
   npx prisma migrate dev
   ```

5. Start the development server:

   ```
   npm run dev
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

- `/src/app`: Next.js app router pages and API routes
- `/src/components`: Reusable React components
- `/src/lib`: Utility functions and shared logic
- `/prisma`: Database schema and migrations

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
