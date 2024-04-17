Research
========

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
            <h3>NASA Internship, Glenn Research Center <a href="https://github.com/adamkurth/nasa"><img src="_static/images/github-logo.png" alt="GitHub" class="github-logo" /></a></h3>
            <p><span class="highlight">Role:</span> Human Reliability Analyst at NASA Glenn Research Center</p>
            <p><span class="highlight">Period:</span> June 2024 - present</p>
            <p><span class="highlight">Description:</span> In this role, I am responsible for developing computational models to analyze astronaut health metrics, using advanced statistical methods. These models will provide quantitative risk assessments essential for mission planning and ensuring astronaut safety and performance for future missions, including Mars expeditions. My work involves extensive research and application of mathematical and statistical techniques, primarily using Python, to support NASA's mission-critical decision-making processes.</p>
        </div>
    </div>

    <div class="project-entry">
        <div class="project-description">
            <h3>Biodesign Institute, CXFEL Beus Laser Laboratory <a href="https://github.com/adamkurth/cxls_hitfinder"><img src="_static/images/github-logo.png" alt="GitHub" class="github-logo" /></a></h3>
            
            <p><span class="highlight">Roles:</span> Graduate Research Assistant, Research Aide, and Data Analyst</p>
            <p><span class="highlight">Period:</span> June 2023 - present</p>
            <p><span class="highlight">Description:</span> In my capacity as both a Graduate Research Assistant and a Research Aide and Data Analyst, I engage in developing Python packages tailored for high-throughput experimental crystallography imaging and conduct data analysis to bolster biophysics research. My work at the CXFEL Beus Laser Laboratory is instrumental in advancing medical research through the application of cutting-edge imaging technologies and has been pivotal in enhancing my expertise in the computational aspects of biostatistics and biophysics.</p>
        </div>
    </div>
    
    <iframe width="560" height="315" src="https://www.youtube.com/embed/HLF2sv78fiQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

.. raw:: html
    <hr> 

    <div class="github-link" style="margin-top: 2rem; margin-bottom: 2rem;">
        <p>For more of my work, follow me on GitHub:</p>
        <a href="https://github.com/adamkurth" style="display: inline-block;">
            <img src="https://img.shields.io/badge/Follow%20on%20GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="Follow on GitHub" style="margin-right: 10px;">
        </a>
    </div>


.. raw:: html

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
    .project-description p {
        font-size: 0.9rem;
        line-height: 1.6; /* Improved readability */
        margin-bottom: 0.5rem;
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

    </style>

    <p>
    <p>To explore more about these projects, visit the project-specific links or reach out directly via the contact details provided on the site.</p>

