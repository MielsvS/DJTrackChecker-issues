# DJTrackChecker

Less time on the boring stuff. More time for music that matters.

All your downloaded tracks, correctly tagged, properly named, and sorted — automatically. No more fixing filenames, filling in missing metadata, or wondering whether the audio quality is actually any good.

DJTrackChecker monitors an inbox folder and automatically handles the rest:

- Identifies your tracks via Beatport
- Fetches and writes the correct metadata (artist, title, remix version, genre, BPM, release date, artwork)
- Checks audio quality (detects fake high-quality files)
- Renames and organises your files to fit your preferences

## Current status

DJTrackChecker is approaching a controlled beta. The core pipeline is working — track identification, metadata tagging, quality checks, renaming, and the review flow are all functional. Right now the app runs on-demand: you pick a source and destination folder, hit process, and review the results. Automatic background monitoring is on the roadmap.

If you're a DJ and this sounds useful, I'd love to hear how you currently manage your tracks:

👉 [**Take the survey**](https://docs.google.com/forms/d/e/1FAIpQLSfXN5ZGDqSYH3ULxUfy_V74Cb8Ro9sEKprTqUOfY2SD_kT1Yg/viewform)

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

What's coming next — and what's already done.

### Soon

- **Settings screen** — Configure matching thresholds, quality check sensitivity, and other preferences from within the app
- **Processing history** — See what DJTrackChecker has done: which tracks were processed, when, and what tags were written
- **Track detail view** — See exactly what tags were written to your track, and correct the match if needed
- **Remember your folders** — DJTrackChecker remembers your last used source and destination folders between sessions
- **Built-in help** — Access documentation, status explanations, and troubleshooting tips without leaving the app

### Later

- **Customise filename and folder structure** — Define how your processed files are named and where they end up, using templates with variables like artist, title, BPM, and key
- **Customise which tags are written** — Choose exactly which metadata fields DJTrackChecker fills in, and set your own defaults
- **Undo processed tracks** — Made a mistake or picked the wrong match? Undo and restore the original file
- **FLAC, WAV, and AIFF support** — Process more than just MP3 files
- **Preview audio before choosing a match** — Listen to Beatport previews directly in the review screen to pick the right track
- **Run in the background** — Let DJTrackChecker watch your inbox folder and process new tracks automatically as they arrive
- **macOS support** — Run DJTrackChecker natively on Mac

### Done

- Track identification via Beatport
- Metadata tagging (artist, title, remix, genre, BPM, key, release date, label, ISRC, artwork)
- Audio quality check (detects fake high-quality files)
- Automatic file renaming
- Review flow for uncertain matches (choose the right track from candidates)
- Review flow for quality warnings (accept or reject flagged files)
- Real-time processing progress
- Browse and select source and destination folders
- Sort and filter your track list
