# TMF - Digital Forensics Analysis Tool

A PyQt6-based GUI application for digital forensics analysis, featuring multiple modules for mobile device analysis, network monitoring, and malware detection.
<img width="1920" height="1048" alt="image" src="https://github.com/user-attachments/assets/0f1586f4-318d-43f1-8b8c-053b4924b053" />

*In accordance with client confidentiality policies, the source code cannot be shared. This repository provides a high-level demonstration of the project for reference purposes.*
## Features

### Main Modules:
1. **Android Device Analysis**
   - Mobile Triaging & Analysis
   - Live Log Analysis
   - Live Analysis
<img width="1920" height="1048" alt="image" src="https://github.com/user-attachments/assets/6e86b3bd-9394-4826-9996-7fd3b4aeb021" />

2. **iOS Device Analysis**
   - Mobile Triaging & Analysis
   - Live Log Analysis
   - Stix File Based malware analysis
<img width="1920" height="1048" alt="image" src="https://github.com/user-attachments/assets/683410a1-e455-49ce-a05f-ac108a670cb6" />

3. **Live Network Analysis**
   - Live Network Monitoring

4. **Mobile Malware Analysis**
   - IPV Spyware Discovery (ISDi)
<img width="1920" height="1048" alt="image" src="https://github.com/user-attachments/assets/275101e3-cd12-479f-abb1-881c313a77cc" />

5. **SD Card Acquisition & Analysis**
   - SD Card Acquisition
   - Analysis
<img width="1920" height="1048" alt="image" src="https://github.com/user-attachments/assets/ba1956d1-c31b-40ff-8e17-279d910a510b" />

## Installation

1. Create a virtual environment (recommended):
```bash
python -m venv virt
source virt/bin/activate  # On Windows: virt\Scripts\activate
```

2. Install requirements:
```bash
pip install -r requirements.txt
```

## Usage

### Option 1: Direct execution
```bash
python tmf_gui.py
```

### Option 2: Using the launcher
```bash
python run_tmf.py
```

## Application Structure

- **Welcome Screen**: Main menu with module selection
- **Module Screens**: Individual screens for each forensic analysis module
- **Output Area**: Real-time display of tool execution results
- **Reference Panel**: Source links and documentation for each tool

## Development

The application is built using:
- PyQt6 for the GUI framework
- python-pptx for extracting layouts from PowerPoint presentations
- Modern, responsive design with custom styling

## References

- iOS Tools: https://github.com/prosch88/UFADE, https://imazing.com/cli
- Network Analysis: https://pts-project.org/

## License

This tool is for educational and authorized forensic analysis purposes only.

