# Generate_All-Combinations

Written the code in Python to generate all the combination of numbers given in the range:
x = [1,2,3,4,5,6,7,8]
combo=0
for i in combinations(x, 4):
    combo=combo+1
    print('Set #{}: {}'.format(i, combo))  
