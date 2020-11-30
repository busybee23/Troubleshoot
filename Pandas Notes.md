### Using pandas dataframe to find and treat null values in dataframe
`train.isnull().sum()` #gives you the sum of all null values into a row when used with isnull() <br>
`train[train.Embarked.isnull()]`<br>
`train.isnull().sum()`
<br> 

### To print a particular column in a dataframe using pandas 
`df.iloc[[row index]]`

### To comment any blocks of code in mostly all editors and language use <br>
`ctrl + /` for all selected lines. 

### Using pandas function to print all rows while using isnull().sum() function 
> https://youtu.be/SXwYy5YDHII 

### For extracting features of your choice :
`features_with_na = [cheese for cheese in dataset.columns if dataset[cheese].isnul().sum()>1]` <br> #this pulls out all columns with even a single null value 

### For dropping columns :
`dataset.drop(['Column Name'], axis=1, inplace=True)`<br> #here axis means columns or row if axis is 0 then it will drop the row with respective number otherwise column, inplace is replacing it within real dataset

### For dropping multiple columns : 
`dataset.drop(['Column 1 Name' , 'Column 2 Name'], axis = 1, inplace = True)

### To find out count of categorical Data in a column :
`print(dataset["Column Name"].unique())`
`dataset["Column Name"].value_counts()`
> https://www.youtube.com/watch?v=gMhDdOwApgs&feature=youtu.be
