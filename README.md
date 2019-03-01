# Print_Number
#Program that prints the numbers from 1 to 100. But for multiples of three print “Fizz” instead of the number and for the multiples of five print “Buzz”. For numbers which are multiples of both three and five print “FizzBuzz”. 

p_num = 1
while p_num <= 100
  if (p_num % 3 == 0) && (p_num % 5 == 0)
	puts 'fizzbuzz'
  elsif (p_num % 3 == 0)
  	puts 'fizz'
  elsif (p_num % 5 == 0)
  	puts 'buzz'
  else
  	puts p_num
  end
  p_num += 1
end
