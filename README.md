# factorialofanumber

#Read a number from user
echo "Enter integer: "
read num
fact=1 #initialize this variable without any space
#Declaring as fact = 1 is Invalid and shows error
while [ $num -gt 1 ]
do
  fact=$((fact * num))
  num=$((num - 1))
done
echo $fact  #Display the facorial of a number.
