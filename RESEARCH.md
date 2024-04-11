# RESEARCH

## Device Fingerprinting

- FingerPrintJS - basic hash, devices ..
- Shield - has free tier
- Cloudflare - what metadata available

## Device Lookup

- Cloudflare KV 
	- Sessions per UserID
	- ProfileID per UserID

- Cloudflare Durable Object 
	- Anonymous FingerPrintID; cluster BY Cloudflare COUNTRY,POP
	- PerSession; Unique FingerPrint

## Long Running 

- JetSocket / Plane.dev; one long running Flow per UserID or per FingerPrintID
- All actions queued for persistence; behavior analysis ..

## Device Info

- Use Tauri to generate a dummy Android app to study fields detected by fingerprinting

## Data Model

- Use SQLMesh to transform sample data for model building ..

