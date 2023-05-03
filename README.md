# Week-2-Day-2_CT_Python_HW
Jupyter Notebook &amp; Python Basics

EXERCISE #1

# Use the following list - [1,11,14,5,8,9]

l_1 = [1,11,14,5,8,9]


def less_than_ten(lst):

    """
    had to look up 'how to'/'what will' etc to get started:
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

l_1 = [1,2,3,4,5,6]
l_2 = [3,4,5,6,7,8,10]

def merge_and_sort_lists(l_1, l_2):

    """
    had to look up 'how to'/'what will merge sort' etc to get started:
    this will merge and sort two lists together

    so Parameters here: 
        1st (list): the first list
        lst2 (list): The second list

    Returns:
        list: a sorted list containing all elements from l_1 AND l_2
    
    """

    merged_list = l_1 + l_2
    # CONCATENATE the two lists into a new list

    sorted_list = sorted(merged_list) 
    # SORT the now new MERGED list as was just done above

    return sorted_list
    # return the now fully processed SORTED list


l_1 = [1,2,3,4,5,6]
l_2 = [3,4,5,6,7,8,10]
# same as exercise #1: to use function, "calling" it here to pass in list of numbers as "ARGUMENT" and then PRINT to displauy OUTPUT

result = merge_and_sort_lists(l_1, l_2)
#SEE original list values above for the "def" first line of code here

print(result)

[1, 2, 3, 3, 4, 4, 5, 5, 6, 6, 7, 8, 10]

