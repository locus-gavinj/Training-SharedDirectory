# Training-SharedDirectory
This zipped FME folder contains the proper Shared FME Folder structure and one "Locus_TrainingTransformer" Custom Transformer for testing.

After downloading the FME.zip
- Extract the directory
- Open FME Options (Utilties > FME Options)
- Navigate to the "Default Paths" page
- In the "Shared FME Folders" section, click the [+] button
- Select the location of this parent folder. For example: C:\Users\Administrator\Downloads\FME

To Test:
- Open FME Form
- In a blank canvas:
  - Add a Transformer: Creator
  - Add the Custom Transformer: Locus-TrainingTransformer
- Run the workspace
- Verify the attribute "message" is Success!!
