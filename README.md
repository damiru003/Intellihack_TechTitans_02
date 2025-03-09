
## Quick Start

1. **Set up your environment**
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

1. **Run the analysis**
   - Open and run the Jupyter notebook:
     ```
     jupyter notebook customer_segmentation.ipynb
     ```
   - Or using VS Code:
     - Open VS Code and install the Jupyter extension
     - Open the repository folder and the notebook file
     - Click "Run All" or run cells individually with Shift+Enter

3. **Verify results**
   - Check that output file `clustered_customers.csv` was created
   - Verify silhouette score (~0.626) and three distinct clusters

## Repository Contents
- `customer_segmentation.ipynb`: The complete analysis code
- `customer_behavior_analytcis.csv`: E-commerce dataset 


## Key Insights
- **Window Shoppers**: Low purchases, high browsing time
- **Bargain Hunters**: High purchases, discount-sensitive
- **High Spenders**: Moderate purchases, high cart value

## Troubleshooting
- Missing dataset? Place `customer_behavior_analytcis.csv` in the root directory
- Module errors? Install missing libraries with `pip install [library-name]`
- Plot issues? Ensure `%matplotlib inline` is in the imports cell

