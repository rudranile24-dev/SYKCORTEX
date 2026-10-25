# SKYCORTEX – Drone PoC (static replica)

This is a static HTML/CSS recreation based on the screenshots you supplied. It keeps the original Google Sites white background, blue sticky title bar, large centered heading, left-aligned media blocks, certificates, project images and plain-text team/contact section.

## Before deployment
The screenshots show the original media but do not include the original full-resolution image/video files. Add those original files into `assets/` and `videos/` using the filenames referenced by `index.html`:
- `assets/uav-field.jpg`
- `assets/remote-pilot-certificate.jpg`
- `assets/glide-poster.jpg`
- `assets/dgca-license.jpg`
- `assets/counter-drone-poster.jpg`
- `assets/vtol-takeoff-poster.jpg`
- `assets/glide-endurance-poster.jpg`
- `assets/dgca-license.jpg`
- `assets/vtol-landing-poster.jpg`
- `assets/ham-license.jpg`
- `assets/funding-letter.jpg`
- `assets/project-work.jpg`
- `assets/team-working.jpg`
- `assets/drone-prototype.jpg`
- `assets/completion-certificate.jpg`
- `assets/team-workshop.jpg`
- `assets/team-workshop-2.jpg`
- `assets/hexacopter-poster.jpg`
- `assets/flight-test.jpg`
- `assets/drone-frame.jpg`
- `assets/team-photo.jpg`

Add videos:
- `videos/initial-flight.mp4`
- `videos/vtol-takeoff.mp4`
- `videos/long-endurance-glide.mp4`
- `videos/vtol-landing.mp4`
- `videos/hexacopter-trials.mp4`

The supplied screenshots are retained in `assets/reference-*.png` for comparison; they are not used as full-page backgrounds.

## Deploy to Vercel
Upload the folder to a GitHub repository, import it into Vercel, choose **Other** as the framework preset, and deploy as a static site. No build command is needed.
