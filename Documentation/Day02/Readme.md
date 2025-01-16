# 🚀 Day 2 - System Design & Integration: Marketplace Builder Hackathon 2025

Welcome to Day 2 of my **Marketplace Builder Hackathon 2025** journey! 🎉 On this day, I focused on designing the overall system architecture and defining how the frontend will connect with the backend, along with integration details for third-party APIs.

---

## 🛠️ System Design Overview

The system is designed to be a seamless and scalable platform, where the frontend interacts smoothly with the backend to provide users with a dynamic and intuitive shopping experience. Here’s an overview of the approach:

---

## 🎯 Frontend-Backend Integration

- # Frontend Framework:
  - Next js, styled using Tailwind CSS with UI Components Library Like **(ShadCn Ui)**, with state management handled via Redux.
- # Backend:
  - Sanity.io with Third Party Api and handle API routes, serving data to the frontend through RESTful APIs.
- # Communication:
  - The frontend will interact with the sanity through HTTP requests (GET, POST, PUT, DELETE).

### 🌐 Third-Party API Integration

I’ve planned the integration of a third-party API that will provide additional features for the marketplace:

#### Third-Party API Details:

- **Purpose** The API will handle features like payment processing and product availability.
- **Integration Flow** The frontend will send requests to the backend, which will process the data and interact with the third-party API to retrieve the required information.
- **Security** Secure communication using HTTPS and API key-based authentication.

### 📊 API Routes Definition

Here is the list of all API routes with their respective actions:

`GET /api/products`: Fetches a list of all available products.
`POST /api/order`: Creates a new order and sends it to the third-party payment gateway for processing.
`GET /api/order/:id`: Fetches the details of a specific order using its ID.
`PUT /api/order/:id`: Updates the status of the order (e.g., shipped, delivered).
`GET /api/payment/verify`: Verifies payment status through the third-party API.
And Many Methods for Payment Gateway processing.

---

## 💡 Tech Stack

**Frontend:** Next js, Tailwind CSS, Zustand
**Backend:** Sanity.io
**API Integration:** Third-party API for payment processing and product availability
**Authentication:** Clerk authentication for secure login and transactions

## 📃 Documenting the Flow

The document clearly outlines how data will flow between the frontend, backend, and third-party API:

1. **Frontend** sends requests to the backend via API routes.
2. **Backend** processes these requests, interacts with the third-party API, and sends a response back to the frontend.
3. **Frontend** updates the UI based on the data received.

You can explore the complete document on how each component connects here: [System Design Document](https://app.eraser.io/workspace/Ux8HAqE3Acfn4DrUns0r?origin=share)

### 📊 Visual Data Structure:

Check out the data structure diagram here: [Data Schema Diagram](https://app.eraser.io/workspace/Ux8HAqE3Acfn4DrUns0r?origin=share)

---

## 📝 Next Steps

I will now focus on implementing the API routes, integrating the third-party services, and starting the frontend development to connect all the pieces together.

## 🚀 Day 2 Summary

I’ve laid out the groundwork for how the system will function, how components will communicate, and how third-party APIs will be integrated. The next steps will involve turning this design into a fully functional marketplace.

---

### 🏷️ Tags:

`#SystemDesign ` `#TechStack ` `#APIIntegration ` `#FrontendBackend` `#DataSchema` `#MarketplaceHackathon` `#Hackathon` `#ThirdPartyAPI` `#EcommerceJourney` `#Marketplace` `#TechJourney`
