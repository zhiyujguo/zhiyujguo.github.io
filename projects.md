---
layout: page
title: Projects & Portfolio
subtitle: Research, Code, and Data Analysis Examples
---

<style>
.project-card {
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 20px;
  margin: 20px 0;
  background-color: #f9f9f9;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.project-card h2 {
  margin-top: 0;
  color: #404040;
  border-bottom: 2px solid #008AFF;
  padding-bottom: 10px;
}

.project-links {
  margin-top: 15px;
}

.btn-project {
  background-color: #008AFF;
  border: none;
  color: white;
  padding: 8px 16px;
  text-decoration: none;
  display: inline-block;
  margin: 4px 2px;
  cursor: pointer;
  border-radius: 4px;
  font-size: 14px;
}

.btn-project:hover {
  background-color: #0085A1;
  color: white;
  text-decoration: none;
}

.tech-tags {
  margin-top: 10px;
}

.tech-tag {
  display: inline-block;
  background-color: #e0e0e0;
  padding: 4px 8px;
  margin: 2px;
  border-radius: 3px;
  font-size: 12px;
  color: #404040;
}
</style>

## Industry Experience

<div class="project-card">
  <h2>Regeneron Pharmaceuticals - PhD Research Intern</h2>
  <p><strong>Duration:</strong> June 2024 - Aug 2024 | <strong>Location:</strong> Tarrytown, NY</p>
  
  <p>Analyzed, modeled, and optimized Regeneron's drug development pipeline and resource requirements for strategic planning.</p>
  
  <p><strong>Key achievements:</strong></p>
  <ul>
    <li>Implemented multistate survival models to predict attrition rates and project durations for drug development in R</li>
    <li>Built Bayesian predictive model with adjustable industry vs. internal data weights for pipeline optimization</li>
    <li>Increased efficiency in predicting required resources for new pipeline products</li>
    <li>Created and connected data sources for efficient processing of model inputs</li>
    <li>Presented optimization strategies to VP-level finance and planning leadership to inform strategic planning of pipeline expansion</li>
  </ul>
  
  <p><strong>Methods:</strong> Multistate survival models, Bayesian methods, nonparametric causal estimation, large-scale data processing</p>
  
  <div class="tech-tags">
    <span class="tech-tag">R</span>
    <span class="tech-tag">Survival Analysis</span>
    <span class="tech-tag">Bayesian Methods</span>
    <span class="tech-tag">Pipeline Optimization</span>
    <span class="tech-tag">Pharmaceutical Industry</span>
  </div>
</div>

## Research Projects

<div class="project-card">
  <h2>Nonparametric Assessment of Racial Disparities in Jury Selection</h2>
  <p><strong>Duration:</strong> Aug 2023 - Dec 2024 | <strong>Status:</strong> Submission in progress</p>
  
  <p>Advanced previous findings on racial disparities in prosecutorial peremptory strikes in Mississippi's Fifth District Court using flexible, nonparametric statistical methods.</p>
  
  <p><strong>Key contributions:</strong></p>
  <ul>
    <li>Applied doubly robust causal inference methods to analyze 2,300 jurors across 89 trials with 120 covariates</li>
    <li>Identified 37 percentage point difference (odds ratio: 6.91) in strike rates between Black and white jurors</li>
    <li>Implemented heterogeneity analysis using variance-based variable importance measures to identify factors associated with disparities</li>
    <li>Conducted extensive sensitivity analysis for robustness to unmeasured confounders and partial missingness</li>
    <li>Found that 44% of the sample would need unmeasured covariates to invalidate results</li>
  </ul>
  
  <p><strong>Methods:</strong> Doubly robust estimation, DR-learner, nonparametric statistics, heterogeneity analysis, sensitivity analysis, variable importance measures</p>
  
  <div class="tech-tags">
    <span class="tech-tag">R</span>
    <span class="tech-tag">Causal Inference</span>
    <span class="tech-tag">Doubly Robust Methods</span>
    <span class="tech-tag">Sensitivity Analysis</span>
    <span class="tech-tag">Criminal Justice</span>
  </div>
  
  <div class="project-links">
    <a href="JSM_slides.pdf" class="btn-project"><i class="fa fa-file-pdf-o"></i> JSM 2025 Slides</a>
  </div>
