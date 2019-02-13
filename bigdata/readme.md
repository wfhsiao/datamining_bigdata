* filtering data of DataFrame<br />
* #note use .loc to set conditions and use | for or condition<br />
ndf=df.loc[df['word'].isin(res) | df['Category'].isin(['中高級'])]<br />
print(ndf.shape)<br />
ndf.head(3)<br />
<br />
* update conda<br />
`conda clean --all`<br />
`conda update conda`<br />
`conda update --all`<br />

* matplotlib set fontsize 
<pre>plt.rcParams.update({'font.size': 22})</pre>

* matplotlib set figsize 
<pre>
plt.figure(figsize=(6, 6))
# for dataframe.plot
df.plot(kind='bar', fontsize=14, figsize=(8,8))
plt.legend(loc='upper right', bbox_to_anchor=(1.3,1), fontsize=14)
</pre>

* matplotlib set legend loc, for fontsize see the above 
<pre>plt.legend(loc='upper right', bbox_to_anchor=(1.5,1))</pre>
<pre>
labels=['東部','西部','南部','北部']
sizes=[6,10,20,15]
colors=['red','green','blue','yellow']
explores=[0,0,0.05,0]
plt.rcParams.update({'font.size': 22})
width = 6
height = 6
plt.figure(figsize=(width, height))
plt.pie(sizes,explode=explores,colors=colors,labels=labels, shadow=True,autopct="%.1f%%")
plt.axis('equal')
plt.legend(loc='upper right', bbox_to_anchor=(1.5,1))
plt.show()
</pre>
