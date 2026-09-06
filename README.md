# Microduck Assembly Lab — local snapshot

Source: https://microduck-assembly-lab.yishan-lin.chatgpt.site/

This folder contains the publicly accessible front-end snapshot captured on 2026-09-06, including the HTML, JavaScript, CSS, assembly manifest, and STL model resources.

To preview it locally:

```powershell
cd "C:\\GdriveM\\PlusObsidianVault\\agentknowledgeinte\\P01-project\\PhysicalAI-Robot"
node "tmp\\serve-microduck.mjs"
```

Then open http://127.0.0.1:8765/.

Server-side code, database contents, and any external services are not included.

The viewer includes a `Walk in Place` toggle. It uses a procedural walk cycle on the downloaded STL assembly; it is a visual in-place animation, not a physics simulation or a trained locomotion policy.
