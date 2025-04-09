# CD Number Wizard

**CD Number Wizard** is an internal utility tool built for automating the creation of CD Numbers, generating local file/folder structures, and optionally integrating with ECi JobBOSS² via API.

This program simplifies the process of generating part numbers, managing related files, and reducing manual entry in the estimating system.

## Key Features

- **Automatic CD Number Generation**  
  Instantly generate the next available CD number based on existing estimates in JobBOSS².

- **Manual Entry Support**  
  Manually create CD numbers including optional suffixes (e.g., `-XLPE`, `REV A`, or `F` for foam).

- **Folder Structure Automation**  
  Automatically creates the correct folder hierarchy under the company network drive for each CD number, including handling revisions.

- **Customer File Attachments**  
  Attach multiple customer files to the correct folder location, either during creation or after.

- **JobBOSS² API Integration**  
  Automatically create the part as a new estimate in JobBOSS² with proper metadata and customer info (optional).

- **Batch Mode**  
  Create multiple CD numbers in a single step with confirmation safeguards.

- **Recent History View**  
  Quickly access recently created CD numbers and open their folders directly.

- **Update Checking**  
  Automatically checks for new versions hosted on GitHub and guides the user through updating.

## Requirements

- Windows 10 or later  
- Internal access to company JobBOSS² API  
- Python 3.10 (for developers only – end users run the compiled `.exe`)  

## Getting Started

1. **Download the latest version** from the [Releases](https://github.com/YOUR-USERNAME/cd-number-wizard/releases) page.
2. **Extract the zip** and run `cdstart.exe`.
3. On first launch, you may be prompted to:
   - Select the correct drive for `PRINTS/CD NUMBERS`
   - Select your employee name

From there, you’re ready to begin creating CD numbers.

## Internal Use Only

This application is intended for internal use by Quality Cases & Containers and includes hardcoded credentials and API keys specific to our environment.

---
