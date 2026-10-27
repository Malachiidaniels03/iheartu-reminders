# I ♡ U reminder timer

The clock for I ♡ U's event reminders. Every 5 minutes it calls the app's server, which reads
both Google Calendars and sends any reminders that are due. Nothing private lives here: the
server address is public, and the key it sends is stored as a GitHub secret (`CRON_KEY`).
