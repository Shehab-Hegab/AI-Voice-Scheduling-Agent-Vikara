AI Voice Scheduling Agent

This project is a real-time voice assistant built for the Vikara.ai Assessment. It collects user details and automatically schedules meetings in Google Calendar.
🚀 Live Demo & Testing

You can access and test the agent here: Click here to test Riley.
[https://dashboard.vapi.ai/assistants/7dd026c8-74b3-42b0-91e1-a2d8cb9769b7#recording-consent](https://dashboard.vapi.ai/assistants/7dd026c8-74b3-42b0-91e1-a2d8cb9769b7)

🛠️ The Tech Stack

    Voice AI Platform: Vapi.ai (using GPT-4o).

    Automation/Backend: Make.com.

    Calendar Integration: Google Calendar API.

⚙️ Implementation Details

    Data Collection: The agent (Riley) asks for Name, Date, Time, and Title.

    Verification: Riley repeats the details back to the user for confirmation.

    Real-time Scheduling: Once confirmed, a webhook is triggered in Make.com, which creates a real event in my Google Calendar.

📁 Included Files

    blueprint.json: The full automation workflow logic from Make.com.

Developed as part of the AI Engineer Assessment for Vikara.ai
