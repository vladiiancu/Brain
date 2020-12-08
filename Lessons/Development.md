When parsing, it's best your evaluation not be based on things like spaces, tabs and such. They are too fragile. 

When creating your class, functions, file etc, from a quick scan you should be able to spot dependencies by looking at function parameters being used. 
If there are no parameters anywhere, it's a sign of a problem. 

Try to limit the nesting level to max 2-3. 

