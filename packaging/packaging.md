1. Use a sample project as a template. 
For example https://github.com/pypa/sampleproject

2. Run ```python setup.py sdist``` for making source distribution.
This is when you dont have any extentions such as C libs. In that case a binary distribution might be needed. 

3. To register with pypa:  
```python setup.py register```  For first time, you register a user/pass and activate account with an email address acknowledgement. Subsequently use this to command and select the login option with pypi  

4. Once logged in, run below command to upload package:  
```python setup.py sdist upload```  

5. For binary packages. (need wheel package locally to build)  
```python setup.py bdist_wheel```  
