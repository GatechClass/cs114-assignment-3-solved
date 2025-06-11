# cs114-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CS114 Assignment 3 Solved](https://mantutor.com/product/cs114-read-these-instructions-repeatedly-until-you-understand-then-begin-your-project-if-something-is-not-clear-ask-a-before-you-begin-a-solved-2/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113992&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS114 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
1. Log in to GitHub.

2. Fork this repo(sitory). See this video on how to carry out this step and step 3.

3. Clone your fork, using either the web site or the GitHub Desktop client.

4. Checkout your personalized branch, the one with your name and GitHub handle.

â– Introduction â–

Write a program that does the following:

1. Requests from the user a positive number representing the size of a matrix

2. Prints a matrix consisting of 0s

3. Populates the matrix with values from 1â€“(input Ã— input)

4. Prints the matrix with the newly-populated values

5. Swaps the contents of the matrix on one side of the diagonal formed from top right to bottom left with the other side, highlighting the elements along the diagonal and leaving them untouched/unswapped

6. Prints the flipped matrix

As mentioned in item 5, the elements in the diagonal must not be touched, while the other elements in the matrix must be swapped. The numbers in every cell of the matrix is arbitrary; each cell could have contained a letter, string, image, or other object/primitive. Numbers are being used in this assignment because they produce a sequence that is easy to follow when working with the matrix. A movie of how this assignment should behave in its resolved state is available here.

â– File List â–

This repo contains the following files, all required to carry out this assignment. Before you start working, ensure you understand the role of each file below.

1. Makefile â€” Run make in your command line interface, or CLI, from this repoâ€™s root folder to build your assignment. As you test input, run make run to only run a previously-compiled Java program, not compile it. Run make clean to remove the class file.

2. .editorconfig â€” Everything in this file is a redundancy of whatâ€™s already in the .editorconfig file you installed in your home folder. Itâ€™s here to make sure youâ€™re working with the formatting rules defined in .editorconfig, as this is part of your grade.

Ensure EditorConfig is working in VS Code, before beginning this assignment.

3. .gitignore â€” Do not modify this file.

4. Matrix.java â€” Where the entire Matrix class and its methods will be defined.

5. RunMatrix.java â€” Method main goes in this file, along withe the instantiation of the Matrix object and all the required behavior.

â– Rules â–

1. Your Matrix class should contain a single field called matrix of the primitive type required to create a matrix.

2. The Matrix constructor should accept an integer value as an argument named size, then create a matrix field whose width and height are equivalent to the integer passed to it. The constructor should also report to the user the dimensions of the matrix.

3. As part of the Matrix class, write a private method called swap that will accept four arguments: x1, y1, x2, and y2, each representing the indices of the two elements in the matrix that should be swapped.

4. Write a public method called printMatrix that accepts no arguments and returns nothing. It should print the matrix, highlighting in yellow the diagonal from top right to bottom left.

5. Write a public method called populateMatrix that accepts no arguments and returns nothing. It should simply populate the matrix with values from 1â€“(size Ã— size).

6. Write a public method called flipMatrix that accepts no arguments and returns nothing. It should â€œflipâ€ the matrixâ€™s values along the diagonal from top right to bottom left. The elements that comprise the diagonal should be highlight and not swapped.

â– Grading â–

| Item | Points | |—————————————————————————–|:——-:| | Program works according to instructions | 20 | | Code avoids being clever in favor of readability | 20 | | Code is neat and professional | 20 | | Variable naming is logical | 20 | | Comments are used thoughtfully in places where code is not self documenting | 20 |

â– Submission â–

You will need to issue a pull request back into the original repo, the one from which your fork was created for this project. See the Issuing Pull Requests section of this site for help on how to submit your assignment.
