# Screenshot provenance

Both PNGs are unmodified offscreen renders of real Local Dictation SwiftUI views from source commit `5196f529969428b4c0a6f3d4284777f57e5178ea`, generated on 2026-09-08.

- `local-dictation.png`: `DesignAppearanceMatrixTests.testHomeHeroCardAppearanceMatrix`, light appearance, isolated empty state.
- `file-transcription.png`: `DesignBacklogRenderTests.testTranscribePaneRendersRecentFilesSection`, synthetic filenames `board-meeting.m4a` and `interview-oslo.wav`; no source audio exists or was read.

Both selected render tests passed. Rendering used `NSHostingView`, isolated test preferences and temporary stores. No personal app window, recording or transcript was captured. These are illustrative development-build views, not screenshots of the downloadable 1.0.27 binaries.
