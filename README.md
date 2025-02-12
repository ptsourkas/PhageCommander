# Phage Commander 
Phage Commander is an application for identifying genes in phage or viral genomes using multiple gene identification programs.


## Overview
Phage Commander runs a phage’s DNA sequence through gene identification tools and outputs a list of potential genes. These tools include:
* Glimmer
* Genemark
* host-trained Genemark.hmm
* Genemark S
* Genemark S2
* Genemark with Heuristics (for short sequences)
* Prodigal
* RAST
* Metagene
* Aragorn (for identifying tRNAs)

Supported export formats:
* Genbank (.gb)
* Excel (.xlsx)


## Getting Started
### Prerequisites
* Python 3.6+


## Installing Phage Commander
1. Windows/Mac
   a. Download from https://github.com/sarah-harris/PhageCommander by clicking on the green "Code" button above and select "Download ZIP".
   b. Go to your downloads folder and unzip Phage Commander with your favorite unzip program (I like 7-zip https://www.7-zip.org/).
   c. After unzipping, open the “PhageCommander-Final-main” folder, then open the “phagecommander” subfolder, and then the “dist” subfolder, and then click on the phagecom.exe file to run.
   d. For Windows, note that there are separate executables for Windows 7 and Windows 10.	   

2. Linux
   a. Open a shell. Navigate to the folder where you have downloaded Phage
   Commander. Type py phagecom.py in the shell.
   **Note:** The pip "Scripts" directory should be included in your PATH variable.
   b. If you need to install any of the supporting packages, first type: ‘pip install .’ (in the PhageCommander-master directory – the directory that contains setup.py)

   
## Using Phage Commander 
1. See the included "Phage Commander User Guide" .ppt or .pdf for how to use Phage Commander.
   

## Manuscript about Phage Commander
Also see the following publication describing Phage Commander and its performance in detail:
https://www.liebertpub.com/doi/full/10.1089/phage.2020.0044


## Authors
* **Matthew Lazeroff**
* **Geordie Ryder**
* **Philippos Tsourkas**
* **Sarah Harris**


## License
This project is licensed under the GNU GPLv3
