# DJTrackChecker

Less time on the boring stuff. More time for music that matters.

All your downloaded tracks, correctly tagged, properly named, and sorted — automatically. No more fixing filenames, filling in missing metadata, or wondering whether the audio quality is actually any good.

DJTrackChecker monitors an inbox folder and automatically handles the rest:

- Identifies your tracks via Beatport
- Fetches and writes the correct metadata (artist, title, remix version, genre, BPM, release date, artwork)
- Checks audio quality (detects fake high-quality files)
- Renames and organises your files to fit your preferences

## Current status

The first beta for Windows has just been released. The core pipeline is working — track identification, metadata tagging, quality checks, renaming, and the review flow are all functional. Right now the app runs on-demand: you pick a source and destination folder, hit process, and review the results. Automatic background monitoring is on the roadmap.

> **NOTE: The program hasn't been signed yet. Expect warnings when installing.**
> On Windows, click **"More info"** in the SmartScreen warning, then click **"Run anyway"**. The app is safe — signing is on the roadmap.

👉 [**Download here**](https://github.com/MielsvS/DJTrackChecker-issues/releases/latest)

---

If you're a DJ and this sounds useful, I'd love to hear how you currently manage your tracks:

👉 [**Take the survey**](https://docs.google.com/forms/d/e/1FAIpQLSfXN5ZGDqSYH3ULxUfy_V74Cb8Ro9sEKprTqUOfY2SD_kT1Yg/viewform?usp=pp_url&entry.1201730315=GitHub&entry.1405928464=DJTrackChecker-issues&entry.1426983850=github-repo&entry.475710295=2026-05-04])

---

## Report a bug

Found something that doesn't work as expected?

👉 [**Submit a bug report**](../../issues/new?template=bug_report.yml)

Please include your app version and machine hash (found in **Help → About**). If the issue involves unexpected processing results, email your log file to **[support@djtrackchecker.com](mailto:support@djtrackchecker.com)** with the issue number in the subject line.

## Browse existing issues / feature requests

Check if your problem or idea has already been reported:

👉 [**View all issues**](../../issues)

## Request a feature

Have an idea to make DJTrackChecker better (that isn't added yet)?

👉 [**Submit a feature request**](../../issues/new?template=feature_request.yml)

## Contact

For questions that aren't bugs or feature requests, reach out at **[support@djtrackchecker.com](mailto:support@djtrackchecker.com)**.

---

## Roadmap

DJTrackChecker is being built towards a polished desktop app for DJs — fast matching, accurate tagging, and a quality check that catches fakes you'd otherwise miss.

👉 [**View planned features**](../../issues?q=is%3Aopen+label%3Aplanned)
👉 [**See what's been released**](../../releases)