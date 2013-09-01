# Checkmate

John Drake, now known as Number Six, is still being held in the bizarre prison known only as "The Village". 

Number Six has devised a way to tell who are the prisoners and who are the warders: by their behaviour. Once he knows for sure who is a prisoner, he'll be able to work with them to plot an escape.

1. Clone the repository from [GitHub](https://github.com/wbillingsley/tutorial-checkmate).

2. Read and run the tests in the `TestCheckmate` class. They should pass, showing that yet again Number Six's plan has failed.

3. Using the [Quick Sequence Diagram Editor](http://sdedit.sourceforge.net/), LucidChart, or pen an paper, sketch out the sequences diagrams of:

   * `TestCheckmate.testCheckmate`, showing why Six's plan fails
   
   * `Person.escapeWithMe`, including both branches
   
   * `Warden.mistreat`, including the loop


# Code coverage

Tests in a project are never perfect.  So one of the things we might ask ourselves is "how much of the code in the project is exercised by the tests"?  This is the concept of "code coverage", and we're going to look at three different ways to measure it.

The Village is always thinking about its villagers. Particularly, it's always thinking about how they might try to escape. So, this week the `Village` class also has a method `Village.couldConspire(asked, asking)` that considers how one prisoner might respond if another prisoner asked them to try to escape together.

1. Read the code of the `Village.couldConspire(asked, asking)` method. Also have a look at the tests in the `TestCoverage` class.  We're going to consider three kinds of "code coverage" for the tests.

    * Which *statements* are not exercised by the tests?  
    
       Write additional test cases (like `TestVillage.testCase1` and   
       `TestVillage.testCase2`) to cover those statements.

    * Which *branches* are not covered by the tests? 
    
      Write additional test cases to cover those statements.

    * Which *execution paths* (combinations of branches) are not covered by the tests? 
    
      Write additional test cases to cover those statements.
 
