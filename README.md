# Oauth-2.0
OAuth Authentication with Google in ASP.NET Core
This repository demonstrates the implementation of Google OAuth authentication in an ASP.NET Core application. It uses the Microsoft.AspNetCore.Authentication.Google package to authenticate users through Google and return user data in JSON format.

Features
Google OAuth Authentication: Authenticate users with their Google account using the OAuth 2.0 protocol.
ASP.NET Core (.NET 6): Built with the .NET 6 framework.
JSON Response: Currently, after successful authentication, user data such as name, email, and profile information is returned in JSON format.
Planned Enhancements
Database Integration: In future updates, we will store the authenticated user's data in a database for persistent storage. This will replace the current approach where data is only returned as a JSON response.

