```mermaid
graph TD;
    Start-->Initialize_a_variable=0;
	Initialize_a_variable=0-->Read_the_input_of_numbers;
  Read_the_input_of_numbers-->For_each_number_in_the_input;
For_each_number_in_the_input-->Calculate_the_square_of_the_number;
Calculate_the_square_of_the_number-->Add_the_square_to_the_'sumOfSquares'_variable;
Add_the_square_to_the_'sumOfSquares'_variable-->Display_the_'sumOfSquares';
Display_the_'sumOfSquares'-->End;
End-->Start;


 
  



    
``` 
