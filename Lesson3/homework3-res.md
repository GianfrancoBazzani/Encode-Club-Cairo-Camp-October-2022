# Homework 3
1. **In the [Cairo Playground](https://www.cairo-lang.org/playground/) use the Hello playground example**

	a) Run the program and see the output in the console
	
	b) Debug the program, look at the memory and the watch window, do you understand how the output_ptr is being used?
	
	
	
	Yes, I can see that in every call of the serialize_word function 2 arguments are passed. In the Cairo code seems that serialize_word has only one argument, but if you analyze the memory you will see that output_ptr is pushed too before the serialize_word call. Also, you can see that output_ptr value is returned from every serialize_word call, you can see in the memory that his value is pushed just before the destination jump pointer en each serialize_word return.

	
2. **Add a function called `square` that will be called from the main function. The `square` function should have one parameter `x` and return the square of `x`.**

````
	// Square func
	func square(x: felt) -> felt {
    		return(x*x);
	}
````



3. **In the main function call the `square` function and output the result.**

````
	func main{output_ptr: felt*}() {
    	tempvar x = 10;
    	tempvar y = x + x;
   	tempvar z = y * y + x;
   	serialize_word(x);
    	serialize_word(y);
    	serialize_word(z);
    
    	tempvar square_val = square(5);
    	serialize_word(square_val);
    	return ();
	}
````
