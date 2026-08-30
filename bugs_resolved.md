# Resolved Bugs & Fixes

## 1. Automated Visual Testing
- **Model Fallback Rotation**: Successfully rotated from `gemini-3.1-flash-lite` to `gemini-flash-lite-latest` when daily quota was exhausted (verified in Step 6 of TC-09).
- **Coordinate Scaling**: Scaled `[0, 1000]` normalized coordinates accurately across 1280x800 resolution.
- **Credential Grounding**: Enforced exact user credential usage (`kirajain2001@gmail.com` / `123456`) and visual verification before submission.
- **Canvas Waypoint Dragging**: Enabled reliable drag and swipe gestures for Flutter PageViews.

## 2. Core App Features Verified
- **Initial Sign Out (TC-01)**: Successfully passed.
- **Authentication & Login (TC-02)**: Verified sign in flow to main dashboard.
- **AI Text Commands (TC-03)**: Verified parsing and task list rendering.
- **Calendar Date Filtering (TC-04)**: Verified date chip filter and All Tasks reset.
- **Community Creation (TC-05)**: Verified workspace creation with Owner badge.
- **Task Lifecycle & Reordering (TC-06)**: Verified task creation and drag handle reordering.
- **Discussion 2-Comment Limit (TC-07)**: Verified comment limit locking and unlock on completion.
- **Profile Identity Fallback (TC-08)**: Verified user initials (`KJ`) rendered on avatar circle.