# Universe (Frontend)

A modern, feature-rich monorepo for Universe's social networking platform and admin dashboard built with Turborepo.

## 🌟 Overview

Universe is a comprehensive social networking platform that consists of two main applications:

- **Name**: TarsUniverse
- **Version**: 1.0
- **Homepage**: [TarsUniverse](tarsuniverse.com)
- - **Admin**: [TarsUniverseAdmin](admin.tarsuniverse.com)
- **Social Network**: A feature-rich social platform for users to connect, share, and interact
- **Admin Dashboard**: A powerful administrative interface for platform management

## 🚀 Tech Stack

- **Build Tool**: [Turborepo](https://turbo.build/) + [Vite](https://vitejs.dev/)
- **Frontend Framework**: [React](https://reactjs.org/) with TypeScript
- **State Management**: [Redux](https://redux.js.org/) + [Redux Thunk](https://github.com/reduxjs/redux-thunk)
- **Styling**: [TailwindCSS](https://tailwindcss.com/)
- **Form Management**: [Formik](https://formik.org/) + [Yup](https://github.com/jquense/yup)
- **Testing**: [Jest](https://jestjs.io/) + [React Testing Library](https://testing-library.com/react)
- **Package Manager**: [pnpm](https://pnpm.io/)
- **HTTP Client**: [Axios](https://axios-http.com/)

## 📦 Project Structure

```bash
universe/
├── apps/
│   ├── admin/        # Admin dashboard application
│   └── social-network/       # Social network application
├── packages/         # Shared packages and utilities
├── turbo.json       # Turborepo configuration
└── pnpm-workspace.yaml
```

## ✨ Features

### Social Network Application

- **Authentication**: Complete user authentication flow
- **Feed & Posts**: Dynamic content creation and interaction
- **Profile Management**: Comprehensive user profile system
- **Real-time Messaging**: Instant messaging capabilities
- **Connections**: User networking and relationship management
- **Notifications**: Real-time activity notifications
- **Market**: Product showcase and interaction
- **Settings**: User preferences and account management
- **Wallet**: Financial transactions and management

### Admin Dashboard

- **User Management**: Monitor and manage platform users
- **Content Moderation**: Review and regulate user-generated content
- **Analytics**: Platform performance metrics and insights
- **System Security**: Platform security management
- **Financial Management**: Transaction oversight
- **Support System**: User feedback and support management

### Functional Modules

1. **Authentication**

   - Sign Up
   - Sign In
   - Email Verification
   - OTP Verification
   - Change Password
   - Reset Password

2. **Home**

   - **Feed**: Browse posts from users.
   - **Create Card**: Quick access to create posts.
   - **Content Interactions**: Like, comment, share, edit, and delete posts.
   - **Connection Interactions**: Manage connections directly from the feed.
   - **Widgets**: Left-side shortcuts and right-side features for enhanced navigation.

3. **Profile Management**

   - **Profile Information**: Update personal details, education, and skills.
   - **Connections & Followers**: View and manage your network.
   - **Categorized Content**: Filter posts by categories like technology, lifestyle, etc.
   - **Create Card**: Quick post creation directly from the profile.
   - **Content Timeline**: Chronological view of posts.
   - **About Me Section**: Display bio, education, experience, and more.

4. **Connections**

   - **Suggested Connections**: Discover people you may know.
   - **Requested Connections**: Manage incoming connection requests.
   - **Connected**: View your active connections.

5. **Settings**

   - **General Information**: Update account settings and preferences.

6. **Notifications**

   - **Real-Time Updates**: Alerts for likes, comments, shares, connection requests, and messages.

7. **Messages**

   - **Chat**: Send and receive messages in real-time.
   - **Active Status**: Show online presence.
   - **Manage Conversations**: Clear, block, delete, or report chats.

8. **Search**

   - **Search Users, Investors, Pages, Communities, Groups**: Comprehensive search functionality.

9. **Menu**

   - **Shortcuts**: Quick links to key sections.
   - **Market**: Access products and services.
   - **Events**: Stay updated on community events.
   - **Pages**: Manage or explore various pages.
   - **Settings & Privacy**: Manage account privacy.
   - **Logout**: Securely exit the platform.

10. **Market**

    - **Catalog**: Explore product offerings.
    - **Product Category**: Filter items by type.
    - **Product Purchase**: Buy products seamlessly.
    - **Interaction**: Save, love, review, and share products.

11. **Admin Panel**

    - **Authentication**: Secure admin access.
    - **Home**: Overview of admin activities.
    - **User Management**: Monitor and manage platform users.
    - **Content Management**: Review and regulate user-generated content.
    - **Product Management**: Oversee marketplace operations.
    - **Analytics & Insights**: Track platform performance metrics.
    - **Advertising Management**: Handle advertisements and promotions.
    - **Marketplace Management**: Manage product listings and transactions.
    - **Wallet & Payment Tracking**: Supervise financial activities.
    - **System Maintenance & Logs**: Ensure platform stability and log integrity.
    - **Message & Notification Management**: Oversee communications.
    - **Groups & Communities Management**: Regulate community activities.
    - **Page Management**: Monitor and verify official pages.
    - **Financial Management**: Oversee transactions and revenue.
    - **AI & Automation**: Implement intelligent features.
    - **Development & Maintenance**: Ensure the platform's growth and stability.
    - **Feedback & Support**: Manage user support and suggestions.
    - **System Security**: Safeguard the platform from vulnerabilities.

12. **Create Pages**

    - **Project Pages**: Enable users to create dedicated project pages.
    - **Startup Pages**: Support the creation of startup-focused pages.
    - **Investment & Official Pages**: Allow users to build investment and official pages.

13. **Page Setup & Personalization**

    - **Customization**: Personalize page layouts and features.
    - **Verification**: Allow page owners to verify their authenticity.

14. **Page Management**

    - **Review Pages**: Authenticate and monitor compliance of pages.
    - **Compliance Monitoring**: Ensure adherence to platform policies for startups and investments.

15. **Wallet**

    - **Authentication**: Secure wallet access.
    - **Home**: Overview of wallet features.
    - **Cash Out**: Withdraw funds securely.
    - **Send Money**: Transfer money to other users.
    - **Purchase**: Buy products and services.
    - **Dashboard**: Financial overview.
    - **Analytics & Reporting**: Detailed insights into wallet usage.
    - **Security & Privacy**: Ensure transactions are safe.
    - **Feedback Management**: Handle wallet-related support.
    - **Marketing & Advertisements**: Promote wallet features.

16. **Reels**
    - **Video**: Infinite user custom based video suggestions.
    - **Media Player**: A dedicated media player.

## 🛠️ Development Setup

### Prerequisites

- Node.js (v16 or higher)
- pnpm (v8 or higher)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/universe.git
cd universe
```

2. Install dependencies:

```bash
pnpm install
```

3. Start development server:

```bash
# Run all applications
pnpm dev

# Run specific application
pnpm dev --filter=social
pnpm dev --filter=admin
```

### Building

```bash
# Build all applications
pnpm build

# Build specific application
pnpm build --filter=social
pnpm build --filter=admin
```

### Testing

```bash
# Run all tests
pnpm test

# Run tests with coverage
pnpm test:coverage
```

## 📝 Scripts

- `pnpm dev`: Start development servers
- `pnpm build`: Build all applications
- `pnpm test`: Run test suites
- `pnpm lint`: Run linting
- `pnpm format`: Format code with Prettier

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🙏 Acknowledgments

- Thanks to all contributors who have helped shape Universe
- Built with [Turborepo](https://turbo.build/)
- Powered by [React](https://reactjs.org/)
