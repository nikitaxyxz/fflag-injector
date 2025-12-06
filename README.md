# fflag-injector
A lightweight FastFlag injector for Roblox focused on simplicity and stability. Loads a local fflag.json, pulls FFlag offsets from GitHub, and writes values directly to running Roblox processes. Includes auto-launch, multi-instance support, and a minimal black-quartz interface.


Features

Load and apply FastFlags from fflag.json

Automatic offset syncing from GitHub

Injects into all running Roblox clients

Restores original values with Uninject

Auto-launch Roblox and auto-inject

Clean, compact UI

How to Use

Load your fflag.json

Click Inject

(Optional) use Auto-Launch

Use Uninject to revert

Notes

Config stored in %AppData%/FFlagToolkit/

Safe write limits (up to 4 bytes per offset)

Supports all common FFlag types
