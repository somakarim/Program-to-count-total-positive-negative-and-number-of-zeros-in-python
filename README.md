# Program-to-count-total-positive-negative-and-number-of-zeros-in-python
positive_list =[]
negative_list= []
zero_list=[]
for x in range(1, 11):
    values= input('Enter values: ')
if int(values)<0:
    negative_list.append(values)
elifint(values)>0:
    positive_list.append(values)
else:
    zero_list.append(values)

print('Number of positive numbers: ',len(positive_list))
print('Number of negative numbers: ', len(negative_list))
print('Number of Zeros: ', len(zero_list))
