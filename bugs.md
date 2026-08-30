# Active Bugs

## 1. Authentication & Login Transitions
- Login page does not automatically transition if credentials are typed too fast or text focus is lost.
- Input fields require visual confirmation to ensure email and password strings are fully rendered before triggering Sign In.
- Inconsistent auth error feedback if invalid credentials are submitted.

## 2. Support Navigation & Tab Handling
- Clicking 'Support & Feedback' opens an external link in a new browser tab/window, causing the agent to repeat clicks on the parent drawer if tab focus is not switched.

## 3. AI Task Creation
- AI task creation still occasionally includes prompt text in the title rather than parsed summary.
- Due date assignment for relative timestamps needs further refinement.

## 4. Onboarding Carousel Usability
- Onboarding tutorial carousel lacks visible desktop click arrows or skip buttons.
- Arrow keys do not trigger slide transitions on desktop web.