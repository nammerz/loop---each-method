loop---each-method
==================
x = [1, 2, 3, 4, 5]
x.each do |a|
  a + 1
end

#When ran through IRB, it will return the same because the program as the array. Since a + 1 does not have an output i.e. "puts" then the program skips it and simply just enters the array itself.
