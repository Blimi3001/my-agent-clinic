# Implementation Roadmap

Deliver the clinic in small, ordered phases. Each phase should leave a working
application and avoid taking on unrelated features.

1. **Create the app foundation.** Set up the Next.js and TypeScript
   application with a local development command and production build.
2. **Define clinic data.** Specify the minimum fields and relationships for
   agents, ailments, therapies, and appointments.
3. **Connect SQLite.** Add local database setup and a server-side data access
   path for the clinic records.
4. **Build the shared clinic shell.** Add responsive page layout and
   navigation for agent and staff areas.
5. **Show the agent directory.** Let clinic users browse and find agents.
6. **Show an agent's care needs.** Add an agent profile with its ailments.
7. **Show available therapies.** Let agents and staff review therapy options.
8. **Book an appointment.** Let an agent select a therapy and submit an
   appointment request, with clear validation and confirmation.
9. **Add staff appointment management.** Give staff a dashboard to review
   bookings and update their status.
10. **Polish and verify.** Check the main flows, accessibility, responsive
    layouts, and behavior in modern browsers; fix issues found before
    expanding scope.