</div>

<div class="project-card">
  <h2>Gender Disparities in Social Media (Reddit Analysis)</h2>
  <p><strong>Duration:</strong> Jan 2022 - May 2024 | <strong>Status:</strong> Paper in progress</p>
  
  <p>Established a comprehensive three-stage framework to assess potential gender disparities in online engagement on r/relationships, controlling for confounders like writing style and topical distributions.</p>
  
  <p><strong>Research approach:</strong></p>
  <ul>
    <li>Analyzed 97,000 Reddit posts using structural topic modeling and sentiment analysis</li>
    <li>Implemented propensity score matching and cardinality matching to ensure comparable treatment and control groups</li>
    <li>Applied nonparametric causal estimation methods to quantify gender disparities in engagement outcomes</li>
    <li>Controlled for writing style, readability, and topic distribution as potential confounders</li>
  </ul>
  
  <p><strong>Methods:</strong> Structural topic modeling, sentiment analysis, readability analysis, propensity score matching, cardinality matching, text preprocessing, nonparametric causal estimation</p>
  
  <p><em>Poster presentation at American Causal Inference Conference (ACIC) 2023, Austin, TX</em></p>
  
  <div class="tech-tags">
    <span class="tech-tag">R</span>
    <span class="tech-tag">Text Analysis</span>
    <span class="tech-tag">NLP</span>
    <span class="tech-tag">Causal Inference</span>
    <span class="tech-tag">Matching Methods</span>
    <span class="tech-tag">Gender Disparities</span>
  </div>
</div>

<div class="project-card">
  <h2>Allegheny Housing Assessment: Effectiveness & Fairness Evaluation</h2>
  <p><strong>Duration:</strong> Feb 2025 - current | <strong>Status:</strong> Ongoing</p>
  
  <p>Comprehensive evaluation of the Allegheny Housing Assessment (AHA) algorithm examining both effectiveness and fairness implications across racial groups.</p>
  
  <p><strong>Analysis components:</strong></p>
  <ul>
    <li>Analyzed 25,000 records from 2018-2023 covering homeless individuals in Allegheny County</li>
    <li>Evaluated three-LASSO prediction model for adverse outcomes including mental health crises, ER visits, and jail bookings</li>
    <li>Assessed disparate impact across racial groups and AHA score categories</li>
    <li>Compared algorithmic tool (AHA) with traditional VI-SPDAT survey in real-world implementation</li>
  </ul>
  
  <p><strong>Keywords:</strong> Causal inference, program evaluation, algorithmic fairness, racial disparities, heterogeneous treatment effects</p>
  
  <div class="tech-tags">
    <span class="tech-tag">R</span>
    <span class="tech-tag">Causal Inference</span>
    <span class="tech-tag">Algorithmic Fairness</span>
    <span class="tech-tag">Program Evaluation</span>
    <span class="tech-tag">LASSO</span>
  </div>
</div>

## Teaching & Data Analysis Examples

<div class="project-card">
  <h2>Statistical Computing Materials</h2>
  <p>Collection of data analysis examples and practice problems developed for graduate-level statistics courses at CMU. These materials demonstrate practical applications of statistical methods to real-world datasets.</p>
  
  <p><strong>Featured analyses:</strong></p>
  
  <h3>Boston Housing Data Analysis</h3>
  <p>Comprehensive exploratory data analysis and regression modeling examining factors affecting housing prices in Boston. Demonstrates data cleaning, visualization, model building, and interpretation.</p>
  <div class="project-links">
    <a href="https://cmustatistics.github.io/data-repository/social/bostonhousing.html" target="_blank" class="btn-project"><i class="fa fa-external-link"></i> View Analysis</a>
  </div>
  
  <h3>Social Capital & Political Networks</h3>
  <p>Analysis of social capital data exploring connections between community networks and political outcomes. Includes network analysis techniques and spatial statistics.</p>
  <div class="project-links">
    <a href="https://cmustatistics.github.io/data-repository/politics/social_capital.html" target="_blank" class="btn-project"><i class="fa fa-external-link"></i> View Analysis</a>
  </div>
  
  <div class="tech-tags">
    <span class="tech-tag">R</span>
    <span class="tech-tag">Data Visualization</span>
    <span class="tech-tag">Regression Analysis</span>
    <span class="tech-tag">Statistical Inference</span>
  </div>
