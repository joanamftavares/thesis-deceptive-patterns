# Complaint by Complaint: Detecting Deceptive Patterns in Complaints from Portal da Queixa

Deceptive patterns are design techniques that manipulate users into unintended behaviors. These are increasingly prevalent in online services, yet detection of these patterns in real-world consumer feedback remains underexplored. This thesis aims to bridge this gap by employing a combined approach of manual annotation with supervised learning to detect deceptive patterns in complaint summaries from Portal da Queixa. We collected a corpus of 2314 complaints across five market segments and a manually labeled a set of 551 instances for pattern presence. A logistic-regression classifier with TF-IDF vectorization was trained on this labeled dataset and then applied to the full corpus, flagging 272 complaints as deceptive. Each flagged complaint was then manually mapped into one of the five established taxonomies (Bait & Switch, Hidden Costs, Hidden Subscription, Obstruction, and Sneaking) based on prior research. To further analyze data, a Power BI dashboard that contains visualizations of pattern distribution by sector, company and temporal trends was also developed. Our analysis revealed Hidden Subscription and Bait & Switch as the most prevalent deceptive patterns and identified the Accommodation, Travel and Tourism sector as the most affected by these patterns. These findings demonstrate that a human approach can effectively surface deceptive patterns in consumer complaints and provide a foundation for scalable monitoring.

# Repository Structure

.
├── bi/                      # Power BI Dashboard 
├── data/                    # original, predicted and manually labeled datasets
├── img/                     # confusion matrix
├── README.md                    # Thesis Abstract
└── thesis-script.ipynb       #Jupyter notebook
