# Adaptive_Optimiser_For_Mobility_Tracking

**Programmer:shipit:**: Zakaria Abdelmoiz DAHI, University of Malaga, Spain. 

**About:** This repositiory implements the binary variants of the algorithms devised and studied in [1] that solves the users' mobility tracking in cellular networks.

- [1] **Dahi, Z.A.E.M.**, Mezioud, C., Alba, E. (2016). A Novel Adaptive Genetic Algorithm for Mobility Management in Cellular Networks. In: Martínez-Álvarez, F., Troncoso, A., Quintián, H., Corchado, E. (eds) Hybrid Artificial Intelligent Systems. HAIS 2016. Lecture Notes in Computer Science(), vol 9648. Springer, Cham. https://doi.org/10.1007/978-3-319-32034-2_19

**How :green_book:** 

    - To excuted just navigate to the folder BBAs or GGA.
    - Choose the folder of the variant you want to test `BA_Angle_modulation, ...
    - Excute the main.py file.
    - **NB**: I am using a cluster for my experiments, so if you are using a local machine just uncomment the lines I dedicated to it.


**Folders Hiearchy :open_file_folder:**
    
    - Code:
        - Linear: contains both the linear decreasing and increasing variants.
        - Oscilatory: contains both the oscilatory increasing and decreasing variants.
        - SOTA: contains the implementation of well-known adaptive variants.
        - Neglected: contains some exploratory adaptive variants of the proposal.
    - Results:
        - Once executed the results are stored in excel files with name Network_a_bxc, where a represent the ID of networks of such shape, b and c represent the number of cells in the width and height of the network.
        
**Demo :movie_camera:**
    
    - Excute of the variant you would like to test and you will get the results as an Excel file.
