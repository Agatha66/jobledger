# JobLedger privacy policy

**Effective date:** 20 November 2026

JobLedger is a browser extension for Google Chrome and Microsoft Edge that keeps track of the job applications you make. This policy explains what it handles and where that information goes. In short: **everything stays in your own browser, and nothing is sent to us or anyone else.**

## What JobLedger stores

JobLedger stores the following, on your computer only:

- **Applications.** For each job you apply to or save: job title, company, location, salary (when the page shows one), the job's link, the job board, the job description (when the page shows one), the stage (for example Applied or Interview), when it changed, and the status words shown on the board's "my applications" page.
- **What you add yourself.** Notes, follow-up dates and any changes you make to the details above.
- **Board visits.** Which supported job boards you have visited, when, whether you appeared to be signed in, and when each was last synced.
- **Settings.** Your choices in JobLedger's Settings page, and the careers sites you have asked JobLedger to track.

## How JobLedger gets this information

- **On supported job boards**, JobLedger reads the job you are looking at when you apply, and the list on your "my applications" page.
  - Supported boards: LinkedIn, JobStreet (and JobsDB/SEEK), Indeed, foundit, Hiredly, Graduan, Maukerja and MYFutureJobs.
- **On other careers sites**, JobLedger reads pages only after you turn it on for that site from the JobLedger popup.
- **When you click "Mark as applied" or "Save"** in the popup, JobLedger reads the page you are on.
- **Automatic sync**, if on (Settings → Automatic sync), opens your supported boards' "my applications" pages in a minimised browser window and reads them, the same as if you had opened them yourself. It uses your existing sign-in to those sites. It only opens boards you have visited while signed in.

JobLedger does not read your passwords, form contents or any other website.

## Where it goes

- **All data is stored locally** in your browser, in the extension's own storage (IndexedDB and `chrome.storage`).
- **JobLedger has no server.** It sends no data to the developer or any third party, and has no analytics, tracking, advertising or accounts.
- **JobLedger itself makes no network requests.** Board icons are bundled with the extension. Icons for other careers sites come from your browser's own icon cache.
- **Backups and CSV exports** are files saved to your computer, only when you choose **Download backup** or **Export CSV**.
- The developer cannot see your data.

## Sharing and selling

JobLedger does not sell, rent, share or transfer your data to anyone. Your data is not used for advertising, creditworthiness or any purpose other than showing you your own applications.

## Keeping or deleting your data

- **One application:** delete it from the dashboard (open it, then choose **Delete application**).
- **Everything:** remove the extension from your browser. This deletes all of JobLedger's data. Download a backup first if you want to keep it.

## Permissions

| Permission | Why JobLedger needs it |
|---|---|
| Access to the supported job boards | To recognise jobs you apply to and read your "my applications" pages. |
| Optional access to other sites | Asked only when you turn on tracking for a careers site, and only for that site. |
| `storage`, `unlimitedStorage` | To keep your applications on your computer, with no size limit for long histories. |
| `alarms` | For follow-up reminders, marking old applications as Ghosted, and automatic sync. |
| `notifications` | To remind you to follow up. |
| `activeTab`, `scripting` | So "Mark as applied" works on the page you are on, and for careers sites you turn on. |
| `downloads` | To save backups and CSV exports to your computer when you ask. |
| `favicon` | To show the icon of careers sites you track, from your browser's own icon cache. |

## Children

JobLedger is not directed at children under 13 and does not knowingly handle their information.

## Changes

If this policy changes, the new version will be posted at this address with a new effective date.

## Contact

Questions about this policy: hazrulhaiqal66@gmail.com

JobLedger is an independent project. It is not affiliated with, endorsed by or sponsored by LinkedIn, SEEK/JobStreet, Indeed, foundit, Hiredly, Graduan, Maukerja or MYFutureJobs. Their names and icons are used only to show which site an application came from.
