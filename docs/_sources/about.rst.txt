About
======

.. raw:: html

    <div class="section-intro">
        <img src="_static/images/42242_SB11.JPG" alt="Adam Kurth" class="inline-photo" />
        <p>As a passionate and driven graduate student at Arizona State University, I have dedicated my academic career to excelling in the fields of mathematics, statistics, and data science. I am currently pursuing a Master's of Science in Statistics and hold a Bachelor's of Science in Mathematics (Statistics), with a minor in Philosophy. I am fascinated by the applications for biostatistics in medical imaging technology, prediction of disease.</p>
    </div>

.. raw:: html

    <div class="research-entry">
         <p>For research specific interests, please refer to the <a href="research.html">Research</a> page.</p>
    </div>

.. raw:: html

    <div class="project-entry">
        <div class="project-description">
            <h3>Skills and Interests</h3>
            <p><span class="highlight">Mathematics:</span> Real Analysis, Probability, Statistics, Linear Algebra, Calculus</p>
            <p><span class="highlight">Programming Skills:</span> R, Python, Bash, Linux, MATLAB, Java, Git/GitHub/GitLab, Sphinx/GitPages, web development, and LaTeX.</p>
            <p><span class="highlight">Languages:</span> Python, R, Bash, Linux/Command Line, MATALAB, LaTeX </p>
            <p><span class="highlight">Interests:</span> Biostatistics, Medical Imaging, Disease Prediction, Machine Learning</p>
            <p>Beyond academics, I am a public speaker and enjoy engaging in activities such as reading, backpacking, meditation, and playing guitar.</p>
        </div>
    </div>

    <div class="project-entry">
        <div class="project-description">
            <h3>Vision for the Future</h3>
            <p>I am excited about the potential to integrate biostatistics with advanced imaging techniques and machine learning to transform biomedical research. I am eager to contribute to a research environment that fosters collaboration among biostatisticians, imaging specialists, and machine learning experts.</p>
        </div>
    </div>

.. raw:: html

    <div class="section-intro">
        <p>For a more comprehensive insight, consider downloading the full CV.</p>
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

    <style>
        .inline-photo {
            float: right;
            margin-left: 20px; /* Adjusted for padding between text and image */
            margin-right: 20px; /* Padding on the right side */
            width: 275px; /* Image width */
            margin-bottom: 1rem; /* Space below the image */
        }
        
        .section-intro {
            overflow: hidden;
            padding-right: 20px; /* Ensures padding on the right side */
        }

        .project-entry {
            clear: both; /* Ensures that the content below the image starts fresh */
            margin-bottom: 2rem;
        }

    .highlight {
        color: #0056b3; /* A softer shade of blue */
        text-shadow: 0px 1px 1px rgba(0, 0, 0, 0.1); /* subtle shadow for depth */
    }

    .. .project-entry {
    ..     margin-bottom: 0.5rem;
    ..     display: flex;
    ..     justify-content: space-between;
    ..     align-items: flex-start;
    .. }

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
        margin-bottom: 1rem; /* Unchanged, ensures space above CV buttons */
    }

    .cv-buttons .button,
    .cv-buttons button {
        margin-right: 0.5rem; /* Unchanged */
        text-decoration: none;
        padding: 0.5rem 1rem; /* Unchanged */
        border: none;
        background-color: #17a2b8; /* Unchanged */
        color: white;
        border-radius: 0.25rem; /* Unchanged */
        cursor: pointer;
        transition: background-color 0.3s ease; /* Unchanged */
    }

    .cv-buttons a.button:hover,
    .cv-buttons button:hover {
        background-color: #138496; /* Darker shade on hover */
        text-decoration: none; /* No underline on hover */
    }

    .section-intro, .project-description {
        margin-bottom: 1rem; /* Reduced margin to bring sections closer together */
        padding: 1rem; /* Unchanged */
    }

    .research-entry {
        margin-top: 2rem; /* Added space before the research entry starts */
    }

    h3 {
        margin-top: 1rem; /* Reduced space above headings */
    }

    .cv-buttons {
        margin-top: 1rem; /* Adds space above the CV buttons */
        margin-bottom: 1rem; /* Adds space below the CV buttons */
    }
    </style>
