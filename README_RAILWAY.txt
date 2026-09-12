PARTO'S OCEAN RUN — RAILWAY DEPLOYMENT

This package is ready to deploy as a single Railway service.
The same public URL works on desktop and phones:
- index.html automatically sends desktop-sized/fine-pointer devices to desktop.html
- phones/small/coarse-pointer devices go to mobile.html
- /desktop.html and /mobile.html can also be opened directly
- add ?choose=1 to the root URL to show the manual Desktop/Mobile chooser

EDITING TEXT
Edit public/text.js. The desktop and mobile versions both load that file.
The intro has no bold emphasis markup.

RAILWAY CLI
1. Open PowerShell inside this folder.
2. Log in if needed:
   railway login
3. Create/link a Railway project:
   railway init
4. Deploy:
   railway up --detach
5. In Railway's dashboard, open the service -> Settings/Networking -> Generate Domain.

No database or environment variables are required.
Railway provides PORT automatically; server.js uses it.
