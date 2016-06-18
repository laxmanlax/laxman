#All importent python concepts 
What does "if __name__ == '__main__':" do? 


Ans: When the Python interpreter reads a source file, it executes all of the code found in it. Before executing the code, it will define a few special variables. For example, if the python interpreter is running that module (the source file) as the main program, it sets the special __name__ variable to have a value __main__. If this file is being imported from another module, __name__ will be set to the module's name.

    import: __name__ = module's filename
    if statement == False, and the script in __main__ will not be executed
    direct run: __name__ = __main__
    if statement == True, and the script in __main__ will be executed
