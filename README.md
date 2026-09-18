# Volta Newsletter — Link Desk

A single-page tool for building UTM-tagged links for the Volta newsletter, so every link dropped into Mailchimp is consistently tracked.

## What it does

- Pick a **send date**, which becomes the `utm_campaign` value (e.g. `2026_09_18`).
- Add a link with a **headline**, **destination URL**, **section** (Founder spotlight / Community event / Other), and a **specific label** to tell it apart from other links in the same section.
- The tool appends standard UTM parameters automatically:
  - `utm_source=volta_newsletter`
  - `utm_medium=email`
  - `utm_campaign=<send date>`
  - `utm_content=<section>_<label>`
- Links collect in a queue on the right, each one copyable individually.
- **Copy all** copies every queued link (title + tagged URL) to the clipboard, ready to paste into Mailchimp.
- **Download as .txt** saves the same list to a file named after the campaign date.

## Usage

Open `demo2.html` directly in a browser — no build step, no dependencies. Fill in the form, add each link for the issue, then copy or download the finished list.
