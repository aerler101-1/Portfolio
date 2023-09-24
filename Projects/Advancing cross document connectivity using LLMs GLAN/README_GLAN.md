
## **GLAN Data Matching** 🔄

Welcome to the `GLAN Data Matching` repository. This project is focused on the intricate task of aligning company and parent company names from diverse data sources using text-based similarity techniques.

### **🛠️ How It Works:**

1. **Data Ingestion and Cleaning**: 
    - Import the reference company list and the dataset intended for matching.
    - Refine the text: unwanted characters are discarded and text is standardized to lowercase for consistency.

2. **TF-IDF Vectorization**: 
    - Textual data is transformed into a numerical format using the TF-IDF (Term Frequency-Inverse Document Frequency) method.

3. **Cosine Similarity Matching**: 
    - Determine the closeness between company names across both datasets.
    - This matching process spans various columns, notably 'Producer' and 'Brand'.

4. **Precision Thresholding**: 
    - Matches are validated based on similarity thresholds, such as 90% or 50%.

5. **Results Compilation**: 
    - Post matching, results are cataloged into a CSV, named 'matched_results.csv'.

6. **Visual Insight**: 
    - A heatmap visualization offers a snapshot of the highest matching values against different columns for every producer.

### **📈 Visualization Preview**:

![Heatmap of Data Matching](heatmap_link_here.png)

*Replace `heatmap_link_here.png` with the link to your heatmap image hosted on GitHub or elsewhere.*

### **🔗 Get Started**:
To delve into the code and datasets, check out the Jupyter notebook named `GLAN data matching.ipynb`.

---

### **Contribute**: 
Feel free to fork this repository, raise issues, or submit pull requests. Your contributions are always welcome!

### **License**: 
This project is licensed under the MIT License.
