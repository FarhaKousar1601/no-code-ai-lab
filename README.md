
# No-Code AI Lab: Build, Train, and Test Without Coding

Exploring Artificial Intelligence and Machine Learning through no-code tools and hands-on experiments.

## About the Project

This repository documents my learning journey through the **No-Code AI Lab: Build, Train, and Test Without Coding** course on Excelerate, supported by the **Rochester Institute of Technology (RIT)**.

The course explores how AI models can be developed, trained, and tested using visual tools without writing code.

The repository includes two practical activities:

- **Experiment 1:** Pen vs. Pencil Image Classification
- **Final Capstone:** EcoSort AI — No-Code Waste Classification

## What Is No-Code AI?

No-Code AI enables users to build and explore AI models through graphical interfaces instead of programming them from scratch.

It allows users to:

- Create and organize data samples.
- Train machine learning models using visual tools.
- Test predictions using new inputs.
- Observe model predictions and limitations.
- Explore practical applications of artificial intelligence.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Google Teachable Machine | Building, training, and testing image classification models |
| Excelerate | Course learning and activities |
| GitHub | Project documentation and version control |
| Image datasets | Training and experimenting with classification models |
| Markdown | Technical documentation |

## Platform: Google Teachable Machine

[Google Teachable Machine](https://teachablemachine.withgoogle.com/) is a browser-based platform that lets users create machine learning models using images, sounds, or body poses without writing code.

The image classification workflow includes:

1. Creating classes for different categories.
2. Collecting or uploading example images.
3. Training an image classification model.
4. Testing predictions using the preview interface.
5. Observing predicted classes and confidence scores.

---

# Experiment 1: Pen vs. Pencil Image Classification

## Objective

Explore how a machine learning model learns to distinguish between two visual categories.

## Dataset

| Class | Image Samples |
|---|---:|
| Pen | 3 |
| Pencil | 3 |
| **Total** | **6** |

## Experiment Screenshot

![Google Teachable Machine Pen vs Pencil experiment](https://raw.githubusercontent.com/FarhaKousar1601/no-code-ai-lab/main/Screenshot%202026-10-24%20101435.png)

## Training Configuration

| Setting | Value |
|---|---:|
| Epochs | 50 |
| Batch size | 16 |
| Learning rate | 0.001 |

## Workflow

1. Created separate classes for Pen and Pencil.
2. Added example images to each class.
3. Configured the training settings.
4. Trained the model using Google Teachable Machine.
5. Explored the model preview.
6. Identified the need for further testing with unseen images.

## Observations

The experiment demonstrated how image samples can be organized into classes and used to train a model without coding.

With only three samples per class, the dataset is very small. More varied images, backgrounds, angles, and lighting conditions would be needed for a meaningful evaluation.

**Evaluation:** No overall accuracy score is claimed for this experiment.

---

# Final Capstone: EcoSort AI — No-Code Waste Classification

## Project Overview

**EcoSort AI** is a no-code image classification project that explores how an AI model can categorize waste images into three visual classes:

- Plastic
- Paper and Cardboard
- Metal

The project demonstrates a practical machine learning workflow using Google Teachable Machine without writing code.

## Problem Statement

Recycling requires waste materials to be identified and separated into appropriate categories. EcoSort AI explores how image classification could support the recognition of recyclable materials.

This project is an educational prototype, not a production-ready waste-sorting system.

## Objectives

- Explore AI-assisted waste image classification.
- Create and label three image classes.
- Train an image classification model.
- Observe predictions and confidence scores.
- Understand dataset limitations and model evaluation.
- Explore a practical application of AI for recycling awareness.

## Class Labels

| Class | Example Items |
|---|---|
| Plastic | Plastic bottles, caps, containers, and packaging |
| Paper and Cardboard | Paper sheets, newspapers, and cardboard boxes |
| Metal | Metal cans, scraps, and metal containers |

## Dataset Summary

The trained model contained the following samples in the recorded project:

| Class | Image Samples |
|---|---:|
| Plastic | 7 |
| Paper and Cardboard | 7 |
| Metal | 7 |
| **Total** | **21** |

The dataset contains 21 samples across three classes. This is a small demonstration dataset and is not sufficient to establish reliable real-world performance.

## Model Training and Workflow

The model was created and trained using the Google Teachable Machine Image Project interface.

1. Created three image classes.
2. Added example images to their corresponding classes.
3. Trained the model using the platform's training feature.
4. Used the Preview panel to observe a prediction.
5. Recorded the project demonstration.
6. Documented the initial result and limitations.


## Capstone Project Screenshots

### EcoSort AI — No-Code Waste Classification

![EcoSort AI project screenshot](https://raw.githubusercontent.com/FarhaKousar1601/no-code-ai-lab/main/Screenshot%202026-10-24%20123350.png)



## Initial Observation

For the displayed image of colorful plastic bottles and containers, the preview showed:

- **Predicted class:** Plastic
- **Displayed confidence:** 100%

This is one observed prediction, not the model's overall accuracy. A confidence score does not guarantee that a prediction is correct.

## Evaluation and Testing

A reliable overall accuracy score requires testing on separate images that were not used for training and recording whether each prediction is correct.

The accuracy formula is:

**Accuracy = (Correct predictions / Total test images) × 100**

No overall accuracy percentage is claimed because a complete set of test results has not been documented.

## Potential Applications

- Recycling education and awareness.
- Demonstrations of AI-assisted waste classification.
- Exploring automated waste segregation concepts.
- Learning about computer vision and supervised machine learning.

## Limitations

- The dataset contains only seven samples per class in the recorded screenshot.
- The model may be sensitive to backgrounds, lighting, angles, and object appearance.
- Composite, contaminated, or mixed-material objects may be difficult to classify visually.
- Confidence scores are not guarantees of correctness.
- A visual prediction does not determine whether an item is accepted by local recycling facilities.
- Real-world use would require a larger dataset and systematic evaluation.

## Future Improvements

- Expand the dataset with more varied examples for every class.
- Keep unseen images separate for testing.
- Record correct and incorrect predictions.
- Calculate accuracy from actual test results.
- Test different backgrounds, lighting conditions, and object angles.
- Explore additional categories after evaluating the current model.

---

# Course Modules and Progress

The following sections summarize the learning areas and activities documented in this repository. Use the official module titles if they differ from these descriptions.

## Module 1: Understanding AI and No-Code Platforms

Topics explored:

- AI fundamentals and no-code platforms.
- How machine learning models learn patterns from data.
- Everyday applications of AI.
- The role of data in model training.

**Status:** Completed.

## Module 2: Working with Sample Datasets

Topics explored:

- Dataset structure and organization.
- Inputs, labels, and observations.
- Data preparation and quality.
- Potential dataset bias and limitations.

**Status:** Completed.

If the PDF is uploaded to the repository root, you can link it here:

[View Module 2 Dataset Notes (PDF)](FarhaKousar_Module2_DatasetNotes.pdf)

## Module 3: Training AI Models

Topics explored:

- Creating image classes.
- Uploading training examples.
- Understanding training settings.
- Training a model using a visual interface.
- Observing how training examples influence predictions.

**Practical activities:** Pen vs. Pencil experiment and EcoSort AI model training.

**Status:** Completed.

## Module 4: Evaluating and Testing AI Models

Topics explored:

- Viewing model predictions.
- Understanding confidence scores.
- Recognizing the difference between confidence and accuracy.
- Identifying dataset limitations.
- Understanding the importance of unseen-image testing.

**Practical activity:** Examined the Teachable Machine preview and documented an initial prediction.

**Status:** Completed.

## Module 5: Final Validation and Project Compilation

Activities:

- Selected a practical image classification use case.
- Built and trained the EcoSort AI model.
- Recorded the project demonstration.
- Prepared project documentation.
- Reflected on the learning process and model limitations.

**Capstone:** EcoSort AI — No-Code Waste Classification.

**Status:** Completed.

---

# Course Progress Tracker

- [x] Course introduction and overview
- [x] Module 1: Understanding AI and No-Code Platforms
- [x] Module 2: Working with Sample Datasets
- [x] Module 3: Training AI Models
- [x] Module 4: Evaluating and Testing AI Models
- [x] Module 5: Final Validation and Project Compilation
- [x] Pen vs. Pencil experiment
- [x] EcoSort AI model training
- [x] EcoSort AI demonstration recording
- [x] Project documentation prepared
- [x] Course learning activities completed

---

## Learning Outcomes

Through this course and the practical experiments, I explored how to:

- Understand fundamental AI and machine learning concepts.
- Use a no-code platform to train an image classifier.
- Organize data into labeled classes.
- Understand how training examples influence predictions.
- Interpret confidence scores carefully.
- Recognize the importance of testing, data quality, and model limitations.
- Document a practical AI experiment and its results.
- Explore how AI can be applied to recycling-related use cases.


## 🏅 Course Completion Badge

I successfully completed the **No-Code AI Lab: Build, Train, and Test Without Coding** course, supported by Rochester Institute of Technology (RIT).

![No-Code AI Lab Completion Badge](https://raw.githubusercontent.com/FarhaKousar1601/no-code-ai-lab/main/Badge_.png)


## Conclusion

The No-Code AI Lab course provided hands-on exposure to creating, training, and testing image classification models without programming.

The Pen vs. Pencil experiment introduced the fundamentals of image classification, while EcoSort AI applied those concepts to a recycling-related use case with three material categories.

This project strengthened my understanding of dataset preparation, model training, prediction confidence, and the importance of evaluating machine learning models using unseen data.

## About the Author

**Farha Kousar**  
B.E. in Artificial Intelligence and Machine Learning

- **GitHub:** [FarhaKousar1601](https://github.com/FarhaKousar1601)
- **Portfolio:** [farha-kousar.vercel.app](https://farha-kousar.vercel.app/)

---

*This repository documents an independent learning project and an educational prototype. The recorded prediction is an individual observation, not a verified measure of overall model accuracy. This repository is not an official project of Excelerate or the Rochester Institute of Technology.*
