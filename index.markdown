---
layout: default
title: Portfolio
---

<div class="project-card">
  <img src="{{ '/assets/images/ai_reco.png' | relative_url }}" alt="Customer Segmentation & Recommendation Engine">
  <div class="project-card-content">
  <h3>Customer Segmentation & Recommendation Engine</h3>
  <p><strong>Problem:</strong> Low product discovery rates and lack of personalised recommendations on eCommerce led to missed revenue opportunities. </p>
  <p><strong>Goal:</strong> Build a recommendation engine using customer segmentation insights. </p>

  <ul>
    <li>Developed clustering models to segment customers into different clusters (<b>K-Means, GMM</b>).</li>
    <li>Built a recommendation engine with <b>Recall@5 of 87%</b> using a weighted hybrid model (<b>GMM cluster, product affinity, CF & CBF scores</b>) to suggest top 5 customer-level products.</li>
    <li>Visualised insights with Tableau dashboards for stakeholders.</li>
  </ul>

  <div class="tags">
      <span class="tag-pill">Python (pandas, sklearn, numpy)</span>
      <span class="tag-pill">Tableau</span>
    </div>
    <a href="https://github.com/SereneChanSiYun/customer-segmentation-recommendation" class="view-project" target="_blank">View Full Project Here → </a>
  </div>
</div>

<div class="project-card">
  <img src="{{ '/assets/images/hdb_prediction.png' | relative_url }}" alt="Price Prediction">
  <div class="project-card-content">
  <h3>HDB Resale Price Prediction</h3>

  <p><strong>Problem:</strong> Fragmented HDB flat pricing data resulted in inaccuracies and client's lack of confidence in real estate agents.</p>
  <p><strong>Goal:</strong> Build a predictive model for resale HDB flat prices.</p>

  <ul>
    <li>Built 2 <b>Linear Regression</b> models to predict HDB prices; selected the model with <b>RMSE improvement of 57%</b>.</li>
    <li>Created a <b>Streamlit app</b> for real estate agents to easily input the features and get the predicted price.</li>
    <li>Visualised insights via an interactive Tableau dashboard for stakeholders.</li>
  </ul>

  <div class="tags">
      <span class="tag-pill">Python (pandas, sklearn, numpy, joblib)</span>
      <span class="tag-pill">Tableau</span>
      <span class="tag-pill">Streamlit</span>
    </div>
    <a href="https://github.com/SereneChanSiYun/hdb-price-prediction" class="view-project" target="_blank">View Full Project Here →</a>
  </div>
</div>

<div class="project-card">
  <img src="{{ '/assets/images/us_election.png' | relative_url }}" alt="US Election">
  <div class="project-card-content">
  <h3>U.S. Presidential Elections Analysis with Power BI</h3>

  <p><strong>Problem:</strong> Lacks a clear, data-driven visual narrative that shows how U.S. elections have evolved since 2020.</p>
  <p><strong>Goal:</strong> Create a story that helps everyday readers easily understand the key electoral trends. </p>

  <ul>
    <li>Created a <b>Power BI interactive dashboard</b> with 4 levels of details for trend analysis. </li>
    <li>Built visuals such as KPI, bar charts, time-series line graphs, filled maps and animations. </li>
    <li>Craft insightful narratives with analysis of voter movements. </li>
  </ul>

  <div class="tags">
      <span class="tag-pill">Power BI</span>
    </div>
    <a href="https://github.com/SereneChanSiYun/us-presidential-election-power-bi" class="view-project" target="_blank">View Full Project Here →</a>
  </div>
</div>

<div class="project-card">
  <img src="{{ '/assets/images/gender_pay_gap.png' | relative_url }}" alt="Gender Pay Gap">
  <div class="project-card-content">
  <h3>Gender Pay Gap Analysis with SQL</h3>

  <p><strong>Problem:</strong> Lack of reliable monitoring on how gender pay gap varies across UK. </p>
  <p><strong>Goal:</strong> Use SQL analysis to uncover the geographical and sector-level patterns and present clear insights for policymakers to reduce pay inequalities.</p>

  <ul>
    <li>Generate <b>SQL queries with pgadmin</b> and analyzed the data on city/state, employer size and industry levels.</li>
    <li>Communicated the findings with graphs and visualisations, plus a presentation for non-technical stakeholders</li>
  </ul>

  <div class="tags">
      <span class="tag-pill">SQL</span>
      <span class="tag-pill">Excel</span>
    </div>
    <a href="https://github.com/SereneChanSiYun/gender-pay-gap-sql" class="view-project" target="_blank">View Full Project Here →</a>
  </div>
</div>