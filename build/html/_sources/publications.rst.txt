Publications and Presentations
==============================

.. raw:: html

    <div class="project-entry">
        <div class="project-description">
        <h2>Publications</h2>
            <h3>Monte Carlo Efficacy of IRT Software Estimation<a href="https://github.com/adamkurth/IRT_MIRT_project"><img src="_static/images/github-logo.png" alt="GitHub" class="github-logo" /></a></h3>
            <p><span class="highlight">Title:</span> "A Monte Carlo Comparison of the Efficacy of Mplus, flexMIRT, PROC IRT, ltm, and mirt in IRT Models Estimation."</p>
            <p><span class="highlight">Status:</span> Upcoming</p>
            <p><span class="highlight">Role:</span> Co-Author under supervision of Yi Zheng and Mark Reiser</p>
            <p><span class="highlight">Description:</span> Managed simulations and contributed to research on Item Response Theory (IRT) estimation comparing several statistical software packages.</p>
        </div>
    </div>
    
    <div class="project-entry">
        <div class="project-description">
        <h2>Poster Presentations</h2>
            <h3>Experimental Peak Intensity Analysis for CXLS<a href="https://github.com/adamkurth/waterbackground_subtraction"><img src="_static/images/github-logo.png" alt="GitHub" class="github-logo" /></a></h3>           
             <p><span class="highlight">Title:</span> "Peak Intensity Analysis for Serial Femtosecond Crystallography Experiments at the Compact X-ray Light Source."</p>
            <p><span class="highlight">Authors:</span> Kurth, A. M., Botha, S.</p>
            <p><span class="highlight">Affiliations:</span> CXFEL Labs Biodesign Institute, Arizona State University; Department of Physics, Arizona State University</p>
            <p><span class="highlight">Abstract:</span> This research introduces innovative Bragg peak integration methods to advance peak intensity analysis in X-ray crystallography, crucial for accurate structure determination. The Compact X-ray light source (CXLS) will produce femtosecond duration X-ray pulses, allowing the collection of “diffraction before destruction” data. However, the flux will be limited compared to traditional full-scale X-ray free electron laser facilities, warranting the development of unique data analysis tools to fully exploit the unique capabilities of these sources for macromolecular crystallography. By improving the differentiation between signal and noise, coupled with a novel data collection scheme, our approach will enable experiments at the compact X-ray light source at Arizona State University.</p>
            <div class="cv-buttons">
                <a href="_static/2024 BioXFEL Spring Symposium Abstract Revised.pdf" class="button" download>Download Abstract (PDF)</a>
                <a href="_static/Kurth_BioXFEL2024.pdf" class="button" download>Download Presentation (PPTX)</a>
                <button id="viewPosterPresentationButton" class="button">View Presentation</button>
            </div>
            <div id="posterPresentationContainer" style="display: none;">
                <embed src="_static/Kurth_BioXFEL2024.pdf" type="application/pdf" width="100%" height="600px" />
            </div>
            <script>
                document.getElementById('viewPosterPresentationButton').addEventListener('click', function() {
                    var posterPresentationContainer = document.getElementById('posterPresentationContainer');
                    posterPresentationContainer.style.display = posterPresentationContainer.style.display === 'none' ? 'block' : 'none';
                });
            </script>
            <p>Repository: <a href="https://github.com/adamkurth/IRT_MIRT_project" target="_blank">IRT_MIRT_project</a></p>
        </div>
    </div>

    <div class="project-entry">
        <div class="project-description"> 
            <h3>Enhancing X-ray Peakfinding Through Deep Learning<a href="https://github.com/adamkurth/cxls_hitfinder"><img src="_static/images/github-logo.png" alt="GitHub" class="github-logo" /></a></h3>           
            <p><span class="highlight">Title:</span> "Enhancing X-ray Peakfinding Through Deep Learning at the Compact X-ray Light Source (CXLS), Arizona State University"</p>
            <p><span class="highlight">Authors:</span> Kurth, A. M., Everett, E., Botha, S.</p>
            <p><span class="highlight">Affiliations:</span> The Biodesign Beus CXFEL Laboratory, Arizona State University; Department of Physics, Arizona State University</p>
            <p><span class="highlight">Abstract:</span> This paper explores the application of deep learning techniques at Arizona State University's (ASU) Compact X-ray Light Source (CXLS) to analyze experimental data from various modalities, primarily focusing on X-ray crystallography using the Dectris Eiger 4M detector. Traditional methods of predicting photon energy and sample-detector distance are challenged by dynamic scattering, intrinsic noise, and the CXLS low flux X-ray beam, prompting the need for more advanced solutions. Utilizing the CrystFEL software, we simulate diffraction images for protein 1IC6.pdb across a matrix of nine variable combinations involving photon energies and camera length. Our approach employs convolutional neural networks (CNNs), testing various architectures for binary classification of peak detection and prediction of experimental parameters. The scope of this research wishes to further expand this with modifications in the architecture to accommodate for spectroscopy data, although this is beyond the extent of this manuscript. By integrating different experimental conditions, we anticipate broader applications and improved experimental outcomes.</p>
            <div class="cv-buttons">
                <a href="_static/APM598_Final_Project_Report_Everett_Kurth.pdf" class="button" download="APM598_Final_Project_Report_Everett_Kurth.pdf">Download Report (PDF)</a>
                <button id="viewDeepLearningPresentationButton" class="button">View Report</button>
            </div>
            <div id="deepLearningPresentationContainer" style="display: none;">
                <embed src="_static/APM598_Final_Project_Report_Everett_Kurth.pdf.pdf" type="application/pdf" width="100%" height="600px" />
            </div>
            <script>
                document.getElementById('viewDeepLearningPresentationButton').addEventListener('click', function() {
                    var deepLearningPresentationContainer = document.getElementById('deepLearningPresentationContainer');
                    deepLearningPresentationContainer.style.display = deepLearningPresentationContainer.style.display === 'none' ? 'block' : 'none';
                });
            </script>
            <p>Repository: <a href="https://github.com/adamkurth/cxls_hitfinder" target="_blank">cxls_hitfinder</a></p>
        </div>
    </div>



    <style>
    .highlight {
        color: #0056b3; /* A softer shade of blue */
        text-shadow: 0px 1px 1px rgba(0, 0, 0, 0.1); /* subtle shadow for depth */
    }

    .project-entry {
        margin-bottom: 2rem;
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
    }

    .project-description h3 {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 0.5rem;
        font-weight: 500; /* Medium weight */
        text-rendering: optimizeLegibility;
    }

    .project-description h3 .github-logo {
        width: 30px; /* Adjust the size of the GitHub logo here */
        height: 30px; /* Ensure the logo is square */
        margin-left: 10px;
    }

    .cv-buttons {
        margin-bottom: 1rem;
    }

    .cv-buttons .button,
    .cv-buttons button {
        margin-right: 0.5rem;
        text-decoration: none; /* Remove underline from download buttons */
        padding: 0.5rem 1rem;
        border: none;
        background-color: #17a2b8; /* Bootstrap's info color for a change */
        color: white;
        border-radius: 0.25rem;
        cursor: pointer;
        transition: background-color 0.3s ease; /* Smooth background color transition */
    }

    .cv-buttons a.button:hover,
    .cv-buttons button:hover {
        background-color: #138496; /* Darker shade on hover */
    }

    .project-description a {
        text-decoration: none; /* Remove underline from all links within the project-description */
    }

    .project-description p {
        font-size: 0.9rem;
        line-height: 1.6; /* Improved readability */
        margin-bottom: 0.5rem;
    }
    </style>
