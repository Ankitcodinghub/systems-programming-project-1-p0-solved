# systems-programming-project-1-p0-solved
**TO GET THIS SOLUTION VISIT:** [Systems Programming Project 1 P0 Solved](https://www.ankitcodinghub.com/product/systems-programming-project-1-p0-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;124411&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Systems Programming Project 1 P0 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
1 Hashassin

For Projects 1 and 2 we will be working on a library (and front end) called Hashassin. Hashassin is a tool for generating and using hashes. For Project 2, you will be adding functionality to handle rainbow tables, but for Project 1 we are going to be working on the basic building blocks.

You can accept the GitHub classroom assignment atAssignment Project Exam Helphttps://classroom.github.com/a/B4CBWnvw.

This project is relatively straight forward as we are mostly interested in making sure that you are able to write a relatively complicated program that uses threading and deals with IO. To that end, you will be creating a workspace with two crates, one binary and one a library.

Your binary crate should be in a directory called cli and it should compile to a binary named hashassin.

Your library crate should be in a directory called core and it should be available called hashassin-core and usable by other crates via use hashassin core::Whatever.

Your CLI will support two commands: 1) gen-passwords and 2) gen-hashes.

gen-passwords will generate random passwords and save them to a file. gen-passwords must have several options that can be set:

1. –min-chars, which specifies the minimum number of characters to be used in generated passwords. This value must be greater than zero and the maximum value should be the maximum length of an array on whatever system the program is being run on. –min-chars should have a default value of 4.

2. –max-chars, which specifies the maximum number of characters to be used in generated passwords. This value must be greater than zero and the maximum value should be the maximum length of an array on whatever system the program is being run on. It must also be greater than or equal to whatever the –min-chars value is. –max-chars should have a default value of 4.

3. –out-path, which, if present, will write the output of the command to the specified file, one passwords per line (using Unix new lines and no empty lines between them). If not present, results should be written to stdout.

4. –threads, the number of threads to use to generate passwords. This value must be greater than zero and the maximum value should be the maximum length of an array on whatever system the program is being run on. –threads must have a default value of 1.

5. –num-to-gen, which is the number of passwords to generate. It must be greater than zero and the maximum value should be the maximum size of an array on the system it’s being run.

All passwords generated should be valid ASCII, both caps and lower case, and including punctuation and spaces but not including non-printable characters like n or

a. Assignment Project Exam Help

1. –in-path, which specifies the path to read plaintext passwords from.

2. –out-path, which, if present, will write the output of the command to the specified file, one hashed password per line (using Unix new lines and no empty lines between them). If not present, results should be written to stdout

3. –threads, the number of threads to use to generate hashes. This value must be greater than zero and the maximum value should be the maximum length of an array on whatever system the program is being run on. –threads must have a default value of 1.

4. –algorithm, which should be the algorithm used to generate hashes.

You are free to add other options and functionality, but whatever you add should not be required to be set by a user. I.e., it should either be optional or have sensible defaults.

3 Grading

• -1,000 points: If you do not update CREDITS.md with the names of your group members, as well as an honest break down of the work each group member did, you will receive NEGATIVE ONE THOUSAND points. I.e., it would be next to impossible to get anything higher than a zero on this project.

• -1,000 points: If running cargo fmt results in any change to your repository, you will get NEGATIVE ONE THOUSAND points. Be sure to run cargo fmt!!!!!!!!!

• 25 points: Program compiles, as well as the items noted below as required for graduate groups.

• 20 points: All required functionality of gen-passwords is implemented (e.g., setting –threads actually uses multiple threads, etc.)

• 20 points:Assignment Project Exam HelpAll required functionality of gen-hashes is implemented (e.g., setting –threads actually uses multiple threads, etc.).

• 10 points: No warnings from cargo clippy with no use of directives that would suppress default warnings (e.g., #[allow(dead code)])

• 5 points: Support one hashing algorithm.

• 0.25 points: Support an additional hashing algorithm (0.25 points per algorithm)

• 5 points: REQUIRED FOR GRADUATE GROUPS. Proper error handling. Create and use proper error types in library code and appropriate handling in any user code (e.g., CLI).

• 5 points: No unwraps or expects. Add #![deny(clippy::unwrap used, clippy::expect used)] to the top of your main.rs and lib.rs. If running cargo clippy doesn’t result in any errors, then you get the 5 points.

• 5 points: REQUIRED FOR GRADUATE GROUPS. Add proper logging. Using the tracing crate to generate logs. Points will be determined on comprehensiveness of logs, as well as the usage of different log levels.

• Unlimited points: Cool factor. Points are determined subjectively by me, but if I find anything about your project to be particularly unique, difficult, clever, etc., you can get some extra points. Be sure to point out anything we should pay special attention to in your README.md file.

In addition to the above, you must have a README.md to summarize what you did and give any and all instructions on how to run things! I’m going to go off what’s in the README.md to grade, so make sure you tell us everything you did and test all the instructions, etc.

3.1 Allowed Crates

Generally speaking, you are free to use any crates listed on https://blessed.rs.

Any crates not on Blessed.rs need to be approved by Jeremy.

Be sure to note what crates you use in your README.md!

REMEMBER THAT IF YOU USE A MACHINE LEARNING TOOL THAT IS CHEATING, YOU WILL RECEIVE A ZERO ON THE PROJECT (i.e., your max grade in the class will be a 66%, which is an F), AND THE CLASS WILL REVERT TO IN CLASS TESTS AND QUIZZES!!!!!
