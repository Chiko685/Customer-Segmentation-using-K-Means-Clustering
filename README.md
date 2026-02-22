# Customer Segmentation Using K-Means Clustering

This project performs customer segmentation using K-Means Clustering based on three key marketing features:

Age

Annual Income

Spending Score

The goal is to group customers into meaningful segments that businesses can use for targeted marketing, personalization, and product strategy.

# 🔍 Project Objectives

Identify natural customer groups using machine learning

Apply Elbow Method to determine the optimal number of clusters

Visualize cluster distribution

Generate insights useful for marketing & business decision-making

# 📦 Technologies Used

Python (Pandas, NumPy)

Scikit-learn

Seaborn, Matplotlib

## 🧹 1. Exploratory Data Analysis
<img width="616" height="129" alt="Screenshot 2026-02-23 at 01 33 23" src="https://github.com/user-attachments/assets/32baa1b1-afdc-4b8f-91ce-9105c343a1d6" />
<img width="591" height="520" alt="Screenshot 2026-02-23 at 01 41 58" src="https://github.com/user-attachments/assets/1a5246e3-d1b2-436f-ad31-10c83fa482b6" />
<img width="471" height="393" alt="Screenshot 2026-02-23 at 01 42 57" src="https://github.com/user-attachments/assets/58efcfeb-9053-4d0c-b470-a9223c8447bc" />

## 📉 2. Elbow Method (Finding Optimal K)
<img width="571" height="646" alt="Screenshot 2026-02-23 at 01 45 25" src="https://github.com/user-attachments/assets/19a57269-2fa5-4019-869b-fe00cd17940a" />
<img width="571" height="439" alt="Screenshot 2026-02-23 at 01 45 49" src="https://github.com/user-attachments/assets/f94f88c3-6628-49d6-a2dd-d0f88a0e0842" />


Interpretation:
Choose the “siku” / elbow point where the WCSS drop slows significantly.
In this project, the best value is typically K = 5.

## 🎯 3. Scatter Plot K-Means Clustering(n_cluster = 5)

<img width="593" height="592" alt="Screenshot 2026-02-23 at 01 48 05" src="https://github.com/user-attachments/assets/c46562aa-76bc-4a41-9c62-9ea5f06493e5" />

## Result
<img width="702" height="422" alt="Screenshot 2026-02-23 at 01 49 30" src="https://github.com/user-attachments/assets/f79d2c6d-3560-4eda-b6af-90a66e86d78b" />

# 💡 Key Insights

      * K-Means identified 5 clear customer groups with distinct behaviors.
      * We can see the cluster no.0 with Age = 32, have a high Annual Income and hig Spending Score = 82 compare to other cluster.
      So the company might want to centainly look at the cluster no.0 before generate any campaigns. 
      * Cluster no.0 presents 54% shoppers are women and we should look for ways to attract these customers using 
      marketing campaign ,targeting popular items in this cluster
      * But there is one cluster (no.3) also have a high Spending Score =79 with the lowest Annual Income and Age =25. 
      This needs to run a deep research. Might be the customer of this cluster only had their purchase for discount, promotion etc.
      * Others show low-spending segments that may need different strategies.


## Segmentation helps companies personalize:

- Promotions

- Product recommendations

- Loyalty programs

- Pricing strategy

