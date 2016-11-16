This is the medWebSource code done at 2016/11/16 15:20


**you can jshint your develping code anywhere with command line in this file:**

	if jshint is not installed yet, you may install it globally using the following command:
				
				npm install -g jshint
				
	After this, you can use the jshint command-line interface.It is common to install JSHint as a development dependency within an existing Node.js project:
				
				npm install --save-dev jshint
				
	Then, you can check any js file with command:
				
				jshint (file-path-and-)name
				
	You may also use "gulp jshint" to check all of your js code when the gulp part is done.
	
	
***much more importantly, you can get the release version from developing version in this way:***
	
	1.you may manipulate your js code in the dev file(app) and run a server to check with appSouce.js at port 3015
	
	2.run command "npm install" to install packages needed for gulp (if it's slow and you are in China, please try "cnpm", it works for me)
	
	3.After packages installed, run command "gulp" to get the release version which you will find in "dist" file and may check with app.js at port 3016

	
If any problem, please send to my email: lixiaoyu0575@qq.com#medWebCode
"# medWebCode" 
