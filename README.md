ANS 1.
import pandas as pd
print(pd.__version__)

Ans 2.
data = np.array(['a', 'b', 'c', 'd', 'e'])
s = pd.Series(data) 
print(s)

Ans 3.
df = pd.DataFrame({'Roll Number': ['20CSE29', '20CSE49', '20CSE36', '20CSE44'], 
                   'Name': ['Amelia', 'Sam', 'Dean', 'Jessica'], 
                   'Marks In Percentage': [97, 90, 70, 82], 
                   'Grade': ['A', 'A', 'C', 'B'], 
                   'Subject': ['Physics', 'Physics', 'Physics', 'Physics']}) 
df

ANS 4.
import seaborn as sb
tips = sb.load_dataset(‘tips’)

Ans 5. USA
