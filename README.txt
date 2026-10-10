BMP Nagar Cricket Turf, Umri — booking website prototype

Files:
- index.html: self-contained responsive website.

Try it:
1. Open index.html in Chrome/Edge.
2. Choose date, enter name and 10-digit mobile number.
3. Select a 1-hour slot.
4. Press “Send booking request on WhatsApp”.

Pricing implemented:
- 06:00–16:00 start times: ₹600 (includes 4–5 PM slot? No: start times before 17:00 use ₹600)
- 17:00–22:00 start times: ₹700
This implements the 5 PM–6 PM slot at ₹700 based on the latest working assumption.

Important limitations:
- This is a front-end prototype. Bookings are stored in this browser only, not shared between customers/devices.
- WhatsApp request is opened to 8999935127. The second number 7620059854 is listed for the owner but is not automatically notified; WhatsApp wa.me opens one recipient at a time.
- Demo admin PIN is 2580 and is not secure. Do not use this as a real admin login.
- Before public launch, add a shared database with atomic slot reservation, real admin authentication, booking statuses, and server-side conflict checking.
- No online payments; customer pays at the turf.
