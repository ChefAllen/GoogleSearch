********** Description **********

  This program is a script I made that takes an excel named "SearchTerms.xls" and searches the terms in that document, it then spits out an excel document that gives you the results per search and how long it took the find those results, It also captures the screen and saves it as a png and labels it appropriately for the search term

it will do this for Firefox, Chrome, and Internet Explorer

"SearchTerms.xls" can be edited manually to search any alphanumerical term and as many search terms as the user likes. 

********** Requirements **********

  The code can run from anywhere but the "Drivers" folder and the "SearchTerms.xls" need to be on the desktop and the desktop should be in the user index. If it isn't then the program wont be able to find what it needs to operate properly and am error will be generated.
  
  You will also need 4 libraries "client-combined-3.0.1-nodeps", "junit-4.10", "jxl-2.6", and "selenium-server-standalone" to run the script properly.

********** Input **********

  The only manual input nessicary are the terms you want to search for in the "SearchTerms.xls". the format that is present on the sample version that is here is the format nessicary for the script to work properly. Which is the first colmn, first row contains "Google terms to be searched" and then each cell after that in the same column contains one search term. 

The cell as a whole will be searched for not the individual words in the cell.


********** Output **********

  The script outputs first a results folder with will hold 3 folders labeled "Chrome", "Firefox", and "Internet Explorer". In each of those 3 folders the script will generate a .png file for each search term present in "SearchTerms.xls" and when complete with each search it will also generate "result.xls" which contains the search terms, how many results google got, and how long it took to find those results. The script also logs the steps as it goes through them.
  
  
********** How To Run **********

  The code has been compiled and it is present in the GoogleSearch\bin\GoogleSearch folder here and just run Webwork.class and it will exicute.

********** ToDo **********

  figure out some way of having the libraries as part of the code so you can compile the code from cmd and not be tied to going through a second party like eclipse which is where it was made. shouldn't be too difficult.
