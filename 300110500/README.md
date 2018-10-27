def quicksort (array) :
  if len (array) < 2 :
    return array
  else :
    pivot = array [0]
    less = [ i for i in array [ 1 :]
    greater = [ i for i in array [ 1 :] if i > pivot
    return quicksort ( less ) + [ pivot ] + quicksort (greater)
print quick sort ([10, 5, 2, 3])
