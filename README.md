
Here is a `README.md` file for the Zuuki Tracker project:

---

# Zuuki Tracker

## Project Vision
Zuuki Tracker is a PET GPS TRACKING WEBSITE aimed at creating a community of pet lovers dedicated to pet safety and well-being. The platform facilitates the quick and efficient location of lost pets and provides a marketplace for pet service providers, along with support for pet rescues in rehoming animals.

## Technology Stack
- **Frontend:** Next.js, Chakra-UI/TailwindCSS
- **Backend:** Node.js, Express
- **Database:** MongoDB, Redis
- **Payment Integration:** Stripe
- **GPS Tracking:** Traccar API
- **Notification Service:** Firebase Cloud Messaging (FCM) or Twilio

## User Roles
- **Pet Owner**
- **Pet Service Provider**
- **Pet Rescue**
- **Staff**

## Subscription Tiers

### Pet Owners
- **Free Tier:**
  - Basic access to the platform.

- **Smart Tag Tier:**
  - One-time fee for a smart tag with NFC & QR code.
  - Ability to assign the smart tag to a pet.
  - Receive notifications when the smart tag is scanned.
  - Scanners can access pet owner-specified details.

- **Premium Tier:**
  - Subscription-based with an initial one-time fee.
  - GPS tracker to view real-time location of the pet via Traccar.
  - Historical location tracking.
  - Set and receive alerts for geo-fences.
  - Mark pets as lost and share last known location.
  - View reports on pet steps and activity.
  - Participate in breed-based activity leaderboards.
  - Access to an in-app shop with discounts on pet-related products.

### Pet Service Provider
- **Paid Tier:**
  - Access to create and manage service listings (e.g., grooming, walking, veterinary).
  - Promote services to pet owners based on location and pet type.
  - Manage service bookings and communicate with pet owners.
  - Offer discounts or promotions to attract new customers.

### Pet Rescue
- **Free Access:**
  - Create profiles for pets available for adoption.
  - Manage inquiries and applications for pet adoptions.
  - Schedule meetings between potential adopters and pets.
  - Collaborate with the community to help locate lost pets.
  - List found pets and attempt to reunite them with owners.
  - Promote dogs and cats in urgent need of adoption to all users.
  - Access to discounts on pet-related products through the in-app shop.
  - Earn points by facilitating adoptions or helping locate lost pets and exchange them for discounts or products in the in-app shop.

## Core Features

### Pet Owner
- **Add a Pet:**
  - Input pet details (name, breed, age, etc.).
  - Assign smart tag or GPS tracker to the pet.
  - Update pet profile information.

- **Pet Management:**
  - View pet's real-time location (Premium).
  - Access historical location data (Premium).
  - Set geo-fences and receive alerts (Premium) through Traccar API.
  - Mark pet as lost and notify community.
  - Receive notifications when the pet is found.
  - Access activity reports and leaderboards (Premium).

- **Smart Tag Management:**
  - Assign smart tag to a pet.
  - Update contact and pet information linked to the tag.
  - Receive notifications when the smart tag is scanned, with scan location and time.

- **Lost Pet Notification:**
  - Mark pet as lost and manually select the last known location if no GPS tracker.
  - Notify users in the area if allowed by the pet owner.

- **In-App Shop:**
  - Browse and purchase pet-related products.
  - Receive discounts on products (Premium).
  - View and manage order history.
  - Redeem points earned through the reward system.

- **Reward System:**
  - Earn points by finding lost pets or helping other users.
  - Exchange points for discounts or products in the in-app shop.

- **Subscription Management:**
  - View and manage subscription plans.
  - Upgrade or downgrade subscription tiers.
  - Manage payment information and billing history via Stripe.

### Pet Service Provider
- **Service Listings:**
  - Create and manage service listings (e.g., grooming, walking, veterinary).
  - Provide details about services, pricing, and availability.

- **Target Audience Engagement:**
  - Promote services to pet owners based on location and pet type.
  - Offer discounts or promotions to attract new customers.

- **Booking Management:**
  - Receive and manage service bookings from pet owners.
  - Communicate with pet owners through the platform.

### Pet Rescue
- **Pet Profiles:**
  - Create profiles for pets available for adoption.
  - Include photos, descriptions, and adoption criteria.

- **Adoption Management:**
  - Manage inquiries and applications for pet adoptions.
  - Schedule meetings between potential adopters and pets.

- **Lost & Found Integration:**
  - Collaborate with the community to help locate lost pets.
  - List found pets and attempt to reunite them with owners.

- **Urgent Adoption Promotion:**
  - Promote dogs and cats in urgent need of adoption to all users.

- **In-App Shop:**
  - Access to discounts on pet-related products.

- **Reward System:**
  - Earn points by facilitating adoptions or helping locate lost pets.
  - Exchange points for discounts or products in the in-app shop.

### Staff
- **User Management:**
  - Manage user accounts and access levels.
  - Handle subscription and payment processing.

- **Community Support:**
  - Provide support to users (pet owners, service providers, rescues).
  - Mediate disputes and ensure community guidelines are followed.

- **Device Management:**
  - Add and manage GPS trackers and smart tags.
  - Assign trackers and tags to user accounts upon purchase.
  - Update device status and manage inventory.

## Additional Features

### Subscription Management
- **Integration with Stripe:**
  - Enable users to manage subscriptions, payments, and billing information through Stripe.
  - Support for multiple currencies and payment methods.
  - Automated billing and invoicing.

### Traccar API Integration
- **Live Tracking:**
  - Implement real-time GPS tracking for pets using the Traccar API.
  - Display pet locations on an interactive map.

- **Geo-Fencing:**
  - Allow users to set up geo-fences through the platform.
  - Automatically send geo-fence data to Traccar when created.
  - Receive geo-fence alerts and notifications from Traccar.

### Design Implementation
- **Figma Design Application:**
  - Apply the provided Figma designs to the platform to ensure a seamless user experience.
  - Maintain design consistency across all pages and components.
  - Ensure responsive design for mobile and desktop devices.

---

Feel free to customize and expand upon this as needed for your project documentation!
