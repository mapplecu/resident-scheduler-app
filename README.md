# Resident Scheduler

A desktop app that helps chief residents build and manage a residency block schedule.
It runs on your own computer, and your program's data stays on it.

## Download

| Computer | Status |
| --- | --- |
| Windows | Available on the [Releases page](../../releases/latest) |
| Mac (Apple Silicon: M1 and later) | Available on the [Releases page](../../releases/latest). Not yet tried on a real Mac, so please report problems |

Start with the **Desktop Chief Guide** (a PDF on the same Releases page). It walks
through setup, building a schedule and sharing it.

**How-to video:** [watch the walkthrough on YouTube](https://youtu.be/hV2lcXdh1uA).

**Documentation:** guides, how-tos and troubleshooting are online at
<https://residentscheduler.mapple.info/docs/>, also as PDFs.

### Installing on a Mac

1. Download `ResidentScheduler-macos-arm64.zip` from the Releases page and extract it.
2. Move `Resident Scheduler.app` to Applications and open it.
3. If macOS blocks it the first time, open **System Settings > Privacy & Security** and
   choose **Open Anyway**. The app is not yet notarized by Apple, so this step is expected.
4. Your programs are saved outside the app, so a newer release keeps them.

Intel Macs and older macOS versions have not been tried.

### Installing on Windows

1. Download `ResidentScheduler-windows-x64.zip` from the Releases page.
2. Before extracting, right-click the ZIP, choose **Properties**, tick **Unblock** if it
   appears, and click OK. Windows may otherwise stop the app window from opening.
3. Extract all of it to a folder such as Documents, then open `ResidentScheduler.exe`.
   If Windows says it protected your PC, choose **More info**, then **Run anyway**.
4. Keep the extracted files together; the app needs all of them. Your programs are
   saved outside the app folder, so a newer release keeps them.

You can check the download with the `.sha256` file on the Releases page.

## Web version

A web version may be released in the future. Guides for it, as PDF:

- [Chief resident guide (web)](https://residentscheduler.mapple.info/docs/pdf/web-chief-guide.pdf)
- [Faculty guide](https://residentscheduler.mapple.info/docs/pdf/faculty-guide.pdf)
- [Resident guide](https://residentscheduler.mapple.info/docs/pdf/resident-guide.pdf)

The same material is online in the [extended docs](https://residentscheduler.mapple.info/docs/extended/).

## Help

Questions or problems: open an [issue](../../issues) and describe what you were doing.
Please do not include real resident names or other personal information.

## License

Resident Scheduler is free to use, change and share under the [MIT License](LICENSE).
It is provided as is, with no warranty. Review every schedule before you publish or rely on it.
