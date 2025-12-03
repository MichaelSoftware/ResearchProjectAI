# Wine Quality Classification — Red Wine Dataset (UCI)

## Abstract
The purpose of this project is to examine the problem of predicting red wine quality using the Wine Quality dataset from the UCI Machine Learning Repository. 

There are 11 physicochemical measurements for 1,599 Portuguese red wines in the dataset as well as sensory quality scores that were assigned by human tasters. 

A stratified 80/20 split was used for the training and evaluation of the Random Forest model. 

According to the model, the majority classes (quality 5 and 6) performed the best, while minority classes (3, 4, and 8) were nearly impossible to predict due to the severe class imbalances. 

In terms of predictors, alcohol, sulfates, volatile acidity, and sulfur dioxide levels were the most significant. Overall, this dataset allowed the model to perform as realistically as possible without the need to rebalance or re-frame the problem.

---

## Video Presentation
**Video Link:**  
https://youtu.be/LrXRiIHyK2w

---

## Project Contents
This repository includes:

- The main notebook implementing the Random Forest classifier  
- README containing the abstract and video link  

## How to Run
1. Open the notebook in Google Colab or any Python environment.  
2. Run all cells from top to bottom.  
3. The script automatically:
   - Downloads the dataset
   - Trains the model
   - Evaluates and will print the results

## Contribution Guidelines
1. **Fork the repository.**
2. **Create a feature branch:** `git checkout -b feature-branch`
3. **Commit changes:** `git commit -m "Description of changes"`
4. **Push the branch:** `git push origin feature-branch`
5. **Submit a Pull Request for review.**

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For inquiries or support, open an issue in the repository or contact the maintainer:
- **CodeLaad**: [GitHub Profile](https://github.com/MichaelSoftware)
