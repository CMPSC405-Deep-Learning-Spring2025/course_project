# Final Project: Design, Implementation, and Deployment of a Deep Learning Model

## Deadline: May 1, 2025 by 9am

## Summary

In this final project, you will design, implement, train, and deploy a deep learning model of your choice to solve a real-world problem. This project invites you to apply the theoretical concepts and practical skills you have learned throughout the course to develop a complete end-to-end deep learning solution.

You will have the freedom to select your own application domain, dataset, and model architecture based on your interests. Your project should demonstrate mastery of key deep learning concepts and showcase your ability to create, evaluate, and optimize a neural network model while considering ethical implications.

During the final exam period, you will deliver a 10-minute presentation of your project that constitutes 5% of your overall course grade. Following all project presentations, there will be a brief conceptual exam covering course material that will account for the remaining 10% of the final exam percentage for the course grade.

## Learning Outcomes

- Apply concepts from calculus and linear algebra to create predictive models using deep neural networks
- Use Python to implement and interpret multilayer neural networks that can process various data sources
- Apply an existing deep learning model in an application for predictive analysis and effectively communicate results
- Evaluate, optimize, and improve model performance with attention to ethical impacts
- Build, train, test, document, and deploy a new deep learning model in a software application

## Resources

- [D2L Textbook](https://d2l.ai/) (Chapters 1-11)
- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)
- [Papers With Code](https://paperswithcode.com/) for state-of-the-art implementations
- [Kaggle Datasets](https://www.kaggle.com/datasets) for potential data sources
- [Hugging Face](https://huggingface.co/) for model hosting and deployment options

## Project Requirements

### 1. Problem Definition and Data Preparation

1. Select a problem domain and clearly define the task your model will address
2. Choose or create an appropriate dataset for your task
3. Perform comprehensive data exploration, analysis, and preprocessing
4. Document your data pipeline including handling of:
   - Data splitting (train/validation/test)
   - Data normalization or augmentation
   - Feature engineering (if applicable)

### 2. Model Design and Implementation

1. Design a neural network architecture appropriate for your chosen problem
2. Implement your model using PyTorch, TensorFlow, JAX, Hugging Face Transformers or another deep learning framework
3. Your implementation must include:
   - A multilayer neural network (minimum of 3 layers)
   - Appropriate activation functions
   - An appropriate loss function
   - At least two techniques to improve training (e.g., batch normalization, dropout, residual connections)

### 3. Model Training and Evaluation

1. Train your model using appropriate optimization algorithms
2. Implement a validation strategy to monitor model performance
3. Document hyperparameter choices and tuning process
4. Evaluate your model using at least three appropriate metrics
5. Compare your model's performance against at least one baseline or alternative approach
6. Analyze model behavior including visualizations. For example, you can graph:
   - Training/validation curves
   - Model predictions
   - Feature importance or attention maps (if applicable)

### 4. Ethical Considerations and Social Impact

1. Analyze potential biases in your data and model
2. Discuss ethical implications of your model's deployment
3. Propose mitigation strategies for identified risks
4. Consider broader societal impacts of your application

### 5. Model Deployment and Documentation

1. Deploy your model in at least one of the following ways:
   - Web application
   - API endpoint
   - Mobile application
   - Embedded system
   - Cloud service
2. Create user documentation in the `src/README` that explains how to use your deployed model

## Project Deliverables

1. **Project Repository**: This project assignment repository containing:
   - All code in the `src/` (including data preprocessing, model implementation, training, evaluation, and deployment)
   - README in the `src/` with clear instructions for setup and use
   - Requirements file listing all dependencies

2. **Project Report**: A comprehensive report in `writing/report.md` documenting:
   - Problem statement and motivation
   - Data analysis and preprocessing
   - Model architecture and implementation details
   - Training methodology and hyperparameter choices
   - Evaluation results and analysis
   - Ethical considerations
   - Deployment details

3. **Deployed Model**: Access to your deployed model with documentation on how to use it

## Presentation

A 10-minute presentation covering:
   - Project overview and motivation
   - Approach and methodology
   - Key results and insights
   - Demo of deployed model
   - Ethical considerations and limitations

The presentation component will be evaluated separate from the project grade and instead will be a part of your final exam, amounting to 5% of the course grade.

## Evaluation Criteria

This project follows contract-based grading. To receive an A, you must:

- Complete all requirements in the five main categories under [Project Requirements](#project-requirements)

Each category that is incomplete will warrant a grade reduction. 

Overall, you should:
- Demonstrate mastery of deep learning concepts through your implementation
- Provide thorough documentation and analysis in your report
- Deploy a functional model that others can use
- Maintain regular commits to GitHub showing progressive development


