- 👋 Hi, I’m @phiro753
- 👀 I’m interested in medical image segmetation and tissue boundary identification
- 🌱 I’m currently learning 3D slicer and interfacing with other software for Orthopaedic applciations
- 💞️ I’m just looking around atm
- 📫 Not looking for mail atm

<!---
phiro753/phiro753 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

PhD student currently - supported (PhD committed until 2025-04) by Ossis Corp.
Project overview;
**Motivation
Bone Tumour surgery needs to account for both errors in surgical procedure and in tumour margin interpretation identification (namely radiological resolution and microscopic infiltration). Guidelines advise surgeons to remove significant healthy (functional) tissue (1-2cm) with tumours just-in-case. However, the recent accessibility of computation has supercharged innovation – surgical cutting guides, custom implants, robotics, and interop navigation reduce surgical procedure errors by leveraging radiology. However, representative data to re-evaluate or augment guidelines remains elusive.

**Our problem – bone tumours
We don’t know the probability/risk that a tumour boundary on radiology (CT and MRI) is the actual tumour boundary.

The resolution of CT and MRI is bad. Furthermore, bone tumour interpretation is difficult because every case is heterogeneous, not the same size, shape, contrast, morphology, etc… Difficult for machines AND humans.
Accuracy in imaging: Current medical imaging systems in hospitals produce low-resolution data, good for tumour diagnosis but inadequate to capitalise on the precision that technology offers.
Interpreting imaging: We (humans and semi-automated/automated systems) can only segment to what we are trained with/can infer. As I understand, ML/DL is only as good as the training data we input… Synopsys, Materialise, 3Dside, and other industries sell ‘trained solutions’ but these are only as good as the CT/MRI-interpreted data that feeds them. 

**Current situation – a tangible opportunity
What is histology - In every hospital, bone tumours are sliced and stained after being removed. These are analysed under the microscope (20x or 40x magnification) to ‘check margins’ – aka make sure no tumour was left behind. This very information-rich microscopy data is then archived. 
Opportunity: Leverage histology data to quantify, then train the modelling of 3D anatomy in radiology. This WILL give the confidence that surgical pre-op plans, with modern devices/navigation, accurately predict the probability of surgical success. 
Difficulty: there is no way to identify how to spatially reconstruct histology slices for radiological quantification.
