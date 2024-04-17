About
======

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
