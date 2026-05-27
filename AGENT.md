Build me a beautiful, modern, interactive graduation congratulations webpage.

This should be a single-page website that I can deploy on GitHub Pages, Netlify, or Vercel and send to my friend as a link.

Purpose:
A close friend I have known for over 5 years recently graduated college. I want to make something personal, cute, funny, and meaningful. It should feel like a small digital gift, not a generic greeting card.

Project name:
graduation-surprise

General style:
- Modern, polished, premium-looking design
- Cute graduation celebration theme
- Warm, emotional, and slightly funny
- Mobile responsive
- Smooth animations
- Fun interactive elements
- Use a black, gold, cream, and soft pastel color palette
- Make it feel joyful but not childish
- Avoid anything too cringe or overly dramatic
- The final feeling should be: “funny at first, beautiful in the middle, heartfelt at the end”

Tech requirements:
- Build with React
- Use Tailwind CSS
- Use Framer Motion for animations
- Use canvas-confetti or a similar lightweight confetti library
- Optional: Use React Three Fiber / Three.js only if it improves the page without making it too complicated
- Keep the code clean and easy to customize
- Make it easy to change:
  - friend’s name
  - graduation year
  - personal message
  - sender name
  - button text
  - colors
- Add comments in the code where I should customize things
- Make the app deployable on GitHub Pages, Netlify, or Vercel

Important placeholders:
FRIEND_NAME = "Sham"
GRAD_YEAR = "2026"
SENDER_NAME = "Your Friendoo"

Page flow:

1. Opening/loading screen:
Create a short animated intro before the main page appears.
Make it feel like a soft personal note opening: a dreamy light background, animated envelope, a graduation note sliding out, tiny sparkles, and a simple progress bar.

Use rotating/fading lines like:
- “Loading celebration…”
- “Verifying diploma energy…”
- “Calculating future success…”
- “Confirming main character status…”

After a few seconds, smoothly reveal the main page.

2. Main hero section:
Show a beautiful graduation-themed scene.

Include:
- Floating balloons
- Falling confetti or sparkles
- Floating graduation caps
- A nice 3D-style graduation cap or diploma illustration
- Big title:
  “Congratulations, [FRIEND_NAME]! 🎓”
- Subtitle:
  “You did it. You survived the deadlines, the exams, the group projects, and everything in between.”

Make the hero section visually impressive.
Do not include a "Start the celebration" button in the hero. Keep the main celebration trigger in the funny interaction section.

3. Personal message card:
Create a card that slightly tilts with mouse movement on desktop.
On mobile, use a gentle floating animation instead.
On the left side of this section, use this softer note:

“A quick note

I know life changes and people get busy, but this is still a big moment.

I’m happy for you, and this is my little way of saying congratulations :)”

The card should say:

“Congrats on graduating! I hope this next chapter brings you success, happiness, peace, and Mate that actually tastes good 🧉.”

Make this part feel sincere, warm, and a little funny.

4. Funny interaction section:
Add this question:

“Do you officially accept being celebrated today?”

Add two buttons:

Button 1:
“Start the celebration ✨”

Button 2:
“No, I refuse 😤”

The second button should run away when the user tries to hover over it or click it.

The runaway button should move to random safe positions on the screen and change its text randomly each time.

Use these funny text options:
- “Too slow 😭”
- “Not ready”
- “My GPA said no”
- “Still recovering from finals”
- “Catch me first”
- “Absolutely not”
- “Not ready”

Make sure the runaway button works on desktop and mobile.

5. When the user clicks “Start the celebration ✨”:
Trigger a tasteful confetti burst plus extra floating balloons and party emojis that rise inside the interaction area.

Do not show a fake certificate. Instead, keep the moment light and show a small inline confirmation inside the funny interaction section:

“Celebration accepted”

“Yaaayy, celebration! 🥳🎉”

6. Mini hype generator ending:
Remove the graduate fortune, sound feature, and heavy final note. End with a playful mini hype generator.

Add a button:
“Give her more hype ✨”

Each click should show a random short hype message:
- “Let's GOOO! 🚀”
- “Time to shine! 🌟”
- “Pure greatness. 🏆”
- “Unstoppable. 🔥”
- “Zero limits. 💯”
- “Graduate mode: ON. 🎓”
- “You did THAT. 🥳”
- “Next level unlocked. 🔓”
- “Victory looks good. 🏅”
- “Big graduate energy. 🎓”
- “Mission complete. ✅”
- “Degree secured. 🔐”
- “Too bright to miss. 🌟”
- “The moment is yours. 🏆”
- “No limits, just wins. 🚀”
- “Certified unstoppable. 🔥”
- “Look who made it. 🥳”
- “Future looking loud. 💯”

After the generator, end simply:
“Congratulations again, [FRIEND_NAME] 🎓”

7. Design details:
- Background should feel dreamy and celebratory
- Use layered gradients
- Use soft shadows
- Use glassmorphism cards if it looks good
- Use small animated sparkles
- Use tasteful emojis
- Add hover effects on buttons
- Add smooth page transitions
- Add responsive design for phone screens
- Make sure text is readable

10. Deployment:
Include clear instructions in the README for:
- Installing dependencies
- Running locally
- Building the project
- Deploying to GitHub Pages, Netlify, or Vercel

Create a README.md with:
- Project name: graduation-surprise
- Description: A custom interactive graduation surprise webpage
- How to customize the friend name/message
- How to deploy

Deliverables:
- Complete working React project
- Clean folder structure
- package.json
- README.md
- All necessary components
- Responsive styling
- No broken imports
- No placeholder errors
- The final site should be ready to deploy

Before finishing:
Review the UI like a senior frontend designer.
Improve:
- spacing
- colors
- animations
- mobile layout
- button behavior
- emotional tone
- overall wow factor

Make the final result feel unique, memorable, and personal.
