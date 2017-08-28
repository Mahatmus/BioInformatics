# T-testing and multi test corrections

In this small project, I demonstrate the use of significance testing using 3 approaches, as well as show and briefly discuss some differences between them.

This is done on an example of Standford School of Medicine dataset, describing gene activities among cancer patients.

Methods used:
- Basic T-Tests
- FWER corrected T-Tests
- FDR corrected T-Tests

[Ipython Notebook](https://github.com/Mahatmus/BioInformatics/blob/master/BioInformatics_Study_Example.ipynb)
 demonstrates a few important points:
 - Using Standard T-tests without applying multi test correction may yield too many statistically different results, with a high proportion of Type I erros
 - Using FWER correction, while making sure that amount of Type I errors is minimized, may have a negative impact on the amount of interesting finidings obtained from the study due to a high proportion of Type II errors
 - Using FDR correction overcomes some problems of FWER correction, but allows for more Type I errors
 
