# Practice to build your Command-Line Utility 

## Specify which languge to excute your script by adding first line as follows
 
'''
  #!/usr/bin/env ruby
'''

##Put your script in usr/local/bin and make sure it is executable(chmod +x my_script)(This is already set in the path, you can check by doing an echo $PATH)

##Create a folder in your home directory called bin. (For your personal scripts)

* cd ~ (Takes you to your home directory)
* mkdir bin (create a bin folder)
* vim .bash_profile (to set path environment variable)
* export PATH="$HOME/bin:$PATH" (Press i then add this line and then do esc and type :wq)
#Now you can just type the name of your script and run it from anywhere you want.
