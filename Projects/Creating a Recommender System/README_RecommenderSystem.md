
## **Movie Recommendation System** 🍿

Welcome to the `Movie Recommendation System` repository. Dive into a world of movie suggestions, tailored to your tastes!

### **🎬 Overview:**
This project aims to provide movie suggestions based on a given movie title. Using data from movie ratings and other attributes, the system identifies movies that are similar to the input and recommends them to the user.

### **🔧 How It Works:**

1. **Data Preparation**: 
    - Data from `ratings.csv`, `movies.csv`, and `tags.csv` is ingested.
    - Basic statistics such as the number of ratings, unique movies, and users are computed.
    
2. **Similarity Computation**: 
    - Based on a given movie title, the system computes similarity scores with other movies.
    
3. **Interactive Interface**: 
    - The system offers a simple Command-Line Interface (CLI) where users can:
        - Lookup movie suggestions.
        - Exit the program.

4. **Feedback Loop**: 
    - Users receive movie suggestions and are informed if a movie isn't in the database.

### **📊 Data Insights**:
- The dataset comprises movies, ratings, and tags, giving a comprehensive understanding of user preferences.
- The system can identify both the lowest and highest-rated movies, providing insights into user preferences.

### **🚀 Get Started**:
To explore the recommendation system, check out the Jupyter notebook named `Recommender_System_KNN.ipynb`.

---

### **Contribute**: 
Your insights can make this recommendation system even better! Fork the repository, submit issues, or raise pull requests. Every contribution counts!

### **License**: 
This project is licensed under the MIT License.
