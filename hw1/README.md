# MAS.500 HW1

Penny Webb and Jasmin Rubinovitz

This code runs a research question using Media Cloud API.
This is homework assignment 1 for MAS.500 class - programming module.

## Research Question:
Has the converstaion about bees increased between 2013 and 2014?

### Installing:
run: `pip install -r requirments.txt`

### Running:
Edit "template_config.cfg" file: change "add your media cloud api key here!" to be your media cloud api key. save the edited file as a new file called "config.cfg"  
run: `python hw1.py`

### Command Line tool - hw2
The file compare.py is a command line tool that compare the use of a word between 2013 and 2014.
To run the file:  
`python compare.py <word> <optional other words>`  
For example to ask if the word "coffee" was used more in 2013 or 2014 run `python compare.py cofee`  

If you want to ask about the mentioning of 2 or more terms together in the same artical just list them in the command.  
For exmaple, to compare the use of the terms "Israel" and "War" in the same article between 2013 and 2014 run: `python compare.py israel war`  

For testing a number of words, not necceraly mentioned together add quatioton marks and the word OR.  
For example, to test how many times the words bee or bees or honey were mentioned in 2013/2014 run: `python compare.py "bee OR bees OR honey"`  
  
You can also change the periods being comapred be changing the date values in your config.cfg file.