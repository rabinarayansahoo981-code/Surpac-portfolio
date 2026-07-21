
# Projects
       01_DTM_to_DTM Volume Calculation
## Project overview
       This project demonstrates how to calculate the net volume between two digital terrain models(DTMs) using geovia surpac.
## Objective
       Create two DTMs using the survey Data.

       Calculate the net volume between them.
## Software used
       GEOVIA SURPAC(Demo version provided by MCL,Hingula O.C.P)


## Input Data/
Original ground level  (https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/3b15a88a6207ebddc3bd2dfdff8038b94a92c914/ogl_hocp%20(2).CSV)

Heap level             (https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/3b15a88a6207ebddc3bd2dfdff8038b94a92c914/heap_hocp.CSV)
## workflow
      1.Import survey data of both file.

      2.Create string files from the imported data.

      3.Generate DTM 1.

      4.Generate DTM 2.

      5.Calculate the net volume.

      6.Export the report.
## Surpac_Files/
1.string file 1 (https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/522a2c43d7f30e06e228b793faa25c04926882e5/project_ogl.str)

2.string file 2 (https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/project_heap.str)

3.DTM 1         (https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/project_ogl.dtm)

4.DTM 2         (https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/project_heap.dtm)

5.Volume Report (https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/volume_project.not)
## Screenshots
1.string file 1 (https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/Screenshot%202026-07-10%20114822.png)

2.string file 2 (https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/Screenshot%202026-07-10%20120017.png)

3.DTM 1         (https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/Screenshot%202026-07-10%20121140.png)

4.DTM 2         (https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/Screenshot%202026-07-08%20132218.png)

5.VALIDATION    (https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/Screenshot%202026-07-10%20083338.png)

6.Volume Report (https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/Screenshot%202026-07-10%20133915.png)
## Results
      1.Two DTMs are created sucessfully.

      2.Net Volume report is Generated.

           ___________________________________end of project1___________________________________________________________

## Project
      02_Orebody_Modelling

## Project overview
       This project demonstrates the complete workflow of creating a three-dimensional ore body model from drill hole data using GEOVIA SURPAC.

## Objectives
       1.import and organize drillhole database.

       2.Validate geological and survey data.

       3.Display drillholes in 3D.

       4.Interpret Ore Boundaries.

       5.Generate a Closed 3D orebody wireframe.

       6.Validate the final geological model.

## Software used
       GEOVIA SURPAC(Demo version provided by MCL,Hingula O.C.P)

## Input Data
1.collar()

2.assay()

3.survey()

4.geology()

## workflow

       1.create the drillhole database and import the same.
   
       2.Validate the drillhole database.
   
       3.display of three dimensional drillhole.
   
       4.generation of cross-section.
   
       5.Geological interpretion.

       6.ore Boundary Digitization.

       7.Wireframe Generation.

       8.create 3D ore body model from the wireframe through tringulation.

      9.Validate the created 3D solid ore body model.

## Methodology
## step 1 - create drillhole database

         created a drillhole database using SURPAC file function.
[screenshots - https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/19ebd787f7a4c1c32f3d0f9a381313a3aa2136da/Screenshot%202026-07-21%20223710.png]

## step 2 - Import Drillhole Database

         Imported collar, survey, assay, and geoology tables into surpac.
[screenshots - ]

[screenshots - https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/19ebd787f7a4c1c32f3d0f9a381313a3aa2136da/Screenshot%202026-07-21%20223506.png]

## Database validation
         Validated the imported drillhole database.
[screenshots]

## step 4 - Display drillholes

         Visualized drillholes in three-dimensional space to understand the spatial distribution of mineralization.
[screenshots - https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/19ebd787f7a4c1c32f3d0f9a381313a3aa2136da/Screenshot%202026-07-21%20223920.png]

## step 5 - Create cross sections

         generated geological sections perpendicular to the ore trend  for interpretion.
[screenshots - https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/19ebd787f7a4c1c32f3d0f9a381313a3aa2136da/Screenshot%202026-07-21%20224050.png]

## step 6 - geological interpretetion and digitization of ore boundaries

         Interpreted Ore contacts using lithogical and assay information.

         Digitized ore outlines on each geological section.
[screenshots - https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/19ebd787f7a4c1c32f3d0f9a381313a3aa2136da/Screenshot%202026-07-21%20224146.png]

## step 7 - Generate wireframe

          Connected interpreted sections to construct a closed 3D orebody wireframe.
[screenshots - https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/19ebd787f7a4c1c32f3d0f9a381313a3aa2136da/Screenshot%202026-07-18%20081109.png]

## step 9 - Final Ore Body Model

          Generated the final  three-dimensional orebody.
[screenshots - https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/19ebd787f7a4c1c32f3d0f9a381313a3aa2136da/Screenshot%202026-07-21%20224309.png]

## step 10  - Validation

          validate the created orebody model to ensure an error free model.
[screenshots - https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/19ebd787f7a4c1c32f3d0f9a381313a3aa2136da/Screenshot%202026-07-21%20231036.png]


## Results

           Sucessfully imported and validated the geological database.
           constructed geological interpretations from drillhole information.
           generated a closed 3D orebody Wireframe.
           produced a geological model suitable for block modelling and resource estimation.



      ________________________End of Project 2______________________________________

    

 

