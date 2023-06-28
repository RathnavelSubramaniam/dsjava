# B.Sc Data Science-Java Programming

- [Java](#dsa-using-java)
  - [Announcements](#announcements)
  - [Practical List](#practicals)
  

## Announcements

<script>
  var countDownDate = new Date("Feb 20, 2023 09:30:00").getTime();
  var myfunc = setInterval(function() {
    var now = new Date().getTime();
    var timeleft = countDownDate - now;
        
    // Calculating the days, hours, minutes and seconds left
    var days = Math.floor(timeleft / (1000 * 60 * 60 * 24));
    var hours = Math.floor((timeleft % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    var minutes = Math.floor((timeleft % (1000 * 60 * 60)) / (1000 * 60));
    var seconds = Math.floor((timeleft % (1000 * 60)) / 1000);

    var lastDate = new Date("Feb 24, 2023 12:45:00");

    if(now<countDownDate){
      document.getElementById("time").innerHTML = 'The Training starts in ' + days + ' days ' + hours + ' hours ' + minutes + ' minutes ' + seconds + ' seconds <br /> <br />';
    } else if(now>=countDownDate && now<=lastDate){
      document.getElementById("time").innerHTML = 'The Training is LIVE! <br /> <br />';
    } else if(now>lastDate){
      document.getElementById("time").innerHTML = 'The Training is COMPLETED! <br /> <br />';
    }

  },1000);
</script>

<div>
  <ul>
    <li id='time'></li>
  </ul>
</div>

- Please make use of the [comment](#write-your-comments-below) section in the end of the page for any doubts/clarifications needed related to the practical.
- The training page will have algorithms for your practical sessions.


## Practicals

**Please select the link to do the Program**



| Topic                                                                                        | Release Date | Deadline             | Link                                                                                                                     |
| -------------------------------------------------------------------------------------------- | ------------ | -------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| 1.	Find the length of the hypotenuse of a right triangle given the lengths of its two opposing sides        |   |  | [Practical 1](https://classroom.github.com/a/XRyyXu1t) / [Algorithm/Pseudocode](./practical-algorithms/algorithm-1.md)   |
| 2.	Write a program to find Season using if-else-if and switch statements                                  |   |  | [Practical 2](https://classroom.github.com/a/QqstL6mr) / [Algorithm/Pseudocode](./practical-algorithms/algorithm-2.md)   |
| 3. Write a Java program to find the factorial of a number using recursion   |   |  | [Practical 3](https://classroom.github.com/a/7MJvCR8I) / [Algorithm/Pseudocode](./practical-algorithms/algorithm-3.md)   |
| 4.Write a Java program that invoke the Box class created with a method named “volume” from 2 Box objects                |  |   | [Practical 4](https://classroom.github.com/a/3ICxrNvq) / [Algorithm/Pseudocode](./practical-algorithms/algorithm-4.md)   |
| 5.Write a program that illustrates method overloading|   |  | [Practical 5](https://classroom.github.com/a/lNRRCkch) / [Algorithm/Pseudocode](./practical-algorithms/algorithm-5.md)   |
| 6.Write a program to demonstrate how the command-line arguments are accessed inside a Java program  |   |  | [Practical 6](https://classroom.github.com/a/-YpUCPUK) / [Algorithm/Pseudocode](./practical-algorithms/algorithm-6.md)   |
| 7. Write a program that uses inheritance to extend Box class by including a variable “weight”                                   |   |  | [Practical 7](https://classroom.github.com/a/Y02sILAW) / [Algorithm/Pseudocode](./practical-algorithms/algorithm-7.md)   |
| 8. Create a program with a superclass called Figure that defines a method called area( ) which computes the area of an object. Then derives two subclasses from Figure. The first is Rectangle and the second is Triangle. Each of these subclasses overrides area( ) so that it returns the area of a rectangle and a triangle, respectively                                |   |  | [Practical 8](https://classroom.github.com/a/PKsk6R1Z) / [Algorithm/Pseudocode](./practical-algorithms/algorithm-8.md)   |
| 9. Define a package named “MyPack” with the public class “Balance”. Import that package to make use of the Balance class                                            |   |  | [Practical 9](https://classroom.github.com/a/rQHnRTSS) / [Algorithm/Pseudocode](./practical-algorithms/algorithm-9.md)   |
| 10. Demonstrate the implementation of an interface concept with a simple program                                             |   |  | [Practical 10](https://classroom.github.com/a/ZHQNMk3T) / [Algorithm/Pseudocode](./practical-algorithms/algorithm-10.md) |
| 11.	Develop a single Java program which caught ArithmeticException and ArrayIndexOutOfBoundsException                                             |   |  | [Practical 10](https://classroom.github.com/a/ZHQNMk3T) / [Algorithm/Pseudocode](./practical-algorithms/algorithm-10.md) |






<!-- ## Pattern of the Test

| Section           | Questions    | Time    |
| ----------------- | ------------ | ------- |
| Programming Logic | 10 Questions | 15 Mins |
| Hands-On Coding   | 1 Question   | 15 Mins |
| Hands-On Coding   | 1 Questions  | 30 Mins | -->

## Write your comments below

<script 
        async
        src="https://utteranc.es/client.js"
        repo="RathnavelSubramaniam
              /DS-Java-2023-Batch"
        issue-term="title"
        theme="github-light"
        crossorigin="anonymous"
></script>
