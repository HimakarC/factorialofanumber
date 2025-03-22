# factorialofanumber

#Read a number from user <br>
echo "Enter integer: " <br>
read num <br>
fact=1 #initialize this variable without any space <br>
#Declaring as fact = 1 is Invalid and shows error <br>
while [ $num -gt 1 ] <br>
do <br>
  fact=$((fact * num)) <br>
  num=$((num - 1)) <br>
done <br>
echo $fact  #Display the facorial of a number.
