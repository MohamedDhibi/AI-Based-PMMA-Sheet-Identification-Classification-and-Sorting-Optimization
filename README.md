# AI-Based PMMA Sheet Identification, Classification, and Sorting Optimization

## Project Overview

This project aims to develop an AI-based system to identify, classify, and optimize the sorting of PMMA (Polymethyl methacrylate) sheet materials to enhance recycling efficiency. The system will utilize computer vision techniques to automatically identify PMMA sheets from images and classify them based on various attributes, optimizing the sorting process for improved recycling outcomes. Note: The sheets may also be made from other crystal-clear polymers such as PET, Polycarbonate, etc.

## Objectives

1. Automatically identify PMMA sheets through measuring dimensions from pictures.
2. Classify PMMA sheets based on attributes such as color, transparency, etc.
3. Explore the dataset using data visualization techniques to gain insights into the distribution of different characteristics among PMMA waste objects.
4. Implement the developed system on Django for a more user-friendly interface.

## Tasks and Deliverables

### 1st Period: Data Acquisition and Preprocessing
- Acquire the dataset of images.
- Preprocess image data and handle corrupt data.
- Perform data augmentation to increase dataset diversity if needed.

### 2nd Period: State of the Art
- Conduct a literature review and examine previous projects similar to ours.
- Identify methodologies, techniques, and best practices relevant to our project objectives.
- Acquire pre-existing knowledge from research consortium on sheet properties.

### 3rd Period: Feature Extraction and Model Development
- Extract features from images and attributes.
- Perform data cleaning to handle potential misleading information throughout the training process.
- Normalize numerical attributes and encode categorical attributes.
- Develop CNN-based models for PMMA sheet classification.
- Implement image processing techniques for dimension measurement.
- Integrate classification and dimension measurement models.

### 4th Period: Sorting Optimization and Data Visualization
- Analyze classification results and sorting errors.
- Develop algorithms to optimize the sorting process based on classification results.
- Explore the dataset using data visualization techniques.
- Analyze the distribution of attributes such as color, transparency, and thickness.
- Identify patterns and outliers within the dataset.

### 5th Period: System Integration
- Setup Django for web development.
- Integrate developed models and functionalities into the Django application.
- Design a user-friendly interface for system interaction.

### 6th Period: Deployment and Finalization
- Deploy Django application on a web server.
- Conduct testing and debugging.
- Prepare a user guide for system usage.
- Finalize project documentation and report.

## Milestones

- **Milestone 1:** Completion of Data Acquisition and Preprocessing.
- **Milestone 2:** Completion of Feature Extraction and Model Development.
- **Milestone 3:** Completion of Sorting Optimization and Data Visualization.
- **Milestone 4:** System Integration.
- **Milestone 5:** Deployment and Finalization.

## Resources

- Images gathered using the sorting station.
- Python programming language
- Libraries: TensorFlow, Keras, Django, Matplotlib, PowerBI, etc.

## Risks and Mitigation

- **Data Quality:** Perform thorough data cleaning and validation.
- **Model Complexity:** Regularly evaluate model performance and consider model simplification if necessary.
- **Deployment Issues:** Conduct extensive testing before deployment and provide adequate user support.

Note: A comprehensive report detailing the project's methodology, experiments, results, and conclusions will be continuously worked on throughout all project periods.
