#Frontend Questions

Frontend interview questions

## Essential

### HTML/CSS

1. What's the first tag of an HTML[^1] document?

	<!DOCTYPE html>
		
2. What's the difference between *div* and *span* elements?
	
	- **span:** inline element
	Mostly used for small chunks of text in the middle of a line (eg: in the middle of a paragraph).
	
	- **div:** block-line element
	Used as a generic page structure element.
	
3. What are the differences between *inline*, *block* and *inline-block*?

	- **Inline:** Elements do not break the flow. think of span it fits in the line. Important points about inline elements,
	margin/ padding will push other elements horizontally not vertically. Moreover, inline elements ignores height and width.

	- **Block:** Breaks the flow and doesn't sit inline. Usually used for containers like div, section, ul and also text p, h1,
	etc.

	- **Inline-block:** Will be similar to inline and will go with the flow of the page. Only differences is this this will
	take height and width.

	
4. What's the difference between id (#) and class (.) selectors in CSS[^2] and how would you use them?
	
	The id selector targets a single item given the id is unique.
	The class selector targets every element that has the selector in it's class attribute. This is valuable for reusability.
	
5. What does 'float' do?

    Float pushes an element to the sides of a page with text wrapped around it.
	
6. How absolute, relative, fixed and static position differ?

    **Absolute:** place an element exactly where you want to place it. absolute position is actually set relative to the element's parent. if no parent available then relatively place to the page itself.
    
    **Relative:** is position an element relative to itself (from where the element would be placed, if u don't apply relative positioning). for example, if you set position relative to an element and set top: 10px, it will move 10px down from where it would be normally.
    
    **Fixed:** element is positioned relative to viewport or the browser window itself. viewport doesn't change if you scroll and hence fixed element will stay right in the same position.
    
    **Static:** element will be positioned based on the normal flow of the document. Usually, you will use position static to remove other position that might be applied to an element.
    
	
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

	**Double Equality (==):** validates the value e tried to convert the valitation elements to the same type.
	
	**Triple Equality (===):** validates value and type.
	
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
	
	1. Type selectors (eg: h1, span, div, ...) 
	inline style usually wins then 
	2. class (or pseudo-class or attribute selector)
	3. ID selector 
	4. universal selector (*) has no specificity.
	
	[Ref](https://developer.mozilla.org/en/docs/Web/CSS/Specificity)

### JavaScript

### AngularJS

1. Which components can be injected as dependencies?
	
	Value, Factory, Service, Provider and Constant.

## Advanced

### HTML/CSS
	
### JavaScript

1. How to extend an initialized Object (Class)?

	By using the Prototype Chain.


### AngularJS



####Reference 

- [That JS Dude](http://www.thatjsdude.com/interview/)

#####Footnotes

[^1]: HTML - Hyper Text Markup Language
[^2]: CSS - Cascading Style Sheets
[^3]: DOM - Document Object Model 