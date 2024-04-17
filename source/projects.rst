Research Projects
==================

.. raw:: html

    <div class="section-intro">
        <p>I have a diverse portfolio of projects ranging from experimental crystallography imaging to computational models for astronaut health metrics. Below is a brief overview of the key projects. For a more comprehensive insight, consider downloading the full CV.</p>
        <div class="cv-buttons">
            <a href="_static/CV.pdf" class="button" download="Adam_Kurth_CV.pdf">Download CV</a>
            <button id="viewCVButton" class="button">View CV</button>
        </div>
        <div id="cvContainer" style="display: none;">
            <embed src="_static/CV.pdf" type="application/pdf" width="100%" height="600px" />
        </div>
        <script>
            document.getElementById('viewCVButton').addEventListener('click', function() {
                var cvContainer = document.getElementById('cvContainer');
                cvContainer.style.display = cvContainer.style.display === 'none' ? 'block' : 'none';
            });
        </script>
    </div>

    <div class="project-entry">
        <div class="project-description">
            <h3>NASA Internship <a href="https://github.com/adamkurth/nasa"><img src="_static/images/github-logo.png" alt="GitHub" class="github-logo" /></a></h3>
            <p><span class="highlight">Role:</span> Human Reliability Analyst at NASA Glenn Research Center</p>
            <p><span class="highlight">Period:</span> June 2024 - present</p>
            <p><span class="highlight">Description:</span> Development of computational models in Python to analyze astronaut health metrics, using advanced statistical methods for quantitative risk estimation.</p>
        </div>
    </div>

    <div class="project-entry">
        <div class="project-description">
            <h3>CXFEL Biodesign Institute <a href="https://github.com/adamkurth/cxls_hitfinder"><img src="_static/images/github-logo.png" alt="GitHub" class="github-logo" /></a></h3>
            <p><span class="highlight">Role:</span> Research Aide and Data Analyst</p>
            <p><span class="highlight">Period:</span> June 2023 - present</p>
            <p><span class="highlight">Description:</span> Development of Python packages for experimental crystallography imaging and assistance in data analysis for biophysics studies at Arizona State University's Biodesign Institute CXFEL Beus Laser Laboratory.</p>
        </div>
    </div>

    <div class="project-entry">
        <div class="project-description">
            <h3>Research Manuscript <a href="https://github.com/adamkurth/IRT_MIRT_project"><img src="_static/images/github-logo.png" alt="GitHub" class="github-logo" /></a></h3>
            <p><span class="highlight">Title:</span> "A Monte Carlo Comparison of the Efficacy of Mplus, flexMIRT, PROC IRT, ltm, and mirt in IRT Models Estimation."</p>
            <p><span class="highlight">Status:</span> Upcoming</p>
            <p><span class="highlight">Role:</span> Co-Author under supervision of Yi Zheng and M. Reiser</p>
            <p><span class="highlight">Description:</span> Managed simulations and contributed to research on Item Response Theory (IRT) estimation comparing several statistical software packages.</p>
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
        text-decoration: none;
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
        text-decoration: none; /* No underline on hover */
    }

    .project-description p {
        font-size: 0.9rem;
        line-height: 1.6; /* Improved readability */
        margin-bottom: 0.5rem;
    }

    /* Ensure that this <style> tag is placed within your .rst file's raw HTML block */

    </style>

    <p>To explore more about these projects, visit the project-specific links or reach out directly via the contact details provided on the site.</p>

