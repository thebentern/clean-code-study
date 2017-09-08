# Error Handling – Chapter 7

## Obscuring Logic

* If error handling obscurs logic, it's wrong

## Exceptions instead of return codes

* Exceptions are built into langauges / frameworks
* Use them instead of making custom error return code structures
* Reduces clutter

## Write Your Try-Catch-Finally Statement First

* Try blocks are like transactions
* Catch blocks should leave your program in a consistent state, regardless of what happens in the try
* Write tests around expected exception handling under certain conditions

## Provide Context with Exceptions

* Use informative error messages and relativant exception parameters

## Define Exception Classes in Terms of a Caller’s Needs

* How they are caught?

## Define the normal flow

* Cleanly separate business logic from  error handling

## Don’t Return Null

* Returning null creates more work for consumers down the line

## Don’t Pass Null

* Same principal as above
