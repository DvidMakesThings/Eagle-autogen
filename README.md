# Eagle-autogen

This script automates the creation of a folder structure for Eagle projects. It prompts the user for a project name and location, then generates the necessary folders and files, including an Eagle project file (`eagle.epf`) and a schematic file (`PROJECT_NAME.sch`).

## Usage

1. Clone the repository to your local machine.
2. Navigate to the directory containing the `Autogen_Folders.bat` script.
3. Run the script by double-clicking it or executing it from the command line.

### Command Line Execution

Open a command prompt and navigate to the directory containing the script. Run the following command:

```cmd
Autogen_Folders.bat
```

### Script Prompts

The script will prompt you for the following information:

- **Project Name**: The name of your project.
- **Project Location**: The full path where you want the project folder structure to be created.

#### Example

```plaintext
Enter the project name: MyProject
Enter the project location (full path): C:\Projects
```

The script will create the following folder structure:

```plaintext
C:\Projects\MyProject
│
├───docs
│   ├───Datasheets
│   ├───Manuals
│   └───Reports
│
├───images
│
├───misc
│
├───src
│   ├───HardwareDesign
│   │   ├───eagle.epf
│   │   └───MyProject.sch
│   ├───Libraries
│   ├───PDF
│   └───Software
│
└───tests
    ├───IntegrationTests
    └───UnitTests
```

### File Contents

- **eagle.epf**: Contains basic Eagle project settings.
- **MyProject.sch**: An empty Eagle schematic file 

### Copying and Updating Readme.md Files

The script also copies and updates `Readme.md` files from the template folder to the corresponding project folders. It replaces the placeholder `%%PROJECT_NAME%%` with the actual project name.

## Contact

For any questions or feedback, please contact:

- **Email**: s.dvid@hotmail.com
- **GitHub**: [DvidMakesThings](https://github.com/DvidMakesThings)
