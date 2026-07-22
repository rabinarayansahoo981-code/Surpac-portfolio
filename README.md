
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
[Original ground level](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/3b15a88a6207ebddc3bd2dfdff8038b94a92c914/ogl_hocp%20(2).CSV)  

[Heap level  ](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/3b15a88a6207ebddc3bd2dfdff8038b94a92c914/heap_hocp.CSV)     


## workflow
      1.Import survey data of both file.

      2.Create string files from the imported data.

      3.Generate DTM 1.

      4.Generate DTM 2.

      5.Calculate the net volume.

      6.Export the report.
## Surpac_Files/
1.[string file 1 ](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/522a2c43d7f30e06e228b793faa25c04926882e5/project_ogl.str)

2.[string file 2](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/project_heap.str) 

3.[DTM 1 ](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/project_ogl.dtm)

4.[DTM 2 ](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/project_heap.dtm)        

5.[Volume Report](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/volume_project.not) 


## Screenshots
1.[string file 1](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/Screenshot%202026-07-10%20114822.png) 


2.[string file 2](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/Screenshot%202026-07-10%20120017.png) 


3.[DTM 1 ](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/Screenshot%202026-07-10%20121140.png)       

4.[DTM 2](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/Screenshot%202026-07-08%20132218.png)  


5.[VALIDATION](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/Screenshot%202026-07-10%20083338.png)    


6.[Volume Report](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/676276d0368d7899336bb8324b1a75e003349c33/Screenshot%202026-07-10%20133915.png) 


## Results
      1.Two DTMs are created sucessfully.

      2.Net Volume report is Generated.
      
      

           ___________________________________________________End of Project 1___________________________________________________________




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
  [screenshots](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/19ebd787f7a4c1c32f3d0f9a381313a3aa2136da/Screenshot%202026-021%20223710.png)

## step 2 - Import Drillhole Database

         Imported collar, survey, assay, and geoology tables into surpac.
[screenshots](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/9b07fcb680b160521753f0f7e3116655a1576a18/Screenshot%202026-21%20223327.png)

[screenshots](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/19ebd787f7a4c1c32f3d0f9a381313a3aa2136da/Screenshot%202026-07-21%20223506.png])
## step 3 - Display drillholes

         Visualized drillholes in three-dimensional space to understand the spatial distribution of mineralization.
[screenshots](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/19ebd787f7a4c1c32f3d0f9a381313a3aa2136da/Screenshot%202026-07-21%20223920.png)
## step 4 - Create cross sections

         generated geological sections perpendicular to the ore trend  for interpretion.
[screenshots](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/19ebd787f7a4c1c32f3d0f9a381313a3aa2136da/Screenshot%202026-07-21%20224050.png)
## step 5 - geological interpretetion and digitization of ore boundaries

         Interpreted Ore contacts using lithogical and assay information.

         Digitized ore outlines on each geological section.
[screenshots](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/19ebd787f7a4c1c32f3d0f9a381313a3aa2136da/Screenshot%202026-07-21%20224146.png)
## step 6 - Generate wireframe

          Connected interpreted sections to construct a closed 3D orebody wireframe.
[screenshots](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/19ebd787f7a4c1c32f3d0f9a381313a3aa2136da/Screenshot%202026-07-18%20081109.png)

## step 7 - Final Ore Body Model

          Generated the final  three-dimensional orebody.
[screenshots ](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/19ebd787f7a4c1c32f3d0f9a381313a3aa2136da/Screenshot%202026-07-21%20224309.png)
## step 8  - Validation

          validate the created orebody model to ensure an error free model.
[screenshots](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/19ebd787f7a4c1c32f3d0f9a381313a3aa2136da/Screenshot%202026-07-21%20231036.png)

## Results

           Sucessfully imported and validated the geological database.
           constructed geological interpretations from drillhole information.
           generated a closed 3D orebody Wireframe.
           produced a geological model suitable for block modelling and resource estimation.

           



      ___________________________________________________________End of Project 2_____________________________________________________

## Project

         03_Block Modelling and Resource Estimation

## Project overview

         This project demonstrates the complete creation of a three-dimensional geological block model and estimating mineral resources using GEOVIA SURPAC.
         The objective of this project is to transform drillhole information into a structured block model that can be used for mineral resource evaluation and   future mine planning.

## Objective

         
         - Import and validate geological drillhole data
         
         - Prepare composite assay intervals

         - Perform exploratory statistical analysis
         
         - Create a three-dimensional block model
         
         - Estimate grades using interpolation methods
         
         - Validate the estimated block model
         
         - Generate a mineral resource report
         
         - Visualize the final grade distribution in 3D

 ## Software used
         GEOVIA SURPAC(Demo version provided by MCL,Hingula O.C.P)


