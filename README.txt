HOW TO ADD YOUR OWN VIDEOS

1. Inside this project folder, create a folder named:
   videos

2. Put your video files in that folder.
   Example:
   videos/video-1.mp4
   videos/video-2.mp4

3. Open app.js and find the courseModules array near the top.

4. For each module, set videoFile like this:
   videoFile: "./videos/video-1.mp4",

5. Leave videoUrl blank if you are not using YouTube.

Example module:
{
  number: "01",
  title: "Financial Literacy Foundations",
  description: "Replace this description here",
  videoFile: "./videos/video-1.mp4",
  videoUrl: "",
  takeaways: [
    "Replace this takeaway",
    "Replace this takeaway",
  ],
}

IMPORTANT

- Easiest option: double-click start-site.bat
- That will open the website and keep the local server running
- If you prefer, you can also double-click start-site.vbs
- The page address is http://127.0.0.1:8000
- Local video files usually will not work correctly if you only double-click index.html
- Best file types to use: .mp4, .webm
