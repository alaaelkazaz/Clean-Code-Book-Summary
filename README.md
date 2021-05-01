# Clean-Code-Book-Summary
A brief of Clean Code - A Handbook of Agile Software Craftsmanship by Robert C. Martin

## Index 
5. [Formatting](#Formatting)
6. [Objects and Data Structures](#objectsandDS)

## <a name="Formatting"> 5. Formatting </a>  
>When people look under the hood, we want them to be impressed with the neatness, consistency,
and attention to detail that they perceive. We want them to be struck by the
orderliness

#### 5.0 The purpose of formatting 
   - Code formatting is about communication, and
   - Communication is the professional developer’s first order of business.

   - The coding style and readability set precedents that continue to
      affect maintainability and extensibility.

   - Your style and discipline survives, even though your code does not.

#### 5.1 Vertical Formatting 
   - File size: Small files are usually easier to understand than large files are.
   - It's possible to build significand systems using files in range 200-500 lines.
    
#### 5.2 The Newspaper Metaphore
   - We would like a source file to be like a newspaper article.
   - The topmost parts of the source file should provide the high-level concepts and algorithms.
   - Detail should increase as we move downward, until at the end
      we find the lowest level functions and details in the source file.
    
#### 5.3 Vertical Openness Between Concepts
   - Each line --> clause, expression.
   - Each group of lines --> a complete thought.
   - We use blank line separations 

#### 5.4 Vertical Density
> If openness separates concepts, then vertical density implies close association.
   - Example : Useless comments in class declaraion makes it harder to read.

#### 5.5 Vertical Distance 
   - Concepts that are closely related should be kept vertically close to each other.
   - Related concepts should not be separated into different files unless you have a very good
     reason.
   - Variables should be declared as close to their usage as possible.
   - Control variables for loops should usually be declared within the loop statement, 
     in rare cases a variable might be declared at the top of a block or just before a loop in a
     long-ish function.
   - Instance variables should be declared at the top of the class.
   - Dependent Functions: If one function calls another, they should be vertically close.
   - Conceptual Affinity: Certain bits of code want to be near other bits. They have a certain
     conceptual affinity. The stronger that affinity, the less vertical distance there should 
     be between them.
   - Affinity causes:
            - Function dependance 
            - Funcion using a variable.
            - A group of functions perform similarly.
   -  Vertical ordering:
            - Function call dependencies to point in the downward direction.That is,
              a function that is called should be below a function that does the calling
#### 5.6 Horizontal Formatting
   - Programmers clearly prefer short lines.
   - Horizontal Openness and Density
            - We use horizontal white space to associate things that are strongly related and disassociate
              things that are more weakly related.
   - Horizontal Alignment: aligned, the problem is the length of the lists(Declared variables one after another for example), not
     the lack of alignment.
   - Indentation: to make this hierarchy of scopes visible, we indent the lines of source code in proportion
     to their position in the hiearchy.
   - Programmers rely heavily on this indentation scheme.
#### 5.7 Team Rules 
   - A team of developers should agree upon a single formatting style.
   - Remember, a good software system is composed of a set of documents that read nicely.
 
## <a name="objectsandDS"> 6. Objects and Data Structures </a> 

 

