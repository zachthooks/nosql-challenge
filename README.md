# nosql-challenge

## **Project Overview**
This project analyzes food hygiene ratings from the UK Food Standards Agency to provide insights for journalists and food critics of the magazine *Eat Safe, Love*. The data is stored in a NoSQL MongoDB database and queried using Python, with results analyzed and visualized using Pandas.

## **Key Features**
1. Import and manage food hygiene data in MongoDB.
2. Clean and update the database with necessary modifications.
3. Perform exploratory data analysis (EDA) to answer specific business questions.
4. Generate actionable insights using Python and Pandas.

---

## **Technologies Used**
- **Database**: MongoDB
- **Language**: Python
- **Libraries**:
  - `pymongo` for database interaction.
  - `pandas` for data manipulation.
  - `pprint` for displaying query results.

---

## **Project Structure**
```plaintext
├── NoSQL_setup_starter.ipynb  # Jupyter Notebook for database setup and modifications
├── NoSQL_analysis_starter.ipynb  # Jupyter Notebook for exploratory analysis
├── establishments.json  # Input data for the MongoDB database
├── README.md  # Project documentation
```

---

## **Setup Instructions**

### **Prerequisites**
1. **Install MongoDB**:
   - [Download MongoDB](https://www.mongodb.com/try/download/community) and follow the installation instructions.
   - Ensure MongoDB is running locally on port `27017`.

2. **Install Python and Required Libraries**:
   ```bash
   pip install pymongo pandas
   ```
3. Clone the Repository:
   ```bash
   git clone <repository-link>
   cd <repository-name>
   ```
## **How to Run**

### **Step 1: Database Setup**

Open `NoSQL_setup_starter.ipynb` in Jupyter Notebook:

- Verify the database and collection setup.
- Perform database updates:
  - Insert new restaurant data.
  - Remove irrelevant records.
  - Normalize data types.

### **Step 2: Exploratory Analysis**

Open `NoSQL_analysis_starter.ipynb` in Jupyter Notebook:

- Run queries to answer specific questions, such as:
  - Establishments with a hygiene score of 20.
  - Top-rated establishments near a specified location.
- Convert query results into pandas DataFrames for analysis.


## **Analysis Questions**

1. **Which establishments have a hygiene score equal to 20?**
   - **Count**: 41
   - Displayed in a pandas DataFrame.

2. **Which establishments in London have a `RatingValue` greater than or equal to 4?**
   - **Count**: 33
   - Displayed in a pandas DataFrame.

3. **What are the top 5 establishments with a `RatingValue` of 5, sorted by lowest hygiene score, nearest to the new restaurant "Penang Flavours"?**
   - Results sorted and displayed.

4. **How many establishments in each Local Authority area have a hygiene score of 0?**
   - Results grouped and sorted in descending order.

---

## **Deliverables**

- **MongoDB database** (`uk_food`) with updated records.
- **Two Jupyter Notebooks**:
  1. `NoSQL_setup_starter.ipynb`: For database setup and updates.
  2. `NoSQL_analysis_starter.ipynb`: For analysis and insights.
- **Results** exported as pandas DataFrames for visualization.

## **Contact**

If you have any questions or feedback, feel free to contact me:

- **Name**: Zachary Hooks  
- **Email**: [zhooks558@gmail.com](mailto:zhooks558@gmail.com)  
- **Phone**: 210-787-0346  






