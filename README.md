Download Link: https://assignmentchef.com/product/solved-soft8033-assignment-1-map-reduce
<br>



From the window you can see the sun shining in a lovely spring morning.

Its Monday, 10am, and you are in the open plan office of a new start-up, OptimiseYourJourney, which will enter the market next year with a clear goal in mind: “<em>leverage Big Data-based technologies for improving the user experience in transportation”</em>.

The start-up is at a very early stage, and has no clear product in mind yet.                  However, they have offered a short-term internship in their Data Analytics Department to help them exploring the datasets, technologies and techniques that can be applied in their future products. They do not pay very well (0€ per hour), but you see this as a good opportunity to complement your knowledge in the module Big Data &amp; Analytics you are studying at the moment, so you have decided to give it a go.

In the department meeting that has just finished your boss was particularly happy. During the weekend he was exploring public datasets over the internet and he found a dataset regarding the New York City Bike Sharing System: <u>https://www.citibikenyc.com/</u>

The official website (<u>https://www.citibikenyc.com/system-data</u>) provides publicly available datasets in a monthly basis. Each of these datasets amalgamate all the bike trips of the month. For example, the files “201905-citibike-tripdata.csv.zip”, “201906-citibike-tripdata.csv.zip” and “201907-citibike-tripdata.csv.zip” contain information for all the trips that took place in May, June and July of 2019, resp.

Your boss thinks this dataset provides a great opportunity to explore the potential of MapReduce in analysing large datasets. He has already cleaned the dataset for you to perform some data analysis on it.

<strong><u>DATASET:</u>  </strong>

This dataset occupies ~80MB and contains 73 files. Each file contains all the trips registered the CitiBike system for a concrete day:

<ul>

 <li>csv =&gt; All trips registered on the 1<sup>st</sup> of May of 2019.</li>

 <li>csv =&gt; All trips registered on the 2<sup>nd</sup> of May of 2019.</li>

 <li>…</li>

 <li>csv =&gt; All trips registered on the 12<sup>th</sup> of July of 2019.</li>

</ul>




Altogether, the files contain 444,110 rows. Each row contains the following fields:

<strong><em>start_time , stop_time , trip_duration , start_station_id , start_station_name , start_station_latitude , start_station_longitude , stop_station_id , stop_station_name , stop_station_latitude , stop_station_longitude , bike_id , user_type , birth_year , gender , trip_id </em></strong>

<strong><em> </em></strong>

<ul>

 <li><strong>(00) <em>start_time</em></strong></li>

</ul>

! A String representing the time the trip started at.

&lt;%Y/%m/%d %H:%M:%S&gt;

!Example: “2019/05/02 10:05:00”

<ul>

 <li><strong>(01) <em>stop_time</em></strong></li>

</ul>

! A String representing the time the trip finished at.

&lt;%Y/%m/%d %H:%M:%S&gt;

!Example: “2019/05/02 10:10:00”

<ul>

 <li><strong>(02) <em>trip_duration</em></strong></li>

</ul>

!An Integer representing the duration of the trip.

!Example: 300

<ul>

 <li><strong>(03) <em>start_station_id</em></strong></li>

</ul>

!An Integer representing the ID of the CityBike station the trip started from.

!Example: 150

<ul>

 <li><strong>(04) <em>start_station_name</em></strong></li>

</ul>

!A String representing the name of the CitiBike station the trip started from.

!Example: “E 2 St &amp;; Avenue C”.

<ul>

 <li><strong>(05) <em>start_station_latitude</em></strong></li>

</ul>

!A Float representing the latitude of the CitiBike station the trip started from.

!Example: 40.7208736

<ul>

 <li><strong>(06) <em>start_station_longitude</em></strong></li>

</ul>

!A Float representing the longitude of the CitiBike station the trip started from.

! Example:  -73.98085795







<ul>

 <li><strong>(07) <em>stop_station_id</em></strong></li>

</ul>

!An Integer representing the ID of the CityBike station the trip stopped at.

!Example: 150

<ul>

 <li><strong>(08) <em>stop_station_name</em></strong></li>

</ul>

! A String representing the name of the CitiBike station the trip stopped at.

!Example: “E 2 St &amp;; Avenue C”.

<ul>

 <li><strong>(09) <em>stop_station_latitude</em></strong></li>

</ul>

!A Float representing the latitude of the CitiBike station the trip stopped at.

!Example: 40.7208736

<ul>

 <li><strong>(10) <em>stop_station_longitude</em></strong></li>

</ul>

!A Float representing the longitude of the CitiBike station the trip stopped at.

! Example:  -73.98085795

<ul>

 <li><strong>(11) <em>bike_id</em></strong></li>

</ul>

! An Integer representing the id of the bike used in the trip.

! Example:  33882.

<ul>

 <li><strong>(12) <em>user_type</em></strong></li>

</ul>

! A String representing the type of user using the bike (it can be either “Subscriber” or “Customer”).

!Example: “Subscriber”.

<ul>

 <li><strong>(13) <em>birth_year</em></strong></li>

</ul>

! An Integer representing the birth year of the user using the bike.

! Example:  1990.

<ul>

 <li><strong>(14) <em>gender</em></strong></li>

</ul>

! An Integer representing the gender of the user using the bike (it can be either 0 =&gt; Unknown; 1 =&gt; male; 2 =&gt; female).

! Example:  2.

<ul>

 <li><strong>(15) <em>trip_id</em></strong></li>

</ul>

! An Integer representing the id of the trip.

! Example:  190.

<strong> </strong>

<strong><u>TASKS / EXERCISES.</u></strong>

The tasks / exercises to be completed as part of the assignment are described in the next pages of this PDF document.




<ul>

 <li>The following exercises are placed in the folder <strong>my_code:</strong></li>

</ul>

<ol>

 <li><strong>A01_Part1/</strong>A01_Part1.py 2. <strong>A01_Part2/</strong>A01_Part2.py

  <ol start="3">

   <li><strong>A01_Part3/</strong>py</li>

   <li><strong>A01_Part4/</strong>py</li>

   <li><strong>A01_Part4/</strong>py</li>

   <li><strong>A01_Part5/</strong>py</li>

   <li><strong>A01_Part5/</strong>py</li>

   <li><strong>A01_Part6/</strong>py</li>

   <li><strong>A01_Part6/</strong>py</li>

  </ol></li>

</ol>




<strong>Marks are as follows: </strong>

<ul>

 <li><strong>A01_Part1/</strong>py =&gt; 16 marks o <strong>A01_Part2/</strong>A01_Part2.py =&gt; 16 marks o <strong>A01_Part3/</strong>A01_Part3.py =&gt; 18 marks o <strong>A01_Part4/</strong>my_mapper.py =&gt; 8 marks o <strong>A01_Part4/</strong>my_reducer.py =&gt; 8 marks o <strong>A01_Part5/</strong>my_mapper.py =&gt; 8 marks o <strong>A01_Part5/</strong>my_reducer.py =&gt; 8 marks o <strong>A01_Part6/</strong>my_mapper.py =&gt; 9 marks o <strong>A01_Part6/</strong>my_reducer.py =&gt; 9 marks</li>

</ul>




<strong>Tasks: </strong>

<ul>

 <li><strong>A01_Part1/</strong>py o <strong>A01_Part2/</strong>A01_Part2.py o <strong>A01_Part3/</strong>A01_Part3.py</li>

</ul>

<u>Complete the function </u><strong><u>my_main</u></strong><u> of the Python program.</u>

Do not modify the name of the function nor the parameters it receives.




<ul>

 <li><strong>A01_Part4/</strong>py o <strong>A01_Part5/</strong>my_mapper.py  o <strong>A01_Part6/</strong>my_mapper.py</li>

</ul>

<u>Complete the function </u><strong><u>my_map</u></strong><u> of the Python program.</u>

Do not modify the name of the function nor the parameters it receives.




<ul>

 <li><strong>A01_Part4/</strong>py o <strong>A01_Part5/</strong>my_reducer.py o <strong>A01_Part6/</strong>my_reducer.py</li>

</ul>

<u>Complete the function </u><strong><u>my_reduce</u></strong><u> of the Python program.</u>

Do not modify the name of the function nor the parameters it receives.

<strong> </strong>

<strong><u>TEST YOUR SOLUTIONS.</u></strong>

<strong> </strong>

<ul>

 <li>The folder <strong>my_results</strong> contains the expected results for each exercise.</li>

</ul>

o <strong>A01_Part1/</strong>result.txt o <strong>A01_Part2/</strong>result.txt o <strong>A01_Part3/</strong>result.txt o <strong>A01_Part4/1_my_map_simulation</strong> =&gt; 73 files for the output of each map process. o <strong>A01_Part4/2_my_sort_simulation/</strong>sort_1.txt =&gt; input for first reduce process.  o <strong>A01_Part4/2_my_sort_simulation/</strong>sort_2.txt =&gt; input for second reduce process.  o <strong>A01_Part4/3_my_reduce_simulation/</strong>reduce_sort_1.txt =&gt; output of first reduce.  o <strong>A01_Part4/2_my_reduce_simulation/</strong>reduce_sort_2.txt =&gt; output of second reduce. o <strong>A01_Part5/1_my_map_simulation</strong> =&gt; 73 files for the output of each map process. o <strong>A01_Part5/2_my_sort_simulation/</strong>sort_1.txt =&gt; input for first reduce process.  o <strong>A01_Part5/3_my_reduce_simulation/</strong>reduce_sort_1.txt =&gt; output of first reduce.  o <strong>A01_Part6/1_my_map_simulation</strong> =&gt; 73 files for the output of each map process. o <strong>A01_Part6/2_my_sort_simulation/</strong>sort_1.txt =&gt; input for first reduce process.  o <strong>A01_Part6/3_my_reduce_simulation/</strong>reduce_sort_1.txt =&gt; output of first reduce.




<ul>

 <li>Moreover, the subfolder <strong>my_results/check_results</strong> allows you to see if your code is producing the expected output or not.

  <ul>

   <li>The file <strong>py</strong> needs two folders and compares if their files are equal or not.</li>

   <li>When you have completed one part (e.g., A01_Part4), copy the folder <strong>my_results/A01_Part4</strong> into the folder <strong>my_results/check_results/Student_Attempts/A01_Part4</strong>.  o Open the file <strong>py</strong> and edit the line 112 with the value of the part you are attempting (e.g., part = 4).</li>

   <li>Run the program <strong>py</strong>. It will tell you whether your output is correct or not.</li>

  </ul></li>

</ul>







For example, as an example let’s run the Python program <strong>test_checker.py</strong> to see if the solution attempt done by the student for A01_Part1 and A01_Part4 is correct or not.

<ul>

 <li>9 test_checker.py   1</li>

</ul>

———————————————————- Checking :

./Assignment_Solutions/A01_Part1/result.txt

./Student_Attempts/A01_Part1/result.txt




Test passed!

———————————————————- Congratulations, the code passed all the tests!

———————————————————-

As we can see, the code of the student is correct, and thus it gets the marks.




<ul>

 <li>9 test_checker.py   4</li>

</ul>

———————————————————- Checking :

./Assignment_Solutions/A01_Part4/2_my_sort_simulation/sort_1.txt

./Student_Attempts/A01_Part4/2_my_sort_simulation/sort_1.txt




Test did not pass.

———————————————————- Checking :

./Assignment_Solutions/A01_Part4/2_my_sort_simulation/sort_2.txt

./Student_Attempts/A01_Part4/2_my_sort_simulation/sort_2.txt




Test passed!

———————————————————- Checking :

./Assignment_Solutions/A01_Part4/3_my_reduce_simulation/reduce_sort_1.txt

./Student_Attempts/A01_Part4/3_my_reduce_simulation/reduce_sort_1.txt




Test did not pass.

———————————————————- Checking :

./Assignment_Solutions/A01_Part4/3_my_reduce_simulation/reduce_sort_2.txt

./Student_Attempts/A01_Part4/3_my_reduce_simulation/reduce_sort_2.txt

Test passed!

———————————————————- Sorry, the output of some files is incorrect!

———————————————————-

As we can see, the code of the student is not correct, and thus it does not get the marks. The problem was that some output lines in some files were wrong.

<strong><u>Main Message</u></strong>

Use the program <strong>test_checker.py</strong> to ensure that all your exercises produce the expected output (and in the right format!).




<h1>EXERCISE 1.                                                                                (16</h1>

<strong> </strong>

<strong>Technology:  </strong>

Python (without using the MapReduce simulator).

<strong> </strong>

<strong>Your task is to: </strong>

<ul>

 <li>Compute the amount of trips starting from and finishing at each station_name.</li>

</ul>

<em> </em>

<u>Complete the function </u><strong><u>my_main</u></strong><u> of the Python program.</u>

<ul>

 <li>Do not modify the name of the function nor the parameters it receives.</li>

 <li>In particular, the function must read the dataset provided in input_folder and must open and write the results to output_file.</li>

 <li>You can use the auxiliary function process_line which, given one line from a dataset file, returns a tuple with its content. o You can also program any other auxiliary functions you might need.</li>

</ul>




<u>Results:</u>

Output one text line per station_name. Lines must follow alphabetic order in the name of the station. Each line must have the following format:

station_name t (total_trips_starting_from_the_station, total_trips_finishing_at_the_station) 





<h1>EXERCISE .                                                                                  (16</h1>

<strong> </strong>

<strong>Technology:  </strong>

Python (without using the MapReduce simulator).

<strong> </strong>

<strong>Your task is to: </strong>

<ul>

 <li>Compute the top_n_bikes with highest total duration time for their trips.</li>

</ul>

<em> </em>

<u>Complete the function </u><strong><u>my_main</u></strong><u> of the Python program.</u>

<ul>

 <li>Do not modify the name of the function nor the parameters it receives.</li>

 <li>In particular, the function must read the dataset provided in input_folder and must open and write the results to output_file. The number of bikes to output is specified by the parameter top_n_bikes. For example, if top_n_bikes = 10, then you must output the 10 bikes with highest total duration time for their trips.</li>

 <li>You can use the auxiliary function process_line which, given one line from a dataset file, returns a tuple with its content. o You can also program any other auxiliary functions you might need.</li>

</ul>




<u>Results:</u>

Output one text line per bike_id. Lines must follow decreasing order in highest total duration time for their trips. Each line must have the following format:

bike_id t (total_duration_time_for_their_trips, total_number_of_trips) 





<h1>EXERCISE .                                                                                  (18</h1>

<strong> </strong>

<strong>Technology:  </strong>

Python (without using the MapReduce simulator).

<strong> </strong>

<strong>Your task is to: </strong>

<ul>

 <li>Sometimes bikes are re-organised (moved) from station A to station B to balance the amount of bikes available in both stations. A truck operates this bike re-balancing service, and the trips done by-truck are not logged into the dataset. <u>Compute all the</u> <u>times a given </u><u>bike_id was moved by the truck re-balancing system.</u></li>

</ul>

<em> </em>

<u>Complete the function </u><strong><u>my_main</u></strong><u> of the Python program.</u>

<ul>

 <li>Do not modify the name of the function nor the parameters it receives.</li>

 <li>In particular, the function must read the dataset provided in input_folder and must open and write the results to output_file. The concrete bike to be tracked is specified by the parameter bike_id. For example, if bike_id = 35143, then you must track all the times the bike with id 35143 was moved by the truck re-balancing system.</li>

 <li>You can use the auxiliary function process_line which, given one line from a dataset file, returns a tuple with its content.</li>

 <li>You can also program any other auxiliary functions you might need.</li>

</ul>




<u>Results:</u>

Output one text line per moving trip. Lines must follow temporal order. Each line must have the following format:

<table width="574">

 <tbody>

  <tr>

   <td colspan="2" width="574">By_Truck t (time_it_was_logged_at_station2, station2_id, time_it_was_logged_at_station3</td>

  </tr>

  <tr>

   <td width="94">station3_id) 
</td>

   <td width="480"> </td>

  </tr>

 </tbody>

</table>

For example, if the dataset <strong><u>contains</u></strong> the following 2 trips:

<ul>

 <li><strong>Trip1:</strong> A user used bike_id to start a trip from Station1 on 2019/05/10 09:00:00 and finished the trip at Station2 on 2019/05/10 10:00:00</li>

 <li><strong>Trip2:</strong> A user used bike_id to start a trip from Station3 on 2019/05/10 11:00:00 and finished the trip at Station4 on 2019/05/10 12:00:00 And the dataset <strong><u>does not contain</u></strong> any extra trip:</li>

 <li><strong>Trip3:</strong> A user used bike_id to start a trip from Station2 and finish at Station3 anytime between 2019/05/10 10:00:00 and 2019/05/10 11:00:00</li>

</ul>

<u>Then it is clear that the bike was moved from Station2 to Station3 by truck, and we output:</u>

By_Truck t (2019/05/10 10:00:00, Station2, 2019/05/10 11:00:00, Station3) 








<h1>EXERCISE                                     7                                             (16</h1>

<strong> </strong>

<strong>Technology:  </strong>

Python – Use the MapReduce simulator.

<strong> </strong>

<strong>Your task is to: </strong>

<ul>

 <li>Compute the amount of trips starting from and finishing at each station_name.</li>

</ul>

<em> </em>

<strong><u>my_mapper.py</u></strong><u> =&gt; Complete the function </u><strong><u>my_map</u></strong><u> of the Python program.</u>  o Do not modify the name of the function nor the parameters it receives.  o In particular, the function must read the content of a file provided by my_input_stream and must write the results to the file provided by my_output_stream. There are no extra parameters provided via my_mapper_input_parameters. o You can use the auxiliary function process_line which, given one line from a dataset file, returns a tuple with its content. o You can also program any other auxiliary functions you might need.




<strong><u>my_reducer.py</u></strong><u> =&gt; Complete the function </u><strong><u>my_reduce</u></strong><u> of the Python program.</u>  o Do not modify the name of the function nor the parameters it receives.  o In particular, the function must read the content of a file provided by my_input_stream and must write the results to the file provided by my_output_stream. There are no extra parameters provided via my_reducer_input_parameters. o You can also program any other auxiliary functions you might need.




<u>Results:</u>

Output one text line per station_name. Lines must follow alphabetic order in the name of the station. Each line must have the following format:

station_name t (total_trips_starting_from_the_station, total_trips_finishing_at_the_station) 


<em> </em>

<em> </em>

<h1>EXERCISE                                     8                                             (16</h1>

<strong> </strong>

<strong>Technology:  </strong>

Python – Use the MapReduce simulator.

<strong> </strong>

<strong>Your task is to: </strong>

<ul>

 <li>Compute the top_n_bikes with highest total duration time for their trips.</li>

</ul>

<em> </em>

<strong><u>my_mapper.py</u></strong><u> =&gt; Complete the function </u><strong><u>my_map</u></strong><u> of the Python program.</u>  o Do not modify the name of the function nor the parameters it receives.  o In particular, the function must read the content of a file provided by my_input_stream and must write the results to the file provided by my_output_stream. There are no extra parameters provided via my_mapper_input_parameters. o You can use the auxiliary function process_line which, given one line from a dataset file, returns a tuple with its content. o You can also program any other auxiliary functions you might need.




<strong><u>my_reducer.py</u></strong><u> =&gt; Complete the function </u><strong><u>my_reduce</u></strong><u> of the Python program.</u>  o Do not modify the name of the function nor the parameters it receives.  o In particular, the function must read the content of a file provided by my_input_stream and must write the results to the file provided by my_output_stream. The extra parameter top_n_bikes is provided via my_reducer_input_parameters.

o You can also program any other auxiliary functions you might need.




<u>Results:</u>

Output one text line per bike_id. Lines must follow decreasing order in highest total duration time for their trips. Each line must have the following format:

bike_id t (total_duration_time_for_their_trips, total_number_of_trips) 





<h1>EXERCISE                                     9                                             (18</h1>

<strong> </strong>

<strong>Technology:  </strong>

Python – Use the MapReduce simulator.

<strong> </strong>

<strong>Your task is to: </strong>

<ul>

 <li>Sometimes bikes are re-organised (moved) from station A to station B to balance the amount of bikes available in both stations. A truck operates this bike re-balancing service, and the trips done by-truck are not logged into the dataset. <u>Compute all the</u> <u>times a given </u><u>bike_id was moved by the truck re-balancing system.</u></li>

</ul>

<em> </em>

<strong><u>my_mapper.py</u></strong><u> =&gt; Complete the function </u><strong><u>my_map</u></strong><u> of the Python program.</u>  o Do not modify the name of the function nor the parameters it receives.

<ul>

 <li>In particular, the function must read the content of a file provided by my_input_stream and must write the results to the file provided by my_output_stream. The extra parameter bike_id is provided via my_mapper_input_parameters. o You can use the auxiliary function process_line which, given one line from a dataset file, returns a tuple with its content. o You can also program any other auxiliary functions you might need.</li>

</ul>




<strong><u>my_reducer.py</u></strong><u> =&gt; Complete the function </u><strong><u>my_reduce</u></strong><u> of the Python program.</u>  o Do not modify the name of the function nor the parameters it receives.  o In particular, the function must read the content of a file provided by my_input_stream and must write the results to the file provided by my_output_stream. There are no extra parameters provided via my_reducer_input_parameters. o You can also program any other auxiliary functions you might need.




<u>Results:</u>

Output one text line per moving trip. Lines must follow temporal order. Each line must have the following format:

<table width="574">

 <tbody>

  <tr>

   <td colspan="2" width="574">By_Truck t (time_it_was_logged_at_station2, station2_id, time_it_was_logged_at_station3</td>

  </tr>

  <tr>

   <td width="94">station3_id) 
</td>

   <td width="480"> </td>

  </tr>

 </tbody>

</table>

For example, if the dataset <strong><u>contains</u></strong> the following 2 trips:

<ul>

 <li><strong>Trip1:</strong> A user used bike_id to start a trip from Station1 on 2019/05/10 09:00:00 and finished the trip at Station2 on 2019/05/10 10:00:00</li>

 <li><strong>Trip2:</strong> A user used bike_id to start a trip from Station3 on 2019/05/10 11:00:00                    and finished the trip at Station4 on 2019/05/10 12:00:00</li>

</ul>







And the dataset <strong><u>does not contain</u></strong> any extra trip:

<ul>

 <li><strong>Trip3:</strong> A user used bike_id to start a trip from Station2 and finish at Station3 anytime between 2019/05/10 10:00:00 and 2019/05/10 11:00:00</li>

</ul>

<u>Then it is clear that the bike was moved from Station2 to Station3 by truck, and we output:</u>

<h2>By_Truck t (2019/05/10 10:00:00, Station2, 2019/05/10 11:00:00, Station3) 
</h2>





