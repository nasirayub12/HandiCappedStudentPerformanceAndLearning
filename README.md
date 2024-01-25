# Disabled Students Learning and Performance Dataset
This data was collected at Air University, Islamabad, Pakistan, specifically focusing on disabled students over a period of four years from 2020 to 2023.
a detailed explanation of each column in the dataset:

StudentID: A unique identifier assigned to each student.
department: The academic department or major in which the student is enrolled (e.g., Biology, Psychology, Business Administration, Engineering).
gender: The gender of the student (e.g., Male, Female).
address: The type of residence the student comes from (e.g., Urban, Rural).
admission_status: Indicates whether the student has been admitted or not (e.g., Admitted, Not Admitted).
aboriginal: Binary indicator (0 or 1) specifying whether the student is of aboriginal descent.
child_of_new_residents: Binary indicator (0 or 1) specifying whether the student is a child of new residents.
family_children_ranking: The ranking of the student among their siblings in terms of birth order.
parent_avg_income_per_month: The average monthly income of the student's parents.
on_campus_accommodation: Binary indicator (0 or 1) specifying whether the student lives in on-campus accommodation.
main_source_of_living_expenses: The primary source of funds for the student's living expenses (e.g., Scholarship, Family Support).
student_loan: Binary indicator (0 or 1) specifying whether the student has a student loan.
tuition_waiver: Binary indicator (0 or 1) specifying whether the student has a tuition waiver.
father_live_or_not: Binary indicator (0 or 1) specifying whether the student's father is alive.
father_occupations: The occupation of the student's father.
father_education: The highest level of education attained by the student's father.
mother_live_or_not: Binary indicator (0 or 1) specifying whether the student's mother is alive.
mother_occupations: The occupation of the student's mother.
mother_education: The highest level of education attained by the student's mother.
num_required_credits: The number of credits required for the student's program.
num_elective_credits: The number of elective credits taken by the student.
sick_leave: The number of sick leave days taken by the student.
personal_leave: The number of personal leave days taken by the student.
learning_status: The current learning status of the student (e.g., 1 for active, 0 for inactive).
target_group: The target group classification for disabled students (e.g., Group 1, Group 2, Group 3).

This dataset capture various demographic, academic, and personal factors that may influence the learning performance of disabled students. 
**24. learning_status:**
Description: This column represents the current learning status of the student. It is a binary indicator with values 1 and 0.
Values:
1: Indicates that the student is currently active in their learning, implying that they are actively enrolled in courses or participating in educational activities.
0: Indicates that the student is inactive in terms of learning, suggesting that they might be on a break, have temporarily withdrawn, or are not currently participating in academic activities.
Interpretation and Insights:

A value of 1 in the "learning_status" column suggests that the student is actively engaged in the learning process.
A value of 0 implies that the student is not currently participating in academic activities. The reasons for inactivity could vary, such as taking a leave of absence, experiencing health issues, or facing personal challenges.
Potential Use Cases:

Monitoring Academic Engagement: The "learning_status" column can be used to monitor and track the active participation of disabled students in their academic programs.
Identifying At-Risk Students: Inactive status might prompt further investigation into the reasons behind a student's disengagement, allowing for timely interventions to support those at risk of falling behind.
Relationship with Other Columns:

The "learning_status" column could be correlated with other columns such as "sick_leave" and "personal_leave" to understand if health issues or personal circumstances contribute to periods of inactivity.
It may also be associated with the "target_group" column, as different groups of disabled students might have varying levels of engagement or face unique challenges affecting their learning status.
Considerations:

While the "learning_status" column provides valuable information, its interpretation may depend on the context of the dataset and the specific criteria used to determine the learning status of a student.
Recommendations for Further Analysis:

Exploring the reasons behind changes in learning status, especially for transitions from active to inactive, can provide insights into factors influencing student engagement.
Analyzing the relationship between learning status and academic performance or well-being metrics could offer a comprehensive understanding of the dynamics affecting disabled students in their learning journeys.
Overall, the "learning_status" column is a crucial indicator that focuses on the current educational engagement of disabled students, providing a basis for targeted support and interventions to enhance their learning experiences.
