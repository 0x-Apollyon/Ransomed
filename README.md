# Ransomed
#### Ransomware note analysis | Part of the Silmarilli Project

## How does it work ?
A simple two step process to analyze which ransomnotes belong to which ransomware gangs.

### Step 1: Artifact based analysis
Checks the ransomnote for known artifacts such as links, emails, IDs etc to link the unknown ransomnote to a known.

### Step 2: Text Analysis
Compares the text of the unkown ransomnote with known ransomnotes by converting the text into a vector and then compares it with the vectors of known ransomnotes using cosine similarity.

### Credits
- All contributors of [the threat labz ransomnote repo](https://github.com/ThreatLabz/ransomware_notes)
- Authors over at PC risk making ransomnotes available with their blogs
- Tool made by Apollyon
