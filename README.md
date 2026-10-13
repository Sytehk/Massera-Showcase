# Massera

**A marketplace for massage, spa, and wellness bookings**

Massera is designed to help people discover wellness services and arrange appointments with independent providers and spa teams. The product centers on the full booking journey, from finding a suitable service to managing the appointment afterward.

Its initial market focus is Nigeria, with the product structure designed to accommodate country and city configuration as the marketplace expands.

## Marketplace experiences

- **Clients** can discover therapists, compare service details, choose preferences, and arrange a visit.
- **Providers** can present their services and manage appointment-related work.
- **Spa teams** can coordinate services, schedules, and client interactions through dedicated workspaces.
- **Administrators** can support marketplace operations through a separate web console.

The planned customer journey includes service and provider discovery, profiles and reviews, scheduling, booking details, checkout, notifications, and follow-up. Provider and spa workflows are kept distinct from client discovery, while shared booking records connect the steps.

## Mobile concept

<p align="center">
  <img src="assets/booking-request-concept.jpg" width="340" alt="Massera mobile booking-request design concept">
</p>
<p align="center"><sub>Design concept from the project reference screens, not a production app capture.</sub></p>

## Engineering

The platform combines a Flutter mobile application, a Next.js administration experience, and Supabase-backed data and server workflows. The repository is organized into mobile and web apps, shared Flutter packages for design, models, validation, and Supabase access, plus database migrations and server functions.

Security boundaries are important for a booking marketplace. Sensitive account, booking, payment, provider-verification, and administrative actions belong in trusted server-side workflows rather than in the client app.

## Technology

Flutter and Dart, Next.js, Supabase, PostgreSQL, shared Flutter packages, and server functions.

## This repository

This is a public product overview with one clearly labeled design concept. It does not include private source code, customer or booking records, credentials, or internal operating details.

[Explore AceNetics](https://acenetics.dev)
