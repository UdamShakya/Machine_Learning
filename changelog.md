## 📌 Changelog  

### Commit 1 – Dataset Exploration  
- Added **class distribution plot** to visualize Dropout, Enrolled, Graduate counts.  
- Added **feature correlation heatmap** using the original DataFrame (instead of NumPy arrays).  
- Improves understanding of dataset balance and feature relationships.  

### Commit 2 – Training Improvements  
- Integrated a **learning rate scheduler** (`StepLR`) to improve convergence.  
- Training loop now **tracks learning rate** at each epoch.  
- Provides better stability and potentially higher performance.  

### Commit 3 – Model Saving & Reloading  
- Added functionality to **save trained model weights** (`student_outcome_model.pth`).  
- Demonstrated how to **reload the model** and run inference on test samples.  
- Makes the model reusable for future predictions without retraining.  

 
