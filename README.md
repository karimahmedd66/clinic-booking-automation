
# Clinic Booking Automation System

A fully automated clinic appointment booking system built as a managed service for medical clinics in Egypt. The system handles the complete booking lifecycle including scheduling, notifications, and calendar management.

## Features

- Online booking page where patients select their branch, date, and time slot
- Automated WhatsApp confirmations and reminders sent to patients
- Google Sheets used as a real-time database for all appointments
- Google Calendar sync — every booking creates, updates, or deletes an event automatically
- Patients can modify or cancel appointments with instant WhatsApp updates
- Day-before reminders sent automatically
- Completed and cancelled appointments archived nightly
- Real-time availability check prevents double bookings

## Tech Stack

- Frontend: React.js, deployed on Vercel
- Automation: Workflow automation engine, self-hosted on Railway
- Database: Google Sheets API
- Calendar: Google Calendar API
- Messaging: WhatsApp Business API
- Infrastructure: Railway

## How It Works

The patient opens the booking page, selects a branch and available time slot, and submits their details. The system validates the input, checks real-time availability, generates a unique booking ID, stores the appointment in Google Sheets, creates a Google Calendar event, and sends a WhatsApp confirmation to the patient — all automatically.

## Business Model

This system is deployed as a managed service for medical clinics in Egypt, running on a setup fee plus monthly subscription model. Currently serving paying clients.

## Author

Karim Ahmed  
Communication and Electronics Engineering Student, Higher Technological Institute (HTI)  
karim.ahwafik@gmail.com  
https://www.linkedin.com/in/karim-ahmed-850253391/
