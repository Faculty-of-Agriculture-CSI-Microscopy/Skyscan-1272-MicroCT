## Last Updated: 2024-06-27
# SkyScan 1272 Micro-CT Standard Operating Procedures (SOPs)

### Quick Start Guide - For detailed instructions, refer to the [SkyScan 1272 User Manual](https://example.com/sky-scan-quick-guide).

### PURPOSE

- Provide a Standard Operating Procedure (SOP) for scanning samples with SkyScan 1272.
- Guide and document all critical steps in this operation.
- Ensure that approved procedures are followed in compliance with Core Facility requirements.

### SCOPE

- These procedures are followed in compliance with the Core facility requirements at all critical steps to ensure that safety and quality standards are met for the end-user, company, and the environment.

### DEFINITIONS

- **MicroCT** – SkyScan 1272 by Bruker.

### RESPONSIBILITY

- It is the responsibility of the Head of Quality or their designee to ensure that the SOP is read and followed by the end-user.
- It shall be the responsibility of the Head of Quality or their designee to review and reissue this SOP in time.
- The head of the lab shall approve any Standard Operating Procedure that may have legal or liability implications.

### PROCEDURE

#### 1. Sample Preparation
- Samples should be either dense or, if biological and not dense, stained.
- It is favorable to mount samples in air rather than in a liquid environment. Moist/wet samples should be mounted within a vapor chamber to prevent drying during the scan.
- Place the sample on a mounting device or use the instrument's tubes for multiple scans.

#### 2. Log into the System
- Log into Bookit with your credentials. The Skyscan software will open automatically.

#### 3. Turn on the X-ray
- Turn the X-ray on for a 15-minute warm-up.

#### 4. Choose Working Configurations
- Select working configurations according to your sample: Options => Configuration => Load => high/low kV => press the file to load.

#### 5. Perform Flat Field Calibration
- After the warm-up is done, perform Flat Field calibration according to your scanning conditions:
  - Turn on the X-ray.
  - Press Ctrl+Alt+Shift+S (a beep sound should be heard).
  - Go to Options => Scanning modes and mark the fields for calibration according to the conditions.
  - Mark "Update flat-field for marked modes and modes with modified exposure."
  - If only the central camera position is needed, leave "use only central camera position" checked, otherwise uncheck it.
  - Uncheck "update only bright flat-field reference."
  - Check "adjust exposure automatically."
  - Uncheck "x-ray ON after updating."
  - Only if you update the flat-field with your sample in the machine (a small single sample that is out of the field of view during the flat-field update) can you leave the X-ray on after updating.

#### 6. Insert Sample and Adjust Settings
- Insert your mounted sample into the machine and turn on the X-ray.
- Adjust the resolution, filter, and pixel size to your scanning conditions.

#### 7. Create a Destination Folder
- Outside the Skyscan software, open a destination folder for every scan in your lab's folder.

#### 8. Set Scanning Parameters
- Press the scan button and determine your scanning parameters (rotation step, averaging, random movement, and 360° scanning). Direct the scan to its designated folder and give it a name.
- If you scan multiple samples or large samples: press Options => batch/oversize scanning => mark your scans with the mouse while pressing the Ctrl button. Add each scan by repeating this stage.

#### 9. Start the Scan
- Press "scan" and ensure the machine starts to scan.

#### 10. Shut Down
- When finished, close the X-ray and then the software. The machine will turn off.
- Log off your Bookit account.

### REVISION

| REVISION | REVISION DATE | REVISED BY     | COMMENTS  |
|----------|----------------|----------------|-----------|
| 0        | January 8, 2023 | Tally Kossovsky | Original  |
| 1        |                |                |           |

