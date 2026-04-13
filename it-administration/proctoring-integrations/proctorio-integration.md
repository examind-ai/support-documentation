---
description: >-
  This page provides step by step instructions for instructors to set up EXAMIND
  with Proctorio in Canvas. At the end there is a draft of student instructions
  that you could provide students.
---

# Proctorio Integration

## Instructor Setup Guide: EXAMIND with Proctorio and Canvas

Prerequisities: Examind is configured as an External Tool in your Canvas instance. Proctorio is installed and enabled at the institutional level. Your exam content is already built in Examind.

### Step 1: Create the Examind Assignment

1. In your Canvas course, go to Assignments and create a new Assignment.
2. Set the points to the actual exam value (e.g., 100 points).
3. Under Submission Type, select External Tool and select Examind. Link it to your specific exam.
4. Set Available From and Until dates to define the exam window.
5. Do NOT set a Due Date. A due date causes the assignment to appear on the student to-do list, which could lead students to open it directly and bypass Proctorio. Use only the availability window.
6. Set Allowed Attempts to Unlimited. This is required for Examind's automatic grade sync to function correctly.
7. Click Save & Publish.
8. Copy the full URL of this Assignment from your browser's address bar. You will need it in Step 3.

### Step 2: Hide the Assignment

The Assignment must be published (so students can access it via the link), but it should not be independently discoverable.

1. Do not add this Assignment to any Module. It should not appear in the course navigation flow.
2. Go to Settings → Navigation and ensure the Assignments tab is either hidden from students or that students are instructed to access exams only through the designated Quiz.
3.  To hide the tab: drag "Assignments" to the hidden items area in the Navigation settings.

    The Assignment will still appear in the Gradebook, which is expected.

### Step 3: Create the Proctorio Quiz

1. Go to Quizzes and create a new Classic Quiz (Proctorio does not support New Quizzes at all institutions — confirm with your institution).
2. Set the quiz title to your exam name (e.g., "Exam 3").
3. Set the quiz to be worth 0 points. This quiz exists only to activate Proctorio.
4. Add one question (e.g., a "Text (No Question)" type or an Essay question worth 0 points). In the question body, paste the URL from Step 1 as a clickable hyperlink. Label it clearly, e.g.:\
   \
   Click here to open your exam in Examind → \[link]<br>
5. Set the time limit to be longer than the Examind exam timer (e.g., if the exam is 60 minutes, set the quiz to 75–90 minutes). This accounts for setup time.
6. Set availability dates to match or slightly exceed the Assignment availability window.
7. Save the Quiz (do not publish yet).

### Step 4: Configure Proctorio Settings

1. Open the Quiz in edit mode and navigate to the Proctorio settings (typically accessible via a Proctorio shield icon or settings panel).
2. Enable:
   1. Webcam recording
   2. Screen recording
   3. Web traffic / URL logging
3. Disable or relax:
   1. Force full screen → Disabled (students must switch tabs)
   2. Close open tabs → Disabled
   3. Restrict new tabs / websites → Set to the most permissive option. The "allow in-exam links only" setting is not sufficient — it blocks the second redirect from the Canvas Assignment to Examind. Students need to be able to navigate freely.
4. Optionally enable the Proctorio calculator, though note that students will likely prefer their OS calculator since the Proctorio calculator is on a different tab.
5. Save settings.

### Step 5: Add Exam Instructions

In the Quiz description (visible to students before they begin), include clear instructions. At minimum, cover:

* The exam is remotely proctored via Proctorio — webcam and screen will be recorded.
* The quiz itself contains only a link; the actual exam is in Examind.
* After completing the exam in Examind, students must return to this Quiz tab and click Submit to end the Proctorio recording.
* Students must use an on-screen calculator (OS built-in or Proctorio's) — no phones or off-screen devices.
* (Optional) Students must show blank scratch paper before starting and show it again after finishing.
* If no Proctorio recording is found for a submission, the student will receive a zero and may be required to retake the exam.

See the companion Student Instructions below for ready-to-use language.&#x20;

### Step 6: Publish and Add to Module

1. Publish the Quiz.
2. Add the Quiz (not the Assignment) to the appropriate Module in your course. The Quiz is the only entry point students should see.

### Step 7: Post-Exam Review

After students submit:

1. Cross-reference submissions: In the Gradebook, verify that every student who submitted the Examind Assignment also has a corresponding Proctorio Quiz submission (even if it's 0 points). A student with an Assignment grade but a missing Quiz submission may have bypassed Proctorio.
2. Review Proctorio recordings: Use the Proctorio dashboard to review recordings. Playback at 8× or 16× speed is typically sufficient for spot-checking compliance.
3. Review URL logs: Proctorio logs which URLs students visited. If any URL is not Canvas or Examind, investigate further.
4. Check scratch paper (if required): Confirm students showed blank paper at the start and written-on paper at the end.

### Quick-Reference Checklist

* \[ ] Examind Assignment created, linked to exam, set to correct points
* \[ ] Assignment has availability window only (no due date)
* \[ ] Assignment has unlimited attempts enabled
* \[ ] Assignment is published but hidden from Modules and Assignments tab
* \[ ] Quiz created with 0 points, containing one link to the Assignment
* \[ ] Quiz time limit exceeds Examind exam timer by 15–30 minutes
* \[ ] Proctorio settings: recording ON, full-screen OFF, tab restriction OFF
* \[ ] Student instructions included in Quiz description
* \[ ] Quiz is published and added to the appropriate Module

## Proctored Student Exam Instructions (Please Read!)

We use Proctorio to record your exam session. Your webcam, screen, and web activity are all recorded. Your instructor will personally review a portion of your recording to check adherence to these policies.

### Rules

1. Eyes on your screen or scratch paper only. There is no reason to look anywhere else.
2. You must use an on-screen calculator. If a question requires calculation and you do not use an on-screen calculator, your instructor will assume you used an unauthorized source. You may use the basic calculator built into your computer (Windows Calculator, Mac Calculator app) or the Proctorio calculator, which is available on the quiz tab labeled "Quiz: \[Exam Name] (Remotely Proctored)." The important thing is that the calculator is visible on your screen.
3. Show your scratch paper to your webcam at the start of the exam so that it is clearly blank.
4. Show your scratch paper again at the end so your instructor can see how you used it.
5. Do not use your phone or any off-screen device. If a phone or other device appears in your recording, you may be required to retake the exam.

### Starting Your Exam

1. Open this exam in Canvas. Proctorio will begin automatically — follow its setup prompts.
2. The only question in this exam is a link. Click it to open the assignment.
3. On the assignment page, click "Load \[Exam Name] in a New Window" to start your exam in Examind.

You will now have multiple browser tabs open. This is normal — do not close any of them.

### Finishing Your Exam

1. After you answer all questions, submit your exam in Examind.
2. Return to the original Canvas quiz tab and click Submit. This will close Proctorio.

If you do not submit the Canvas quiz, your Proctorio recording may be incomplete and you may receive a zero or be required to retake the exam.

### If Something Goes Wrong

If Proctorio won't start, make sure you are using Chrome with the Proctorio extension installed. If your recording stops or you experience a technical issue, contact your instructor immediately — do not continue without a recording.<br>
