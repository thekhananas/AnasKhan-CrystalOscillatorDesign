<h1 align="center">AnasKhan-CrystalOscillatorDesign</h1>
<p align="center">
    <a href="https://twitter.com/theanaskhan">
    <img src="https://img.shields.io/twitter/url/https/github.com/ArmynC/ArminC-AutoExec.svg?style=flat-square&logo=twitter"
         alt="GitHub tweet">
 </p>
<h4 align="center">Crystal oscillator analog pads (3.3V, Fclkout-1MHz-4MHz @osu180nm)</h4>

## About the Design and Simulations

This repository contains the simulations done using NI Multisim 14.1+. The files are ready to be opened from the said version of the software. Download NI Multisim Education Edition 14.0 using the below-mentioned instructions. It is a full featured software for learning circuit design.

## Set Up for Simulation

### Clone the git repository
```bash
sudo apt-get install git
git clone https://github.com/chilloutwithanas/AnasKhan-CrystalOscillatorDesign.git
```

### Installation

[Click here](http://sno.filex.no-ip.org/download?file=multisim+program) to download the NI Multisim  into your system.

First install NI multisim from the above mentioned site or from your choice. After steps to draw and run schematic on NI multisim in windows are as follows:
1) Open NI Multisim 14.1 from start menu
2) click on Launch Multisim
3) `File -> New -> Open (Ctrl + O) `
4) Choose the respective `.cir` file and open it.
5) The reuired circuit will start getting placed in the open area along with connections.
6) To open file whch is already created
   `File -> Open -> choose schematic file in .ms14 extension` 
7) Go to` Simulate -> Analyses and simulation` 
8) Choose required analysis and enter variables and choose parameters to be displayed .
9) To run 
   `Simulate -> Run `
10) Outputs are shown on simulation window.
11) For spice netlist
   `Transfer -> Export SPICE Netlist -> Save` (save in `.cir` extension)


## Usage

The oscillator is an
important block in electronic devices which work on the principle of oscillation. The oscillators can be
designed from a wide range of well-known topologies. However, not all types of the oscillators can be
integrated. The crystal oscillator is one of the oscillators which is impossible to integrate into CMOS
technology.

## Contact Information

- **Anas Khan** 
 B.Tech Computer Science and Engineering, SRMIST, KTR
  mailkhananas@gmail.com
- **Kunal Gosh** 
 Director, VSD Corp. Pvt. Ltd. 
  kunalpghosh@gmail.com
- **Philipp Gühring** 
Software Architect at LibreSilicon Association
  pg@futureware.at
- **Dr. Gaurav Trivedi** 
 Co-Principal Investigator, EICT Academy, IIT Guwahati

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[BSD 3-Clause License](https://opensource.org/licenses/BSD-3-Clause)
