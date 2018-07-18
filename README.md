# smooth - A simple Stata scheme
Welcome to the smooth repo!

# Installation
To install, enter the following into the Stata command window:
```
cap ado uninstall "scheme-smooth"
net install scheme-smooth, from("https://raw.githubusercontent.com/jandrewsmith03/smooth/master/")
```

# Example
To see this scheme in action, copy and paste the following into the Stata command window:
```
sysuse auto, clear
twoway (scatter mpg price) (qfit mpg price), scheme(smooth)
```

# Author
Jonathan "Andrew" Smith

University of Chicago

Email: jas3@uchicago.edu
