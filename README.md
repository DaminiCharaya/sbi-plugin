# sbi-plugin
It is a plugin to check which student did not give the fees for reappear exam or suppliment and the fine he/she needs to pay for exams.
save the files in htdocs of xampp.
you need to install website bootstrap ,fpdf,and PHPEXCEL-DEVELOPE to find out all the functionality.
appropriate folder is defined in plugin.html file you can also change it.
main motive of this is to compare the fees details of bank csv with three files of college like-reappear fees file,suppliment file and fine files .merging the all files of college with a column remarks like for reappear file remark is reappear.
plugin.html has three buttons upload student files which contains the buttons to upload all student files
second button contains convert payment data into excel format which is for uploading the bank csv which was tilde seperated in my case you can change in the code and can upload your csv too
third one will actually compare the files and will tell you about who paid the fees who didnot whose date is not matching or many more comparison are there
