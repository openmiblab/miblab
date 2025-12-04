.. _pipelines:

#########
Pipelines
#########

Python scripts that turn imaging data into imaging biomarkers. Since 
imaging pipelines are complex and may take a long time to run, they 
are often split into smaller stages producing intermediate checkpoints. 


.. raw:: html

    <h2 class="highlight-title">Model training</h2>


.. raw:: html

    <div class="card-grid">

        <div class="custom-card">
            <img src="_static/fat_recon.png" alt="Fatwater training">
            <div class="custom-card-body">
                <h3>Fat-water mapping from 3D Dixon-MRI</h3>
                <p>Pipeline for training the deep-learning model</p>
                <div class="button-row">
                    <a href="https://github.com/openmiblab/iBEAt-fatwater" target="_blank" class="custom-btn btn-repo">
                        <i class="fa fa-github"></i> Repository
                    </a>
                    <a href="https://zenodo.org/records/17817186" target="_blank" class="custom-btn btn-zenodo">
                        <i class="fa fa-database"></i> Archive
                    </a>
                    <span class="custom-btn btn-embargo embargo-disabled">
                        <i class="fa fa-lock"></i> Input Data (Embargoed)
                    </span>
                    <a href="https://zenodo.org/records/15356745" target="_blank" class="custom-btn btn-output">
                        <i class="fa fa-download"></i> Model weights
                    </a>
                </div>
            </div>
        </div>

    </div>


.. raw:: html

    <h2 class="highlight-title">Modelling</h2>


.. raw:: html

    <div class="card-grid">

        <div class="custom-card">
            <img src="_static/tristan-modelling.png" alt="Tristan modelling">
            <div class="custom-card-body">
                <h3>Drug-mediated liver transporter inhibition</h3>
                <p>MRI kinetic analysis (human assay)</p>
                <div class="button-row">
                    <a href="https://github.com/openmiblab/tristan-human-stage-2-modelling?tab=readme-ov-file#measuring-drug-mediated-inhibition-of-liver-transporters" target="_blank" class="custom-btn btn-repo">
                        <i class="fa fa-github"></i> Repository
                    </a>
                    <a href="https://zenodo.org/records/15611776" target="_blank" class="custom-btn btn-zenodo">
                        <i class="fa fa-database"></i> Archive
                    </a>
                    <a href="https://github.com/openmiblab/tristan-human-stage-2-modelling/blob/main/src/analyze_rifampicin.ipynb" target="_blank" class="custom-btn btn-notebook">
                        <i class="fa fa-book"></i> Notebook
                    </a>
                    <a href="https://zenodo.org/records/15610261" target="_blank" class="custom-btn btn-input">
                        <i class="fa fa-upload"></i> Input Data
                    </a>
                    <a href="https://zenodo.org/records/15610350" target="_blank" class="custom-btn btn-output">
                        <i class="fa fa-download"></i> Output Data
                    </a>
                </div>
            </div>
        </div>

        <div class="custom-card">
            <img src="_static/tristan-rat-modelling.png" alt="Tristan rat modelling">
            <div class="custom-card-body">
                <h3>Drug-mediated liver transporter inhibition</h3>
                <p>MRI kinetic analysis (rat assay)</p>
                <div class="button-row">
                    <a href="https://github.com/openmiblab/tristan-rat-modelling?tab=readme-ov-file#measuring-drug-mediated-inhibition-of-liver-transporters-in-rats" target="_blank" class="custom-btn btn-repo">
                        <i class="fa fa-github"></i> Repository
                    </a>
                    <a href="https://zenodo.org/records/15648009" target="_blank" class="custom-btn btn-zenodo">
                        <i class="fa fa-database"></i> Archive
                    </a>
                    <a href="https://zenodo.org/records/15610261" target="_blank" class="custom-btn btn-input">
                        <i class="fa fa-upload"></i> Input Data
                    </a>
                    <a href="https://zenodo.org/records/15644248" target="_blank" class="custom-btn btn-output">
                        <i class="fa fa-download"></i> Output Data
                    </a>
                </div>
            </div>
        </div>

    </div>


.. raw:: html

    <h2 class="highlight-title">Analysis</h2>


.. raw:: html

    <div class="card-grid">

        <div class="custom-card">
            <img src="_static/correlations_effect.png" alt="Correlations Effect">
            <div class="custom-card-body">
                <h3>Drug-mediated liver transporter inhibition</h3>
                <p>Data analysis of the first-in-human study</p>
                <div class="button-row">
                    <a href="https://github.com/openmiblab/tristan-human-stage-3-analysis?tab=readme-ov-file#an-mri-assay-for-drug-induced-inhibition-of-liver-transporters-first-in-human-study" target="_blank" class="custom-btn btn-repo">
                        <i class="fa fa-github"></i> Repository
                    </a>
                    <a href="https://zenodo.org/records/15616745" target="_blank" class="custom-btn btn-zenodo">
                        <i class="fa fa-database"></i> Archive
                    </a>
                    <a href="https://github.com/openmiblab/tristan-human-stage-3-analysis/blob/main/src/run.ipynb" target="_blank" class="custom-btn btn-notebook">
                        <i class="fa fa-book"></i> Notebook
                    </a>
                    <a href="https://zenodo.org/records/15610350" target="_blank" class="custom-btn btn-input">
                        <i class="fa fa-upload"></i> Input Data
                    </a>
                    <a href="https://zenodo.org/records/15610541" target="_blank" class="custom-btn btn-input">
                        <i class="fa fa-upload"></i> Input Data
                    </a>
                    <a href="https://www.medrxiv.org/content/10.1101/2025.06.16.25329670v1" target="_blank" class="custom-btn btn-publication">
                        <i class="fa fa-file-text"></i> Preprint
                    </a>
                </div>
            </div>
        </div>

        <div class="custom-card">
            <img src="_static/tristan-rat-analysis.png" alt="Tristan rat analysis">
            <div class="custom-card-body">
                <h3>Drug-mediated liver transporter inhibition</h3>
                <p>Data analysis of TRISTAN rat studies</p>
                <div class="button-row">
                    <a href="https://github.com/openmiblab/tristan-rat-analysis?tab=readme-ov-file#measuring-drug-mediated-inhibition-of-liver-transporters-analysis-of-tristan-rat-data" target="_blank" class="custom-btn btn-repo">
                        <i class="fa fa-github"></i> Repository
                    </a>
                    <a href="https://zenodo.org/records/15647997" target="_blank" class="custom-btn btn-zenodo">
                        <i class="fa fa-database"></i> Archive
                    </a>
                    <a href="https://zenodo.org/records/15644248" target="_blank" class="custom-btn btn-input">
                        <i class="fa fa-upload"></i> Input Data
                    </a>
                    <a href="https://pubs.acs.org/doi/full/10.1021/acs.molpharmaceut.1c00206" target="_blank" class="custom-btn btn-publication">
                        <i class="fa fa-file-text"></i> Paper
                    </a>
                    <a href="https://link.springer.com/article/10.1007/s10334-024-01192-5" target="_blank" class="custom-btn btn-publication">
                        <i class="fa fa-file-text"></i> Paper
                    </a>
                    <a href="https://archive.ismrm.org/2021/2764.html" target="_blank" class="custom-btn btn-publication">
                        <i class="fa fa-file-text"></i> Abstract
                    </a>
                </div>
            </div>
        </div>

    </div>



