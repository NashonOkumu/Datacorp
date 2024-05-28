BUSINESS UNDERSTANDING

Employee turnover poses significant challenges for companies, including increased costs associated with recruitment, training, and lost productivity. By accurately predicting which candidates are more inclined to remain with DataCorp after completing their training program, we aim to optimize our training initiatives, reduce turnover costs, and enhance candidate categorization.

Our objective is clear: build a robust machine learning model that predicts the probability of a candidate seeking a new job or staying with DataCorp post-training. Leveraging demographic, educational, and experiential attributes of candidates, this model will enable us to allocate resources effectively, focus on candidates more likely to stay, and ultimately enhance the quality and efficiency of our training programs.

DATA UNDERSTANDING

The dataset provided contains anonymized information about candidates'
demographics, education, experience, and other relevant features. It includes features such
as city development index, gender, relevant experience, education level, major discipline,
total experience, company size, company type, last new job, and training hours. The target
variable indicates whether a candidate is looking for a job change (1) or not (0).

Features
● enrollee_id : Unique ID for candidate.
● city: City code.
● city_ development _index : Development index of the city (scaled).
● gender: Gender of candidate
● relevent_experience: Relevant experience of candidate
● enrolled_university: Type of University course enrolled if any
● education_level: Education level of candidate
● major_discipline :Education major discipline of candidate
● experience: Candidate total experience in years
● company_size: No of employees in current employer's company
● company_type : Type of current employer
● last_new_job: Difference in years between previous job and current job
● training_hours: training hours completed
● target: 0 – Not looking for job change, 1 – Looking for a job change

DATA PREPARATION

![image](https://github.com/NashonOkumu/Datacorp/assets/66790358/48051ff0-e3a0-40f4-8f3c-0bdc4c198f34)

![image](https://github.com/NashonOkumu/Datacorp/assets/66790358/6f346bac-4cea-4548-a006-3d06a3c8f4f3)

![image](https://github.com/NashonOkumu/Datacorp/assets/66790358/4b98ccb2-acbf-4bb8-83fb-fe33a4b743a1)

![image](https://github.com/NashonOkumu/Datacorp/assets/66790358/aad6f3ab-79b2-4757-ad78-567c3c86713c)

![image](https://github.com/NashonOkumu/Datacorp/assets/66790358/addb298b-e94b-41e4-8f05-0dd93038ef4d)

![image](https://github.com/NashonOkumu/Datacorp/assets/66790358/30f803d0-ca37-4d68-91fc-b09c0284d343)

![image](https://github.com/NashonOkumu/Datacorp/assets/66790358/59ed8a76-c051-4520-9b96-fb3b08d70c66)

![image](https://github.com/NashonOkumu/Datacorp/assets/66790358/0d291632-5946-47e1-8b5f-c31c29c41713)

![image](https://github.com/NashonOkumu/Datacorp/assets/66790358/40563e1d-c531-440d-a234-6c9d623f615d)

<img width="343" alt="image" src="https://github.com/NashonOkumu/Datacorp/assets/66790358/73946520-2d49-485e-bbce-751b74f77cb8">


CONCLUSION & RECOMMENDATION

The logistic regression model achieved an accuracy of approximately 85.65% on the test data. The classification report provides insights into the model's performance for each class, including precision, recall, and F1-score. In this case, the model performs better at predicting the negative class (0.0) compared to the positive class (1.0), as evidenced by higher precision, recall, and F1-score for the negative class.

This model can inform DataCorp's decision-making process in optimizing their training programs and resource allocation. By identifying candidates who are more likely to stay, DataCorp can focus their efforts on providing targeted support and incentives to retain these individuals, thereby reducing turnover costs and enhancing the effectiveness of their training programs. Additionally, insights from the model can help DataCorp tailor their recruitment strategies and employee retention initiatives to attract and retain high-potential candidates who are committed to long-term engagement with the company. Overall, leveraging predictive modeling techniques like logistic regression enables DataCorp to make data-driven decisions that support their strategic goals of talent retention and organizational development.




