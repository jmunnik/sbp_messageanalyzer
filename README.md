sbp_messageanalyzer Cookbook
===================
This cookbook will install Microsoft Message Analyzer 1.1 (which replaces Microsoft Network Monitor) on a Windows system


Requirements
------------
The cookbook depends on the windows cookbook


Attributes
----------
default['msganalyzer']['package_name']
default['msganalyzer']['url']
default['msganalyzer']['checksum']


Usage
-----
Just include `sbp_messageanalyzer` in your node's `run_list`


Contributing
------------
	1. Fork the repository on Github
	2. Create a named feature branch (i.e. `add-new-recipe`)
	3. Write you change
	4. Write tests for your change (if applicable)
	5. Run the tests, ensuring they all pass
	6. Submit a Pull Request


License and Authors
-------------------

Authors: Joris van Lieshout

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0
