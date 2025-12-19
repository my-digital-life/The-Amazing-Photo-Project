The Amazing Photo Project
Trying to use Immich to sort out and clean up the 20–30k photos I’ve collected over the years. This is the start of that whole adventure. No idea where it’ll end up, but it feels like the right time to dive in.
I’m using Copilot along the way — mostly to help me plan things out, write scripts, and keep the technical side from turning into a mess. If you’re not into AI, this probably isn’t your place.
What I’m building
A clean, structured photo system using Immich, with:
• 	A dedicated RAW library on F:\immich\raw
• 	A backup of those RAWs on E:\immich\raw_backup
• 	A working/editing area on D:\immich\work
• 	A fresh Immich Docker setup running on my LAN
Everything is organized under a single  folder on each drive so it’s predictable and easy to maintain.
Docker setup
Immich runs in Docker on Windows, and I wanted it:
• 	On the same LAN subnet as the rest of my computers
• 	With a static IP (192.168.1.5)
• 	Accessible on port 80
• 	Fully behind my router’s firewall
The Docker config lives in:

This folder holds the  and .
All the actual photo data lives on F:, E:, and D:.
Folder structure
F:\immich\raw
Main photo library (RAWs, incoming, year folders)
E:\immich\raw_backup
Backup of the RAWs
D:\immich\work
Exports, edits, AI stuff, temp files, and the Immich database
Why this repo exists
Mostly to track the scripts, configs, and notes as I go. This project is taking longer than expected, but that’s part of the process.
Friday, December 19, 2025 — 4:06 AM
