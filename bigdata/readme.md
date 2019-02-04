* matplotlib set fontsize *
<code>plt.rcParams.update({'font.size': 22})</code>

* matplotlib set figsize *
width = 6
height = 6
plt.figure(figsize=(width, height))

* matplotlib set legend loc *
plt.legend(loc='upper right', bbox_to_anchor=(1.5,1))
<code>
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
</code>