## Input Data

        The project uses a validated exploration drilling dataset consisting of:

       Collar coordinates
       Survey information
       Assay intervals
       Lithology logs
       Geological domains
       Composite intervals

       **Input File**
Collar.csv

Survey.csv

Assay.csv

geology.csv

Composite.csv

## Workflow


     Validated Drillhole Database

            │
            ▼
            
     Data Validation

            │
            ▼
            
     Drillhole Compositing

            │
            ▼
            
    Statistical Analysis

            │
            ▼
            
    Block Model Creation

            │
            ▼
            
    Grade Estimation
    
     (IDW / Kriging)
     
            │
            ▼
            
    Model Validation
    
            │
            ▼
            
    Resource Reporting




# Methodology

## 1. Drillhole Database Preparation

              The validated geological database was imported into SURPAC. The dataset included collar coordinates, survey measurements, lithology information, and assay intervals.

             Database integrity checks were performed to ensure consistency before modelling.

[screenshots](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/c22cf673123c65186c86f18cf4d04cc8add765f1/Screenshot%202026-07-21%20223920.png)

## 2. Drillhole Compositing

           Assay intervals were composited into fixed-length intervals to reduce sampling bias and prepare the dataset for grade estimation.

           Typical compositing steps included:

         - Composite length selection
         - Handling residual intervals
         - Maintaining geological boundaries

[screenshots](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/c841343c3b58f06d003e69f5325205b26cb396f1/Screenshot%202026-07-20%20221615.png)

## 3. Exploratory Data Analysis

             The composite dataset was analysed statistically to understand grade distribution.

              The following analyses were performed:

        - Minimum grade
        - Maximum grade
        - Mean
        - Median
        - Standard deviation
        - Coefficient of variation
        - Histograms
        - Frequency distribution

[screenshots](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/c841343c3b58f06d003e69f5325205b26cb396f1/Screenshot%202026-07-20%20222653.png)


## 4. Block Model Creation

          A parent block model was generated using the geological limits of the deposit.

[screenshots](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/c841343c3b58f06d003e69f5325205b26cb396f1/Screenshot%202026-07-20%20224509.png)

## 5. Constrain file creation

          

[screenshots 1](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/c841343c3b58f06d003e69f5325205b26cb396f1/Screenshot%202026-07-20%20230913.png)

[Screenshots 2](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/c841343c3b58f06d003e69f5325205b26cb396f1/Screenshot%202026-07-20%20230932.png)


## 6. Grade Estimation

          Grades were estimated using interpolation techniques available in SURPAC.

         Typical methods include:

        - Inverse Distance Weighting (IDW)
        - Ordinary Kriging
        (here IDW Method is used for the grade estimation)
[screenshots 1](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/c841343c3b58f06d003e69f5325205b26cb396f1/Screenshot%202026-07-20%20232148.png)

[Screenshots 2](https://github.com/rabinarayansahoo981-code/Surpac-portfolio/blob/c841343c3b58f06d003e69f5325205b26cb396f1/Screenshot%202026-07-20%20232209.png)



## 7. Resource Reporting

          The validated block model was summarized into a mineral resource report.

          Typical reporting parameters include:

        - Block count
        
        - Average grade
        
        - Block volume
        
        - Bulk density
        
        - Estimated tonnage
        
        - Contained metal

---screenshots

# Result

        The project generated the following outputs:

        - Validated drillhole database
        - Composite assay dataset
        - Statistical summary
        - Histograms
        - Three-dimensional block model
        - Grade estimation model
        - Resource estimation report


# Repository Structure


        Block-Modelling-and-Resource-Estimation/
        
       |
       ├── README.md
       │
       ├── Report/
       │   └── Project_Report.pdf
       │
       ├── Data/
       │   ├── Collar.csv
       │   ├── Survey.csv
       │   ├── Assay.csv
       │   ├── Lithology.csv
       │   └── Composite.csv
       │
       ├── Surpac_Project/
       │   ├── Strings/
       │   ├── DTM/
       │   ├── Solids/
       │   ├── BlockModel/
       │   └── Reports/
       |
       ├── Screenshots/
           ├── Drillholes.png
           ├── Composite.png
           ├── Histogram.png
           ├── Variogram.png
           ├── BlockModel.png
           ├── GradeModel.png
           ├── Validation.png
           └── ResourceReport.png



 

