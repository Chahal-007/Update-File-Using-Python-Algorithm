# Update-File-Using-Python-Algorithm

<h2>Project Description</h2>
<P>In this project work,I will work with a text file that contains a series of IP addresses that can access restricted information. In this file, there are IP addresses that should no longer have access to restricted information, and those IP addresses must be removed. Python can automate this process of keeping files up-to-date through algorithms. </P>
<h2>Data Resources</h2>
<h5> Allowed_IP_List.txt  </h5>
<p>It contains a series of IP addresses that are allowed to access restricted information.</p>
<h5>Removed_IP_list</h5>
<p>It contains the list of IP addresses to be removed from the [Allowed_IP_List.txt].</p>

<h2>Scenario</h2>
<p>Develop an algorithm that parses a file containing IP addresses that are allowed to access restricted content and removes addresses that no longer have access.</p>

<h4>Task One: Display lists of all IP addresses are there and which needs to remove </h4>
<p align=left>
<p align=center> List of all IP addresses in [Allowed_IP_list.txt]
</p>
<p align=center> <img width="645" alt="image" src="https://github.com/Chahal-007/Update-File-Using-Python-Algorithm/assets/62164775/d03820a6-9c44-42d5-a9ac-2d6a00afce8a">
</p>
<p align=center> IP addresses that need to be removed from [Allowed_IP_list.txt]
</p>
<p align=center><img width="609" alt="image" src="https://github.com/Chahal-007/Update-File-Using-Python-Algorithm/assets/62164775/42d79fe7-a87e-4999-8392-b4fb2440ca1c">
</p>
</br>
<h4>Task Two: Open,Read the file content and Convert String into a List</h4>
<p align=center><img width="962" alt="image" src="https://github.com/Chahal-007/Update-File-Using-Python-Algorithm/assets/62164775/ec5eb115-d36c-4b70-863c-d21a69fc4d08">
</p>
</br>
<h4>Task Three: Remove the addresses from the list using an iterative and conditional statement. </h4>
<p align=center><img width="837" alt="image" src="https://github.com/Chahal-007/Update-File-Using-Python-Algorithm/assets/62164775/14144ee4-0e74-4fb3-b32b-e88ab5107dd5">
</p>
<h4>Task Four: Update the file using function and verify updated IP addresses.</h4>
<p align=center><img width="893" alt="image" src="https://github.com/Chahal-007/Update-File-Using-Python-Algorithm/assets/62164775/557e7227-4469-4d13-8977-a5bbe3ce2242">
</p>
</br>
<h4>Summary</h4>
<p>
  
 - I created an algorithm that removes IP addresses given in a "removed_IP_list" variable from the "Allowed_IP_list.txt" file of approved IP addresses.
 - This algorithm involved opening the file, converting it to a string to be read, and then converting this string to a list stored in the variable all_Ip_addresses. 
 - I then iterated through the IP addresses in removed_IP_list & all_Ip_Addresses and evaluated if the ip addresses was in the list. If it was, then I applied the .remove() method     to remove the retricted IP address from all_Ip_addresses.
 - After this, I used the .join() method to convert the all_Ip_addresses back into a string so that I could write over the contents of the "Allowed_Ip_list.txt" file with the updated list of IP addresses.
</p>
</br>
</p>
