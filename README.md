# Week-2-Day-2_CT_Python_HW
Jupyter Notebook &amp; Python Basics

EXERCISE #1

# Use the following list - [1,11,14,5,8,9]

l_1 = [1,11,14,5,8,9]


def less_than_ten(lst):

    """
    had to look up 'how to'/'what will' etcto get started:
    this will return list of numbers that are <10 from input list provided above 

    so Parameters here: 
        1st (list): a list of numbers

    Returns:
        list: a list of numbers that are <10
    
    """

    result = []   
    #create an empty list to store the result

    for num in lst:   
    #this will "go over" or aka "iterate" every element in the input list above provided


        if num < 10:  
    #check if the number is <10

            result.append(num)  
    #IF number is <10, THEN ad it to the RESULT LIST

    return result  
 #return the RESULT LIST


l_1 = [1, 11, 14, 5, 8, 9]
#to use function, "calling" it here to pass in list of numbers as "ARGUMENT" and PRINT to displauy OUTPUT
result = less_than_ten(l_1
print(result)


[1, 5, 8, 9]




EXERCISE #2

