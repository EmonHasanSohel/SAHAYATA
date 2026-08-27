# Changelog

## Version 1.0 - Initial Release

### Core & Authentication
* feat: added registration form capturing user details (name, email, username, password, phone, address).
* feat: added OTP verification for mobile and confirmation for email.
* feat: added login functionality with username, password, and role-based redirection.
* feat: implemented forgot password feature with OTP verification and new password setup.

### Manager & Admin Modules
* feat: added manager profile management to view and edit personal details.
* feat: implemented admin account creation and status management (activate/deactivate) for managers.
* feat: added system statistics dashboard displaying total users, requests, and deliveries.
* feat: added admin profile management to view and edit personal details.
* feat: implemented disaster request management for admins to view, filter, and approve or reject requests.
* feat: implemented user account management for admins to search, filter, and toggle user activation status.
* feat: added donation and delivery monitoring for admins including volunteer assignment functionality.
* feat: implemented system audit logging and report generation capabilities.

### Victim Module
* feat: added victim profile management to view and edit personal details.
* feat: added help request submission form for victims to report disaster details and urgency.
* feat: implement victim request and delivery tracking to monitor status and volunteer details.
* feat: added in-app/SMS notifications for request status and implemented map view for disaster locations and relief points.

### Donator Module
* feat: added donator profile management to view and edit personal details.
* feat: implemented functionality for donators to view disaster requests and submit donation details.
* feat: added donation tracking and history viewing capabilities for donators.

### Volunteer Module
* feat: added volunteer profile management to view and edit personal details and availability status.
* feat: implemented volunteer delivery task management to view assignments and update delivery statuses.
* feat: added task history viewing and assignment notifications for volunteers.