------------------------------------------------------------------------
This is the project README file. 
Utilizes generics with a sorting algorithm
Takes in an array of any type and sorts into smallest, largest, and then sorts 
the arrays from low to high or in alphabetical order 
------------------------------------------------------------------------

PROJECT TITLE: GenericSortingAlgorithm
PURPOSE OF PROJECT: To use generics
VERSION or DATE: 10/10/2017
HOW TO START THIS PROJECT: Open files in BlueJ and run the main method
AUTHORS: Kyle M. Shive 


Below is the UML 

------------------------------------------------------------------------------------------------
                                            Algorithms
------------------------------------------------------------------------------------------------

------------------------------------------------------------------------------------------------
+sort(list: int[]): void <<static>>
-indexOfSmallestElement(list: int[], int startAt): int <<static>>
-swap(list: int[], int topIndex, int minIndex): void <<static>>

+getSmallestElement(list: int[]): int <<static>>
+getLargestElement(list: int[]): int <<static>>
------------------------------------------------------------------------------------------------

------------------------------------------------------------------------------------------------
                                           Main
------------------------------------------------------------------------------------------------

------------------------------------------------------------------------------------------------
+main(args: String[]): void <<static>
+displayArray(label: String, list: int[]): void <<static>>
------------------------------------------------------------------------------------------------
