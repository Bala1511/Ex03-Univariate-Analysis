# Ex03-Univariate-Analysis

# Aim
To read the given data and perform the univariate analysis with different types of plots.

# Explanation
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

# Step1
Read the given data.

# Step2
Get the information about the data.

# Step3
Remove the null values from the data.

# Step4
Mention the datatypes from the data.

# Step5
Count the values from the data.

```
Developed By : BALA MURUGAN P
reference number: 212222230017
import pandas as pd
import numpy as np
import seaborn as sns

df=pd.read_csv('SuperStore.csv')
print(df)
```

```
df.head()
df.info()
df.dtypes
df['Postal Code'].value_counts()
sns.boxplot(x='Postal Code', data=df)
sns.countplot(x='Postal Code',data=df)
sns.distplot(df["Postal Code"])
df.describe()
```

# OUTPUT


![Screenshot 2023-03-27 203824](https://user-images.githubusercontent.com/118680410/228207821-4c5919f1-2ef7-4c93-89fe-10e0d11c530a.png)
![Screenshot 2023-03-28 155312](https://user-images.githubusercontent.com/118680410/228207826-a8c4eede-6fc5-4fbf-b7ec-23f1b49917b7.png)
![Screenshot 2023-03-28 155321](https://user-images.githubusercontent.com/118680410/228207836-624685a0-434e-4d37-9204-ed2351b96b07.png)
![Screenshot 2023-03-28 155331](https://user-images.githubusercontent.com/118680410/228207841-16c5791c-9fa3-4e75-9a82-3688e6cd80c8.png)
![Screenshot 2023-03-28 155339](https://user-images.githubusercontent.com/118680410/228207844-26a4e0ee-4b72-4ae7-86aa-b3498290fc69.png)
![Screenshot 2023-03-28 155346](https://user-images.githubusercontent.com/118680410/228207850-78aa3991-ecbc-407d-9fff-a663ffa780f6.png)
![Screenshot 2023-03-28 155353](https://user-images.githubusercontent.com/118680410/228207853-f70cc0bb-b67a-4e4f-a770-b4e23ce064ab.png)
![Screenshot 2023-03-28 155400](https://user-images.githubusercontent.com/118680410/228207859-9db566f0-268b-4e82-a056-1b7466ddead5.png)
![Screenshot 2023-03-28 155412](https://user-images.githubusercontent.com/118680410/228207862-c616fd40-ea50-4ccc-82ff-6ae1c394be55.png)
