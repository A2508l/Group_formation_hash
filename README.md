# Group_formation_hash

The code has 4 seperate hash functions .<br>
<ul>
    <li> fold_hash() </li>
    <li> mid_sq_hash() </li>
    <li> digit_extraction_hash() </li>
    <li> custom_hash() </li>
</ul>
<br><br>
The code takes input from a csv file calculate the number of groups to be created and base on the edges cases it decides weather group must have 8 or 9 people for uniform distribution.
<br><br>
For each input taken from csv file a random number is generated for the same and is then moded by 4 which decides which hash function is to be used for the input.<br>
After that for dispute resolving chaining method is used.<br><br>
The result is then printed as a 2d list of roll numbers within a group
<br><br>
This a dynamic hash code as it decides on the number of teams and team members and also for each time code is rum different teams are created as it totaly depends on the random number that which hash function to be used
