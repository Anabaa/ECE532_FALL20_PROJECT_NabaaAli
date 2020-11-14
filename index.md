## Welcome to the Heart diagnositic ML project
Cardiovascular disease includes a wide range of conditions affecting heart and arteries. In this project, a
publicly available dataset which consists of 70000 observations of potential patients is obtained from
https://www.kaggle.com/sulianova/cardiovascular-disease-dataset. The dataset is based on 11 features and
a label of whether the patient observed suffers from a cardiovascular disease or not. The attributes may be
categorized as objective, examination and subjective. Objective attributes are based on factual information,
while the subjective ones are basically information given by the patients themselves.
The Features and their type/name in csv file/ (unit) are explained as follows:
1. Age | Objective Feature | age | int (days)
2. Height | Objective Feature | height | int (cm) |
3. Weight | Objective Feature | weight | float (kg) |
4. Gender | Objective Feature | gender | categorical code |
5. Systolic blood pressure | Examination Feature | ap_hi | int |
6. Diastolic blood pressure | Examination Feature | ap_lo | int |
7. Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above
normal |
8. Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |
9. Smoking | Subjective Feature | smoke | binary |
10. Alcohol intake | Subjective Feature | alco | binary |
11. Physical activity | Subjective Feature | active | binary |
12. Presence or absence of cardiovascular disease | Target Variable | cardio | binary |

The main goal of this project is to utilize different machine learning algorithms to obtain a classifier for
predicting cardiovascular disease with reasonable accuracy. The main tasks are preprocessing the dataset,
training a learner using three different algorithms to classify whether a patient has a cardiovascular disease
and comparing the global performance of each algorithm using cross-validation scheme to avoid overfitting.
The dataset is to be divided into 7 sets, each with 10000 datapoints and shall be used interchangeably for
training and evaluation purposes. The algorithms to be learned are as follows:

• **Linear regression with least squares**
• **K-nearest negihbours**
• **Neural networks with 2 layers**
### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Anabaa/ECE532_FALL20_PROJECT_NabaaAli/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
