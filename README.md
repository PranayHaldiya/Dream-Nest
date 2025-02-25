# Dream-Nest 🏠

Dream-Nest is a modern property rental and management platform built with Next.js, TypeScript, and MongoDB. It provides a seamless experience for both property owners and tenants.

## Features ✨

### For Property Owners
- Create and manage property listings with detailed information
- Upload multiple high-quality images for each property
- Track booking requests and manage reservations
- View earnings and booking history
- Real-time availability calendar
- Property analytics dashboard

### For Tenants
- Search properties with advanced filters (location, price, amenities)
- View detailed property information and high-resolution images
- Real-time booking system
- Secure payment processing
- Review and rating system
- Favorite properties feature
- Booking history and upcoming stays

## Tech Stack 🛠️

- **Frontend:** Next.js 13, TypeScript, Tailwind CSS
- **Backend:** Next.js API Routes
- **Database:** MongoDB with Mongoose
- **Authentication:** NextAuth.js
- **Image Storage:** Cloudinary
- **Payments:** Stripe
- **Maps:** Leaflet
- **Forms:** React Hook Form
- **State Management:** Zustand
- **Styling:** Tailwind CSS, shadcn/ui

## Getting Started 🚀

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/dream-nest.git
   cd dream-nest
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory with:
   ```
   DATABASE_URL=your_mongodb_url
   NEXTAUTH_SECRET=your_secret
   NEXTAUTH_URL=http://localhost:3000
   GITHUB_ID=your_github_id
   GITHUB_SECRET=your_github_secret
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret
   NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=your_cloudinary_name
   STRIPE_SECRET_KEY=your_stripe_secret_key
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

## Contributing 🤝

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License 📝

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments 🙏

- Thanks to all contributors who helped in building this project
- Special thanks to the open-source community for providing amazing tools and libraries

## Contact 📬

Your Name - [@yourusername](https://twitter.com/yourusername)

Project Link: [https://github.com/yourusername/dream-nest](https://github.com/yourusername/dream-nest)
