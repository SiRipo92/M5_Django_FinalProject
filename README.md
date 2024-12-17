# Final Project: Add a New Assessment Feature to an Online Course Application

## Overview
This project involves enhancing an existing Online Course application by implementing a new course assessment feature. You will utilize your Django full-stack development skills to design and integrate models, templates, and views to support the new functionality. Additionally, you will test the application to ensure it meets the required specifications.

The provided boilerplate code serves as the starting point for this project. Your task is to extend the functionality according to the requirements outlined below.

---

## Objectives
By completing this project, you will:

1. **Understand the feature requirements:** Comprehend the purpose and functionality of the new course assessment feature.
2. **Design and implement models:** Create models for `Question`, `Choice`, and `Submission` to support exam-related features.
3. **Admin site setup:** Create a new course object and configure the admin site to manage exam-related models.
4. **Enhance templates:** Update the course details template to display questions and choices.
5. **Build new views:**
   - Create a new view to handle exam result submission.
   - Create a new view to display and evaluate the exam result.
6. **Test the application:** Verify that all features function as expected.

---

## Requirements and Implementation Steps

### 1. Models
- Create models for:
  - **Question**: Represents a question in the course exam.
  - **Choice**: Represents answer choices for a question.
  - **Submission**: Stores a user’s exam responses.

### 2. Admin Site Configuration
- Register the `Question`, `Choice`, and `Submission` models in the Django admin site.
- Configure the admin interface to allow easy management of exam-related data.

### 3. Course Details Template
- Update the course details template to display:
  - A list of questions.
  - The available choices for each question.

### 4. Exam Result Template
- Design a new template to display the result of a submitted exam, including:
  - The user’s responses.
  - The correct answers.
  - The overall score.

### 5. Views
- Implement function-based views to handle:
  - **Exam Submission:** Process and store a user’s exam responses.
  - **Exam Evaluation:** Calculate and display the exam results based on user submissions.

### 6. URLs
- Create URL patterns to:
  - Access the course details page with exam questions.
  - Submit the exam.
  - View the exam results.

---

## Evaluation Criteria (15 Marks Total)

1. **Models (3 Marks):** Correctly implement the `Question`, `Choice`, and `Submission` models.
2. **Model Registration (3 Marks):** Successfully register the models in the admin site.
3. **Admin Site Setup (1 Mark):** Ensure the admin site works as expected for managing exam data.
4. **Course Details Template (2 Marks):** Properly display questions and choices in the course details section.
5. **Views (2 Marks):** Write function-based views for handling exam submission and result display.
6. **URLs (2 Marks):** Implement URL patterns for accessing the new views.
7. **Exam Result Display (2 Marks):** Show the final result accurately in the exam result template.

---

## Deliverables

1. **Updated Models:** `Question`, `Choice`, and `Submission` models.
2. **Admin Site Configuration:** Models registered and functional.
3. **Templates:**
   - Updated course details template.
   - New exam result template.
4. **Views:**
   - Function-based views for exam submission and result evaluation.
5. **URLs:** Patterns for the new views.
6. **Test Results:** Ensure all functionality works as expected.

---

## Author(s)
This project is designed and authored by **Muhammad Yahya** as part of the Django Full-Stack Development course on [CognitiveClass.ai](https://cognitiveclass.ai).


**ER Diagram**
For your reference, we have prepared the ER diagram design for the new assesement feature.

![Onlinecourse ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)
