Minimum Number of Platforms Required for a Railway/Bus Station
Given arrival and departure times of all trains that reach a railway station, the task is to find the minimum number of platforms required for the railway station so that no train waits.
We are given two arrays which represent arrival and departure times of trains that stop.

Examples:

Input: arr[] = {9:00, 9:40, 9:50, 11:00, 15:00, 18:00}
dep[] = {9:10, 12:00, 11:20, 11:30, 19:00, 20:00}
Output: 3
Explantion: There are at-most three trains at a time (time between 11:00 to 11:20)

Input: arr[] = {9:00, 9:40}
dep[] = {9:10, 12:00}
Output: 1
Explantion: Only one platform is needed.


OR

Suppose you have some guests arriving at a party. For each guest, you are given the arrival and departure time. 
When a guest arrives he is given a wine glass and when he leaves he returns that wine glass (it becomes available to be given to another guest). 
Find the minimum number of wine glasses needed to serve all the guests. 
The arrival and departure team can only be between 1800 to 2359 hours.

