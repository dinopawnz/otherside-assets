THE CHOCOLATE FACTORY - setup
=============================
1. On GitHub create a PUBLIC repo named  factory  (account dinopawnz).
   Upload every file in the "models" folder to the repo ROOT on the main branch (drag & drop, 70 files).
   The MML loads them from  https://raw.githubusercontent.com/dinopawnz/factory/main/<name>.glb.gz
   (If you use another repo/branch, change BASE at the top of factory.html.)
2. Put factory.html in your "Otherside MMLs" folder (served by mml-cli on port 7079 / ngrok).
3. In Otherside place the document: you get a small chocolate-bar PLACER. Put it where players arrive.
   The factory rises 152 m behind it with the front facing the placer.
4. Open factory_remote.html in your browser, enter wss://<your ngrok>/factory.html, PIN 2462, Connect, LIVE BUILD.

Remote: gates / front doors / chocolate doors, the 10 coded doors (codes shown, "New code" to change),
boats (send up / bring down / auto), LITE (drops small decoration for weak PCs), REFRESH, fold back.
Host commands also work as "2462 <command>" in the host prompt: build, unbuild, gates open|close,
doors open|close, main | main hold | main close, door <1-10|all> open|close|hold, code <n> <digits>, codes,
boats go|down|reset|auto on|off, lite on|off, refresh.

Door codes for this version are in door_codes.json (Oompa Loompa staff only).
Triangles: ~960,000 of the 1,000,000 limit. Downloads: ~34 MB (meshopt + gzip).
