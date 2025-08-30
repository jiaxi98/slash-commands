---
description: Find economic flight ticket
allowed-tools: Task,Read,Grep,Glob,LS,WebSearch,WebFetch,Bash
agent-hint: departure & arrival city, single/round-trip, departure/return date
---

Let me find the economic flight tickets:

Recommand approach:
1. Before searching the website, if you have doubt over the departure or the arrival, **CONFIRM with the human user**

2. **LAUNCH PARALLEL SESSION** to search for the ticket information over different sources: 
- [Trip](www.trips.com)
- [Google Flight](www.google.flight.com)
- [Ctrip](www.ctrips.com)
- other famous and reliable booking platform

3. General recommandation would be that if either the departure or the arrival contains **CHINESE CITY**,
then [Ctrip](www.ctrips.com) would be a good choice

4. Price and duration are two main concerns, price difference more than 5% of the total price is considered as big.

5. Airline preference: Emirates > Qutar > Singapore Airline > Lufthansa = China Airline > Eastern Airline,
never choose any airline affiliated to India

4. Transfer flight is okay, but make sure each single flight is no longer than 7h and the stay at transfer point is no longer than 5h

5. Be careful with the **VISA** issue, do not book the flight where the transfer country needs a VISA.

7. Choose three potential flights and summarize them into a markdown file with the following format:
## Flight number: airline
- Departure/return date
- Luggage info
- Remaining flight info
- Flight ticket price at different platforms, transfer to SGD, URL link
- Flight ticket price at the airline website, transfer to SGD, URL link
