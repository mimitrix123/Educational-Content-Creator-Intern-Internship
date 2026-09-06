# Week 2 Mini Project — Complete Educational Lesson

## Topic
**Git & GitHub in 5 Minutes**

## Learning Objective
By the end of the lesson, a beginner will understand the difference between Git and GitHub, know the five core commands, and be able to create and push a first repository.

## Video Format
- Target duration: 5 minutes
- Resolution: 1920×1080 (1080p)
- Format: MP4, H.264 video, AAC audio
- Structure: talking-head hook → slides → live screen demo → talking-head recap
- Background music: low-volume instrumental bed during intro/outro; duck or mute it under explanations

## 5-Minute Storyboard & Script

### 0:00–0:25 — Talking Head Hook
**Visual:** Presenter on camera.

**Script:**
"If you can write code but you don't know Git and GitHub, you're missing one of the most useful developer skills. In the next five minutes, I'll show you what Git is, what GitHub is, the five commands you actually need as a beginner, and how to publish your first project."

### 0:25–0:55 — Slide: Why Git?
**Script:**
"Git tracks changes in your project. Think of every commit as a checkpoint in a timeline. If a change breaks something, you can inspect the history and recover. Git also makes it safer to experiment and collaborate."

### 0:55–1:25 — Slide: Git vs GitHub
**Script:**
"Git and GitHub are related, but they aren't the same thing. Git is version-control software that runs on your computer. GitHub is an online platform where Git repositories can be hosted and shared. You can absolutely use Git without GitHub."

### 1:25–2:05 — Slide: Five Commands
**Script:**
"Here are the commands to remember. `git init` starts tracking a project. `git add .` stages your changes. `git commit -m` saves a checkpoint with a message. `git remote add origin` connects your local project to an online repository. And `git push` uploads your commits."

### 2:05–3:45 — Screen Recording: Live Demo
**Visual:** Desktop screen recording. Open terminal and a code editor.

**Demo steps:**
```text
mkdir git-demo
cd git-demo
```
Create `README.md` containing a project title.

```text
git init
git add .
git commit -m "Initial commit"
```
Create an empty GitHub repository named `git-demo` and copy its HTTPS remote URL.

```text
git remote add origin <YOUR_REPOSITORY_URL>
git branch -M main
git push -u origin main
```

**Voiceover:**
"Notice what happened: Git created the local history, we made our first commit, then we connected that local repository to GitHub and pushed it online. From here, every meaningful change can become another commit and be shared through GitHub."

### 3:45–4:30 — Slide: Recruiter-Friendly README
**Script:**
"GitHub is also part of your professional portfolio. A good repository should explain the problem, features, technology used, setup instructions, screenshots or a demo, and what you learned. Don't upload a project with no explanation and expect someone else to figure it out."

### 4:30–4:50 — Talking Head Challenge
**Script:**
"Your challenge is simple: create one repository, make three meaningful commits, write a clear README, and push it to GitHub. If you can do that today, you've practiced a real developer workflow."

### 4:50–5:00 — Talking Head CTA
**Script:**
"Remember: learn, build, document, and share. Subscribe for more practical beginner-friendly programming lessons."

## Background Music Plan
- 0:00–0:25: music at approximately 15–20% of voice level
- 0:25–4:50: music muted or heavily ducked so speech remains clear
- 4:50–5:00: music fades in gently for the closing
- Use royalty-free/licensed instrumental music only

## Recording & Editing Checklist
- [ ] Record talking-head sections in 1080p
- [ ] Capture screen at 1920×1080 where possible
- [ ] Use a USB/lavalier microphone or the cleanest available mic
- [ ] Keep the presenter centered with clear lighting
- [ ] Zoom the terminal text so commands are readable
- [ ] Add captions for key commands
- [ ] Add subtle transitions; avoid distracting effects
- [ ] Normalize voice audio and keep music below speech
- [ ] Export MP4, H.264, 1920×1080
- [ ] Watch the final export from beginning to end before submission

## Slide Deck
`Week_2_Git_GitHub_5_Minute_Lesson.pptx` contains the lesson slides.

## Deliverable Status
- Lesson topic selected: complete
- Educational script: complete
- Slide deck: complete
- Talking-head + screen-recording storyboard: complete
- Background music/editing plan: complete
- 1080p export specification: complete

**Recording note:** This repository contains the production-ready lesson plan and slide deck. The actual camera/screen recording and final MP4 export must be performed in a local recording editor because this environment cannot physically capture the user's camera/microphone or desktop screen.
