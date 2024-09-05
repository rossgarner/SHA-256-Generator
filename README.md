# SHA-256-Generator

As marketers we often want to target users based on Device IDs eg. users that opened my app in last XX days, and did(not) purchase etc. We can create segments in our DMP and share those with DSPs assuming there is a direct integration or we can integrate with a composable CDP such as High Touch or Liveramp. 
If neither of those options are available to you, we can go old school with 'customer match' audiences. The problem is we need to hash the device IDs to upload them to DSPs. 

I built this generator function to do the task for me! I was trawling the internet trying to find a solution in Excel or Google sheets but couldn't find one that didn't involve writing code in VBA. 
