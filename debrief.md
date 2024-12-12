1. **Code and Readability**  
   - Adopt Clean Code principles and use TypeScript to provide type validation and enhance autocompletion. Move HubSpot-related functions to a dedicated module (e.g., `hubspotService.js`).  

2. **Architecture**  
   - Adopt Clean Architecture, S.O.L.I.D principles, and design patterns to reduce coupling, define interfaces, separate responsibilities, facilitate maintenance, and promote code reuse.  

3. **Performance**  
   - Implement parallel processing for handling large data volumes, ensuring multiple pages are processed simultaneously without exceeding API rate limits. Cache contact associations to avoid repeated API calls, reducing latency. 