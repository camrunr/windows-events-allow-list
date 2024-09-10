# windows-events-allow-list
This CSV lists important windows event codes to monitor in a security context -- FROM MY EXPERIENCE. Your mileage may vary. Please note, YMMV!

The intention is to use this as an allow list to ignore other codes. Using a pipeline toolset, like Cribl, dump all events into archive. Only allow these through to your SIEM.

The file includes the numeric account ID, and a short blurb to describe what the event is.

PRs are welcome. Please provide some notes on why new codes need to be included!
