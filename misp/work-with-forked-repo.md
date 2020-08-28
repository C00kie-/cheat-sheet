### Work with forked repositories

Once the repository is forked from the original project and cloned on your machine:

Add the original project repository as a remote (you will need to pull updates from it):
 
      $git remote add [name you give localy to this remote] [adresse of the repository.git]
      
 Pull from the original remote:
 
      $git pull [name given to the remote] main
 **main** is tells here on with branch you want to merge new data, otherwise it's just fetched.
 
 Then push the new data on your fork online (such as your github repository for example)
 
       $git push origin 
