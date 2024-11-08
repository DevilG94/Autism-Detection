# Enhancing Autism Detection: InceptionV3 & Xception Models with Differential Attention Mechanism

Autism spectrum disorder is a condition related to brain development that impacts how a person perceives and socializes with others, causing problems in social interaction and communication. The disorder also includes limited and repetitive patterns of behavior. The term "spectrum" in autism spectrum disorder refers to the wide range of symptoms and severity.
Autism spectrum disorder begins in early childhood and eventually causes problems functioning in society — socially, in school and at work, for example. Often children show symptoms of autism within the first year. A small number of children appear to develop normally in the first year, and then go through a period of regression between 18 and 24 months of age when they develop autism symptoms.
This project aims to enhance the Accuracy and Efficiency of autism diagnosis through image classification.

Causes: -
Autism spectrum disorder has no single known cause. Given the complexity of the disorder, and the fact that symptoms and severity vary, there are probably many causes. Both genetics and environment may play a role.
•	Genetics. Several different genes appear to be involved in autism spectrum disorder. For some children, autism spectrum disorder can be associated with a genetic disorder, such as Rett syndrome or fragile X syndrome. For other children, genetic changes (mutations) may increase the risk of autism spectrum disorder. Still other genes may affect brain development or the way that brain cells communicate, or they may determine the severity of symptoms. Some genetic mutations seem to be inherited, while others occur spontaneously.
•	Environmental factors. Researchers are currently exploring whether factors such as viral infections, medications or complications during pregnancy, or air pollutants play a role in triggering autism spectrum disorder.
Risk factors:-
The number of children diagnosed with autism spectrum disorder is rising. It's not clear whether this is due to better detection and reporting or a real increase in the number of cases, or both.
Autism spectrum disorder affects children of all races and nationalities, but certain factors increase a child's risk. These may include:
•	Your child's sex. Boys are about four times more likely to develop autism spectrum disorder than girls are.
•	Family history. Families who have one child with autism spectrum disorder have an increased risk of having another child with the disorder. It's also not uncommon for parents or relatives of a child with autism spectrum disorder to have minor problems with social or communication skills themselves or to engage in certain behaviors typical of the disorder.
•	Other disorders. Children with certain medical conditions have a higher than normal risk of autism spectrum disorder or autism-like symptoms. Examples include fragile X syndrome, an inherited disorder that causes intellectual problems; tuberous sclerosis, a condition in which benign tumors develop in the brain; and Rett syndrome, a genetic condition occurring almost exclusively in girls, which causes slowing of head growth, intellectual disability and loss of purposeful hand use.
•	Extremely preterm babies. Babies born before 26 weeks of gestation may have a greater risk of autism spectrum disorder.
•	Parents' ages. There may be a connection between children born to older parents and autism spectrum disorder, but more research is necessary to establish this link.

Prevention
There's no way to prevent autism spectrum disorder, but there are treatment options. Early diagnosis and intervention is most helpful and can improve behavior, skills and language development. However, intervention is helpful at any age. Though children usually don't outgrow autism spectrum disorder symptoms, they may learn to function well.
##                                                                        PROJECT OVERVIEW
In this project, I utilized InceptionV3 and Xception pre pretrained models, known for their robust ion performance in image recognition tasks. By integrating a Differential Attention Mechanism, I aimed to improve the model’s ability to focus on relevant features in the input data, thereby enhancing classification Accuracy.

Key Highlights: -
Data Preparation: I complied a comprehensive dataset consisting of labelled images for both ASD and Non-ASD categories. The preprocessing steps included normalization and resizing images to ensure consistency in model training.

Model Architecture: -
InceptionV3 and Xception: Leveraging these powerful pretrained models allowed for effective feature extraction while significantly reducing training time.
Differential Attention Mechanism: This innovative approach enhances traditional attention mechanisms by promoting sparse attention patterns, leading to better performance in tasks involving complex data.

### Performance Metrics: After training and evaluating both models, I achieved promising results –
### 1)	For InceptionV3  Precision: [0.85, 0.84]; Recall: [0.84, 0.85]; F1-Score: [0.85, 0.85]; Accuracy = 85%
### 2)	For Xception Precision: [0.76, 0.89]; Recall: [0.91, 0.71]; F1-Score: [0.83, 0.79]; Accuracy = 81%

This result indicate that the InceptionV3 model, enhanced with the differential attention mechanism, outperformed the Xception model in terms of Precision and Recall

Conclusion: -
This project has provided valuable insights into the potential of Deep Learning in the field of mental health diagnosis, specifically Autism detection. The integration of differential attention not only improved Accuracy but also demonstrated the importance of focusing on relevant features in complex datasets.
