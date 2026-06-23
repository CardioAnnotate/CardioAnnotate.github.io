# CardioAnnotate

CardioAnnotate is an offline, browser-based ECG annotation tool for multi-fiducial ECG labeling, RR-interval quality control and correction, and heart rate variability analysis. The tool runs locally in the user's web browser and does not require server-side processing or upload of ECG data.

## Online application

The live browser version is available at:

https://cardioannotate.github.io/

## Help page

User instructions and documentation are available at:

https://cardioannotate.github.io/help.html

## Main features

CardioAnnotate supports:

- Browser-based ECG visualization and annotation
- Multi-fiducial peak labeling
- R-peak beat-type annotation
- RR-interval quality control
- Gaussian-process-based correction of flagged RR intervals
- Heart rate variability analysis
- Signal quality assessment
- Reproducible import and export workflows
- Offline use after the page has been loaded in the browser

## Data privacy

CardioAnnotate runs entirely in the user's browser. ECG files and annotations are processed locally on the user's machine. The application does not upload patient data, ECG signals, annotations, or analysis results to a remote server.

## Input and output formats

CardioAnnotate supports ECG and annotation workflows using common file formats, including CSV, JSON, MAT, and NPZ-based session files. Supported formats may depend on the version of the application.

## Repository structure

```text
CardioAnnotate.github.io/
├── index.html       # Main CardioAnnotate application
├── help.html        # User help and documentation page
├── README.md        # Repository description
├── LICENSE          # Software license
└── CITATION.cff     # Citation metadata