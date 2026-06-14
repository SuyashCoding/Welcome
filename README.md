<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Suyash Patel - Resume</title>
    <style>
        /* CSS Page Profile for Native Browser Rendering */
        html, body {
            margin: 0;
            padding: 0;
            background-color: #f4f6f8; /* Soft background to highlight the A4 page preview */
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            color: #333333;
            line-height: 1.4;
            font-size: 10.5pt;
        }

        /* Standard A4 Container for Desktop View */
        .page-container {
            width: 210mm;
            min-height: 297mm;
            margin: 30px auto; /* Centers the resume page on screen with top/bottom spacing */
            padding: 20mm 15mm; /* Explicitly sets the 15mm left/right and 20mm top/bottom margins */
            background-color: #ffffff;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08); /* Professional paper shadow drop */
            box-sizing: border-box;
        }

        /* Fallbacks & overrides specifically optimized for physical printing/PDF engines */
        @media print {
            html, body {
                background-color: #ffffff;
            }
            @page {
                size: A4;
                margin: 20mm 15mm;
            }
            .page-container {
                width: auto;
                min-height: auto;
                margin: 0;
                padding: 0;
                box-shadow: none;
            }
        }
        
        *, *::before, *::after {
            box-sizing: border-box;
        }

        /* Header Styles */
        .header {
            text-align: center;
            margin-bottom: 22px;
        }

        .name {
            font-size: 24pt;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin: 0 0 6px 0;
            color: #1a2530;
        }

        .contact-info {
            font-size: 10pt;
            color: #555555;
        }

        .contact-info a {
            color: #1a2530;
            text-decoration: none;
            border-bottom: 1px solid #cccccc;
        }

        .contact-info a:hover {
            border-bottom: 1px solid #1a2530;
        }

        .separator {
            margin: 0 8px;
            color: #cccccc;
        }

        /* Section Styles */
        .section {
            margin-bottom: 18px;
        }

        .section-title {
            font-size: 12pt;
            font-weight: bold;
            color: #1a2530;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            border-bottom: 1px solid #1a2530;
            padding-bottom: 3px;
            margin: 0 0 10px 0;
            page-break-after: avoid;
        }

        /* Block Layouts */
        .row {
            display: table;
            width: 100%;
            margin-bottom: 4px;
            page-break-inside: avoid;
        }

        .cell-left {
            display: table-cell;
            text-align: left;
            font-weight: bold;
        }

        .cell-right {
            display: table-cell;
            text-align: right;
            font-weight: normal;
            color: #444444;
        }

        .sub-row {
            display: table;
            width: 100%;
            margin-bottom: 6px;
            font-style: italic;
            color: #555555;
            page-break-inside: avoid;
        }

        /* List Bullet Styles */
        ul {
            margin: 0 0 10px 0;
            padding-left: 20px;
        }

        li {
            margin-bottom: 4px;
            text-align: justify;
        }

        .skills-table {
            display: table;
            width: 100%;
            margin-bottom: 4px;
        }

        .skills-row {
            display: table-row;
        }

        .skills-label {
            display: table-cell;
            font-weight: bold;
            width: 180px;
            padding-bottom: 5px;
        }

        .skills-value {
            display: table-cell;
            padding-bottom: 5px;
        }

        .item-block {
            margin-bottom: 10px;
            page-break-inside: avoid;
        }

        .publication-title {
            font-weight: bold;
        }

        a {
            color: #1a2530;
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <div class="page-container">
        <!-- Header -->
        <div class="header">
            <h1 class="name">Suyash Patel</h1>
            <div class="contact-info">
                <a href="mailto:suyashpatel2018@gmail.com">suyashpatel2018@gmail.com</a>
                <span class="separator">|</span>
                <span>(984) 292-8029</span>
                <span class="separator">|</span>
                <span>Raleigh, NC</span>
                <span class="separator">|</span>
                <a href="https://www.linkedin.com/in/suyash-patel-9246a4266/" target="newpage">LinkedIn</a>
                <span class="separator">|</span>
                <a href="https://github.com/SuyashCoding" target="newpage">GitHub</a>
            </div>
        </div>

        <!-- Education -->
        <div class="section">
            <h2 class="section-title">Education</h2>
            <div class="row">
                <div class="cell-left">North Carolina State University</div>
                <div class="cell-right">Expected Dec 2026</div>
            </div>
            <div class="sub-row">
                <div class="cell-left">B.S. Computer Science (Senior), AI Concentration with minor in Mathematics</div>
                <div class="cell-right">GPA: 3.6/4.0</div>
            </div>
        </div>

        <!-- Experience -->
        <div class="section">
            <h2 class="section-title">Experience</h2>
            
            <div class="item-block">
                <div class="row">
                    <div class="cell-left">Computer Vision Research Intern</div>
                    <div class="cell-right">Apr – Sep 2025</div>
                </div>
                <div class="sub-row">
                    <div class="cell-left">AI Thinking Labs</div>
                    <div class="cell-right"></div>
                </div>
                <ul>
                    <li>Researched and implemented U-Net image segmentation models on real-world datasets, including insulator detection and cattle muzzle biometrics</li>
                    <li>Built and trained YOLOv5 detection pipelines for stationary and biological image targets</li>
                    <li>Processed large-scale datasets via Roboflow to improve data quality and training consistency</li>
                    <li>Optimized model training pipelines, improving segmentation accuracy and reducing inference time</li>
                    <li>Deployed models as lightweight web interfaces using Streamlit and NGrok</li>
                </ul>
            </div>

            <div class="item-block">
                <div class="row">
                    <div class="cell-left">SparkLabs NC Volunteer</div>
                    <div class="cell-right">Apr – Aug 2025</div>
                </div>
                <div class="sub-row">
                    <div class="cell-left">SparkLabs NC</div>
                    <div class="cell-right"></div>
                </div>
                <ul>
                    <li>Volunteered in teaching North Carolina’s High Schoolers through online modules</li>
                    <li>Reviewed and Proofread learning modules in AI, Data Science, and Software Engineering</li>
                    <li>Worked and collaborated in teams</li>
                </ul>
            </div>
        </div>

        <!-- Publications -->
        <div class="section">
            <h2 class="section-title">Publications</h2>
			<div class="item-block" style="white-space: normal;">
				<div>
					<span class="publication-title">A Novel Multi-Stage Deep Architecture with SIFT-VGG Fusion Net for Muzzle Based Animal Identification</span> 
					<span style="font-style: italic; color: #555555; font-size: 10pt; margin-left: 6px;">
						(<a href="https://ieee-icad.org/wp-content/uploads/2026/06/159.pdf" target="_blank">Published</a>: IEEE International Conference on AI and Data Analytics 2026 (ICAD) (159))
					</span>
				</div>
			</div>
			<div class="item-block" style="white-space: normal;">
				<div>
				<span class="publication-title">Global AI Tool Adoption Across Industries: A Comprehensive Analysis of Trends and Patterns (2023–2025)</span>
				<span style="font-style: italic; color: #555555; font-size: 10pt; margin-left: 6px;">
				(<a href="https://www.researchgate.net/publication/394523153_Global_AI_Tool_Adoption_Across_Industries_A_Comprehensive_Analysis_of_Trends_and_Patterns_2023-2025" target="newpage">ResearchGate Preprint</a>)
				</span>
				</div>
			</div>
        </div>

        <!-- Technical Skills -->
        <div class="section">
            <h2 class="section-title">Technical Skills</h2>
            <div class="skills-table">
                <div class="skills-row">
                    <div class="skills-label">Languages:</div>
                    <div class="skills-value">Python, Java, C, SQL, MATLAB, HTML/CSS</div>
                </div>
                <div class="skills-row">
                    <div class="skills-label">ML & Computer Vision:</div>
                    <div class="skills-value">U-Net, YOLOv5, SIFT-BoVW, VGG-16, image segmentation, feature fusion, model training & optimization</div>
                </div>
                <div class="skills-row">
                    <div class="skills-label">Data & Tools:</div>
                    <div class="skills-value">MySQL, Roboflow, Jupyter Notebook, Git, Linux/Unix, Streamlit, NGrok, Vim, Eclipse</div>
                </div>
            </div>
        </div>

        <!-- Certifications -->
        <div class="section">
            <h2 class="section-title">Certifications</h2>
            <div style="font-weight: bold;">Certified Associate in Python Programming (PCAP) <span style="font-weight: normal; color: #555555;">|</span> Certified Entry-Level Python Programmer (PCEP)</div>
        </div>

        <!-- Patent -->
        <div class="section">
            <h2 class="section-title">Patent</h2>
            <div>
                <span style="font-weight: bold;">Stick Based Leaf Plate Stapler</span> : Patent No. 416708, India Office of the Controller General of Patents, Designs & Trade Marks (2019). <a href="https://nif.org.in/innovation/stapler-for-leaf-plate-making/1127" target="newpage">Link</a>
            </div>
        </div>

        <!-- Honors -->
        <div class="section">
            <h2 class="section-title">Honors</h2>
            <div>
                <span style="font-weight: bold;">Dr. APJ Abdul Kalam Ignite Award (2019)</span> — Presented by former President of India Pranab Mukherjee for the Stick Based Leaf Plate Stapler invention
            </div>
        </div>

        <!-- Activities -->
        <div class="section" style="margin-bottom: 0;">
            <h2 class="section-title">Activities</h2>
            <div>
                <span style="font-weight: bold;">LA/CSC Member & Code Black Member</span>, NC State University.
                <div style="color: #555555; font-size: 10pt; margin-top: 2px;">CS community orgs focused on professional development, peer support, and the annual Black History Month hackathon</div>
            </div>
        </div>
    </div>

</body>
</html>
