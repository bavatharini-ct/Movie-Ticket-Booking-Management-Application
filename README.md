# Movie Ticket Booking Management Application

A Pega-based Movie Ticket Booking Management Application developed as part of the SkillWallet National Internship Program.

## 📌 Project Overview

This application manages the movie ticket booking process through a structured Pega case lifecycle. It allows a user to submit a movie ticket request, check show availability, calculate the booking cost, obtain approval, execute the booking process, and receive a booking confirmation.

## 🛠️ Technology

- Pega Platform
- Pega Infinity 25.1.3
- Pega App Studio
- Pega Dev Studio

## 🎬 Case Type

**Movie Ticket Request**

### Case Lifecycle

1. Initial Stage
2. Availability
3. Approval
4. Booking Execution

## ✨ Key Features

- Submit Movie Ticket Request
- Movie and Show data objects
- Check Show Availability
- Calculate Total Cost
- Booking approval workflow
- Booking details review
- Ticket booking execution
- Booking confirmation notification
- Goal and Deadline SLA configuration
- Automatic routing based on Show Type

## 💰 Cost Calculation

The booking cost is calculated using:

**Total Cost = Number of Tickets × Ticket Price**

## 🔀 Automatic Routing

The application routes booking requests according to Show Type:

- Premium → PremiumShowQueue
- Special → PremiumShowQueue
- Other show types → StandardShowQueue

## ⏱️ SLA

The Movie Ticket Request case is configured with:

- Goal: 1 day
- Deadline: 2 days

## 📦 Project Package

The repository contains the exported Pega application archive:

`Ticketing_010101_20260923T173940_GMT.zip`

The archive was exported from the Pega application environment using Pega's application distribution export.

## 🚀 Setup / Import

To use the exported application:

1. Use a compatible Pega Infinity environment.
2. Open Pega Dev Studio.
3. Navigate to the Application Distribution import functionality.
4. Import the provided Pega application archive.
5. Verify the `Ticketing and Booking` application.
6. Open the `Movie Ticket Request` case type.
7. Run a test case through the configured lifecycle.

## 📋 Project Status

The required Movie Ticket Request workflow and user stories US-001 through US-010 have been implemented and tested in the Pega development environment.

## 👩‍💻 Project

**Movie Ticket Booking Management Application**

Developed as part of the **SkillWallet National Internship Program**.