</div>

## Publications & Presentations

<div class="project-card">
  <h2>Published Research</h2>
  
  <h3>Visualizing Formative Feedback in Statistics Writing</h3>
  <p><strong>Authors:</strong> Laudenbach, M., Brown, D. W., <strong>Guo, Z.</strong>, Ishizaki, S., Reinhart, A., & Weinberg, G.</p>
  <p><strong>Published:</strong> <em>Assessing Writing</em>, Volume 60, April 2024</p>
  
  <p>Interdisciplinary research examining how visualization tools can improve feedback and motivation in statistics education. Contributed statistical analysis and methodology expertise for pre- and post-survey analysis.</p>
  
  <div class="project-links">
    <a href="https://www.sciencedirect.com/science/article/pii/S1075293524000230" target="_blank" class="btn-project"><i class="fa fa-external-link"></i> Read Paper</a>
  </div>
  
  <div class="tech-tags">
    <span class="tech-tag">Education Research</span>
    <span class="tech-tag">Statistical Analysis</span>
    <span class="tech-tag">Survey Methodology</span>
  </div>
</div>

<div class="project-card">
  <h2>Conference Presentations</h2>
  
  <h3>Joint Statistical Meetings (JSM) 2025</h3>
  <p><strong>Talk:</strong> "Nonparametric Assessment of Racial Disparities in Prosecutorial Peremptory Strikes"</p>
  <p><strong>Authors:</strong> Guo, Z., Kennedy, E. H., & Ben-Michael, E.</p>
  <p><strong>Location:</strong> Nashville, TN</p>
  <div class="project-links">
    <a href="JSM_slides.pdf" class="btn-project"><i class="fa fa-file-pdf-o"></i> View Slides</a>
  </div>
  
  <h3>American Causal Inference Conference (ACIC) 2023</h3>
  <p><strong>Poster:</strong> "Assessing Gender Disparities in Textual Response on Reddit.com"</p>
  <p><strong>Authors:</strong> Guo, Z. & Branson, Z.</p>
  <p><strong>Location:</strong> Austin, TX</p>
  
  <h3>IEEE International Professional Communication Conference (ProComm) 2023</h3>
  <p><strong>Panel:</strong> "Structuring Genre Performance for Future Data Scientists via an Interactionist Design Model"</p>
  <p><strong>Authors:</strong> Hutchison, A., Laudenbach, M., Xu, D., & Guo, Z.</p>
  <p><strong>Location:</strong> Ithaca, NY</p>
</div>

---

## Skills & Technologies

**Programming Languages:** R, Python (Pandas, NumPy, scikit-learn, PyTorch), SQL, MATLAB, Git, Tableau, LaTeX

**Statistical Methods:** Causal inference, doubly robust methods, double machine learning, survival analysis, text analysis, Bayesian methods, survey methodology, regression analysis, hypothesis testing, machine learning

**Specialized Techniques:** Propensity score matching, cardinality matching, structural topic modeling, sentiment analysis, sensitivity analysis, variable importance measures, multistate models, LASSO, heterogeneous treatment effects

**Tools & Platforms:** R/RStudio, Jupyter Notebook, Git Bash, MySQL, large-scale data processing

**Domain Expertise:** Algorithmic fairness, criminal justice statistics, text analysis/NLP, pharmaceutical pipeline optimization, program evaluation

---

<p style="text-align: center; margin-top: 40px;">
<em>Interested in collaborating or learning more about my work? <a href="/contact/">Get in touch!</a></em>
</p>
