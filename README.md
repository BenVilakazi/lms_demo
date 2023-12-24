LMS (Learning Management System) clone using Clerk for authentication, Next.js 14, UploadThing for file uploads, and Stripe for payment integration:

# LMS Clone

This is an LMS clone built with Next.js 14, Clerk, UploadThing, and Stripe.
 
## Features

- User authentication using Clerk
- Course management
- Lesson management
- File uploads using UploadThing
- Payment integration with Stripe

## Prerequisites

Before running the application, make sure you have the following installed:

- Node.js
- npm or yarn
- Clerk account  (https://www.clerk.dev/)
- Stripe account  (https://stripe.com/)

## Installation

1. Clone the repository:

 ```bash
 git clone https://github.com/benvilakazi/lms_demo.git
 ```
 
2. Navigate to the project directory:

```bash
 cd lms-clone 
``` 
3. Install dependencies:
```bash
     npm install
 ```  
4. Create a   .env  file in the project root and add the following environment variables:
```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

MUX_TOKEN_ID=
MUX_TOKEN_SECRET=

STRIPE_API_KEY=
NEXT_PUBLIC_APP_URL=http://localhost:3000
STRIPE_WEBHOOK_SECRET=

NEXT_PUBLIC_TEACHER_ID=
```   
6. Start the development server:

     npm run dev
   
7. Open your browser and navigate to   http://localhost:3000    to access the application.

## Usage

1. Sign up or log in using Clerk authentication.
2. Create courses and lessons.
3. Upload files for lessons using UploadThing.
4. Enable payment for courses using Stripe integration.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [Next.js] (https://nextjs.org/)
- [Clerk] (https://www.clerk.dev/)
- [UploadThing] (https://uploadthingy.com/)
- [Stripe] (https://stripe.com/)

That's it! You now have an LMS clone using Clerk for authentication, Next.js 14, UploadThing for file uploads, and Stripe for payment integration. Feel free to customize the README and the application as per your requirements.

Let me know if there's anything else I can help you with!
