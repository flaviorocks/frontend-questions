#Frontend Questions

Frontend interview questions

## Essential

### HTML/CSS

1. What's the first tag of an HTML[^1] document?

	<!DOCTYPE html>
	
2. What's the difference between *div* and *span* elements?
	
	**span:** inline element
	Mostly used for small chunks of text in the middle of a line (eg: in the middle of a paragraph).
	
	**div:** block-line element
	Used as a generic page structure element.
	
3. What's the difference between id (#) and class (.) selectors in CSS[^2] and how would you use them?
	
	The id selector targets a single item given the id is unique.
	The class selector targets every element that has the selector in it's class attribute. This is valuable for reusability.
	
### JavaScript

### AngularJS

1. What's a directive and what's it used for?

	A directive is the bridge between Angular and the DOM[^3].
	
	Uses:
	- Code block reuse;
	- Interaction with libraries external to Angular (eg: any jQuery library).
	
2. What are the different types of directive restrictions?

	- Class
	- Element
	- Attribute
	- Comment

## Basic

### HTML/CSS
	
### JavaScript

1. What's the difference between **==** (double equality) and **===** (triple equality)?

	**Double Equality:** validates the value e tried to convert the valitation elements to the same type.
	
	**Triple Equality:** validates value and type.
	
2. What's the difference between **null** and **undefined**?

	**null:** value.
	Used as no value or invalid value
	
	**undefined:** type.
	Default variable value.


### AngularJS

1. What is Databinding in AngularJS?

	Data binding is the automatic synchronization of data between model and view components. 
	ng-model directive is used in data binding.
	
2. What are the controllers in AngularJS?	

	Controllers are JavaScript functions that are bound to a particular scope. They are the prime actors in AngularJS framework and carry functions to operate on data and decide which view is to be updated to show the updated model based data.


## Intermediate

### HTML/CSS

1. What is specificity? How is specificity calculated?

	Process of determining which css rule will be applied to an element. 
	
	0. Type selectors (eg: h1, span, div, ...) 
	inline style usually wins then 
	2. ID selector 
	3. class (or pseudo-class or attribute selector)
	4. universal selector (*) has no specificity.
	

### JavaScript

### AngularJS

## Advanced

### HTML/CSS
	
### JavaScript

1. How to extend an initialized Object (Class)?

	By using the Prototype Chain.


### AngularJS


[^1]: HTML - Hyper Text Markup Language
[^2]: CSS - Cascading Style Sheets
[^3]: DOM - Document Object Model 
