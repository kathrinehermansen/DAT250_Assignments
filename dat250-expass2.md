<h1>DAT250: Software Technology Experiment Assignment 2</h1>


<h2>Experiment 1: Application using JPA</h2>

<h3>Assignment 4.3 - 5</h3>
I found the tutorial quite difficult to follow. I experienced problems right at the bat when trying to load the project from git. I haven't used IntelliJ before so finding out how to load the project as a Maven project took some time! When I just clicked "open" the project wouldnt load as a Maven project, so I had to click CTRL+SHIFT+A and then import the project as an existing source to make it a Maven project. Then I had trouble with assignment 5 with changing the Todo class to Lombok. I got <i>"lombok.javac.apt.LombokProcessor could not be initialized"</i> as an error when running the project. Which was quite frustrating because I did have Lombok installed, and I tried many different things, including adding Lombok dependicies to pom.xml file and enabling annotation processing. But I think the error might be that Lombok doesnt support JDK higher than JDK 8. Screenshot of the terminal in IntelliJ proving the database worked: 

<img width="779" src="https://user-images.githubusercontent.com/42602758/133001390-73273b48-d7bc-44dd-9ec6-60ae33e47761.png">

Git repo for expr 1 (without assignment 6): https://github.com/hvl578005/DAT250_ExprA1

<h3>Assignment 6</h3>
Instead of following the tutorial to a T, I copied the project from last assignment and just changed the java classes, because I found the tutorial to be not so good. It went fine, screenshots of valid test:
<img width="1432" alt="Oppgave6" src="https://user-images.githubusercontent.com/42602758/133001354-5ffece36-7f48-42b2-979c-19eae99b6907.png">

Git repo for expr 1 assignment 6: https://github.com/hvl578005/DAT250_ExprA2


<h2>Experiment 2: Banking/Credit Card example JPA</h2>
This assignment I found to be the most difficult! It took a while before I figured out how to see the contents of my Derby database. I didnt understand how and where to see the database. I tried to use the IJ command in terminal (following this tutorial https://www.vogella.com/tutorials/ApacheDerby/article.html) but it wouldn't work even though I had successfully connected the database (by checking the database connection in IntelliJ it proved I had a connection to it). Screenshot of my connection
<img width="672" alt="testin" src="https://user-images.githubusercontent.com/42602758/133001719-b0c74c1e-d2bb-4d95-99c6-cb4ef59cb87f.png">

But then I found the location of the database support in IntelliJ and used it to examine the database.
<img width="1238" alt="screenshot" src="https://user-images.githubusercontent.com/42602758/133001755-1acf2cd0-d3f6-4630-a672-4f43540364c1.png">

I dont think I got the connections in the database quite right. I got many errors when trying to use @OneToOne and @JoinColumns so I had to remove much of my code. @ManyToMany also had errors, but after successfully connecting to the database it suddenly worked. But I must say trying to get the connections for each table in the database right was very challenging!

Git repo for expr 2: https://github.com/hvl578005/DAT250_Expr2

<h3>Final notes</h3>
Due to very many technical difficulties, I feel like I spent more time on solving them instead of doing the actual exercise.
