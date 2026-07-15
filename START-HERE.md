# Start Here

This project can automate parts of applying for jobs. It is powerful, but it is **not** a magic “get hired” button.

## Before you touch anything

- Test with fake information first.
- Never upload passwords or secret access keys to GitHub.
- Review every application before it is sent.
- Check each job site's rules. Heavy automation can get an account limited or blocked.
- The project has not recorded a recent successful automatic test on this copy, so treat it as unverified until the checks pass.

## What you need

1. A computer with Google Chrome.
2. Python 3.10, 3.11, or 3.12.
3. An AI service account and its private access key.
4. A copy of your resume information with private details stored only on your computer.
5. Patience for a test run before using real applications.

## The shortest safe setup

### 1. Download the project

On the green **Code** button, choose **Download ZIP**, then unzip it.

### 2. Install the required pieces

The full technical installation is in [README.md](README.md#installation). If those steps feel like alphabet soup, stop and open a help request instead of guessing.

### 3. Make your private data folder

Copy the example data folder. Put your real information in the copy, not in the example.

Your private folder needs:

- `secrets.yaml` for the AI access key.
- `plain_text_resume.yaml` for your resume and job preferences.

### 4. Check for accidental secrets

Before uploading or sharing anything, search for your access key, home address, phone number, and Social Security number. None of those belong in GitHub.

### 5. Run one fake test

Start with a throwaway test. Confirm the tool:

- reads the correct resume,
- chooses sensible answers,
- does not submit without your approval,
- produces a clear result,
- stops when something looks wrong.

## When it breaks

[Open a beginner-friendly help request](../../issues/new?template=something-broke.yml).

Say what you tried, what happened, and what you expected. Paste the exact error, but remove private information first.

## When you want it easier

[Suggest an improvement](../../issues/new?template=idea.yml). Describe the win you want in normal language.
