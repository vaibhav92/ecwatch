# ecwatch
Indian general election 2019 results watcher

_Description:_  
Fetch and dump the general election results of a particular constituency from the election commission results page from ECI results patch.

*****WARNING / DISCLAIMER****:  
Results are provided from "Election Commission of India" site(http://results.eci.gov.in/pc/en/partywise/index.htm) as it is and no sort of validation or correction is performed on the actual results. Hence I wont accept any liability or accountability for any discrepancies in reported results.

_Usage:_  
ecwatch [-l | -h | <constituency-name>]"
	-l: Lists the name of all possible constituencies
	-h: Show this message
	<constituency-name>: Any valid name from constituency list

_Examples:_  

1. List results of Amethi constituency:  
~~~
  $ ./ecwatch amethi
  Fetching result...Ok
  Parsing..Ok
  ==============================================
  Uttar Pradesh-Amethi
  ==============================================
  1:Smriti Irani         467032
  2:Rahul Gandhi         411346
  3:Dhurv lal            7779
  4:Afajal Varis         6164
  5:Ram Sajiwan          5580
  ...
  *snip*
~~~

2. List available constituency names:  
~~~
  $ ./ecwatch -l
  Valid Constituencies:
  kolkata uttar
  robertsganj
  chennai south
  kandhamal
  barpeta
  ..
  ..
  *snip*
~~~

_Author_:  
Vaibhav Jain <ecwatch@vaibhajain.info>
