# RPA-challenge
This process is pretty simple it reads an excel file with information about workers and uploads it to a online form, the catch is that the form changes each time that a worker info is uloaded. Pretty simple logic to apply to the selectors, basically you set the words like "Name" as a strict anchor and then it searches for the text box nearby. There are some catches in the excel file so make sure you use .trim as good practice and to avoid errors.
