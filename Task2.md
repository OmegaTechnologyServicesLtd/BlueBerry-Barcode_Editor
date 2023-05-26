```mermaid
graph TD;
    Start-->Initialize_a_variable_'Sum'=0;
	Initialize_a_variable_'Sum'=0-->Read_the_first_number_from_the_user;
  Read_the_first_number_from_the_user-->While_the_number_is_non-negative;
While_the_number_is_non-negative-->Add_the_number_to_the_'sum';
Add_the_number_to_the_'sum'-->Read_the_next_number_from_the_user;
Read_the_next_number_from_the_user-->Write_out_the_final_'sum';
 Write_out_the_final_'sum'-->End;
 End-->Start;
 



    
``` 
