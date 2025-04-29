# cs111-homework-7-solved
**TO GET THIS SOLUTION VISIT:** [CS111 Homework 7 Solved](https://www.ankitcodinghub.com/product/cs111-submit-your-paper-as-one-pdf-file-and-tell-gradescope-which-pages-each-problem-is-on-if-you-worked-with-a-partner-you-must-each-turn-in-your-own-homework-paper-and-report-the-name-and-pe-6/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115136&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS111 Homework 7 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1. (Compare NCM problem 1.38.) The moral of this problem is that, with floating-point arithmetic, sometimes two algorithms look equivalent but one is better than the other at getting an accurate answer. Suppose you have a number x that is an approximation to another number xexact ̸= 0. Define the relative error in x as |(xexact − x)/xexact|.

1.1. The classic quadratic formula says that the two roots of the quadratic equation

ax2 + bx + c = 0

are

.

Use this formula in numpy (show your input and output) to compute both roots for

a = 1, b = 10,000,000,000, c = 1.

Also compute the roots two other ways: first with numpy’s np.roots(), and then by hand. To at least one significant digit, what is the relative error of the approximation computed using the quadratic formula to x0? To x1? What are the relative errors of the approximations computed using np.roots()?

1.2. You should have found in (1.1) that the classic formula is good for computing one root but not the other. Explain in a sentence why in this case one root isn’t computed accurately. Hint: The answer involves IEEE floating-point arithmetic!

1.3. Use the classic formula to compute one root accurately, and then use the fact that

to compute the other. What are the relative errors now?

and .

2.2. What IEEE 64-bit floating-point number represents κ2(B)? Give your answer both as an ordinary base-10 number, and also as a 64-bit word (16 hexadecimal digits).

3. These questions are all about IEEE standard 64-bit floating-point arithmetic, which is behind both numpy’s float64 type and C’s double type. You can use cs111.print float64() to see the actual bits that represent any number. Recall that one hexadecimal digit stands for 4 bits.

1

3.1. Machine epsilon, or just ϵ for short, is defined as the smallest floating-point number x such that 1 + x &gt; 1 in floating-point arithmetic. The experiment we did in class showed that ϵ is approximately 10−16, which is why we say that IEEE floating-point can be accurate to about 16 decimal digits.

What is the exact value of ϵ? (Give your answer as an exact arithmetic expression involving powers of 2, not a decimal expansion.) What is the 16-digit hex representation of ϵ in the IEEE standard? (Use cs111.print float64().) Approximately how close is ϵ to 10−16 in relative terms? (Answer this by computing |ϵ − 10−16|/ϵ.)

3.2. What is the 16-digit hex representation of 1/ϵ? What is its approximate value in base 10? (Here you should give a decimal expansion.)

3.3. What is the largest non-infinite positive number that can be represented exactly in IEEE floatingpoint? Give your answer three ways: As an exact arithmetic expression involving powers of 2; as the 16-hex-digit IEEE representation; and as an approximate value in base 10. (Hint: Consider the largest possible value of the 11-bit exponent field in the IEEE standard, but remember that value is reserved to represent “infinity”.)

3.4. A common mistake some people make (but not you!) is to think that ϵ is the smallest positive floating-point number. It’s not, by a long shot. Consider for example x = ϵ10. What is the approximate value of x in base 10 (as a decimal expansion)? Is x an exact floating-point number? If so, give its IEEE 16-hex-digit representation; if not, give an IEEE 16-hex-digit representation of a floating-point number as close to x as you can.

3.5. How many different floating-point numbers x are there with 1 &lt; x &lt; 2? How many with 4096 &lt; x &lt; 8192? How many with 1/64 &lt; x &lt; 1/32?

(under Readings on the course GitHub site), especially the section “TPU Chips” that starts on page 9.

The 1985 IEEE floating-point standard specifies a 16-bit version and a 32-bit version as well as the ubiquitous 64-bit version. The 16-bit version was never used much before about 2010, because most scientific modeling requires higher precision. Recently, though, 16-bit floating-point has become popular in machine learning applications, because the weights in a neural network don’t need to be determined very precisely.

IEEE standard 16-bit floating-point uses 1 bit for the sign, 5 bits for the exponent, and 10 bits for the mantissa. However, when Google developed its TPU (“Tensor Processing Unit”) chip for machine learning, it used a different 16-bit format that it calls “bfloat”, with 1 bit for the sign, 8 bits for the exponent, and 7 bits for the mantissa.

4.1. How many different floating-point numbers x are there with 1 &lt; x &lt; 2 in IEEE 16-bit floatingpoint? In bfloat?

4.2. What is machine epsilon for IEEE 16-bit floating-point? For bfloat? (Show your answer both as an exact mathematical expression and as an ordinary base-10 decimal approximation. You don’t need to show the 16-bit hex representation unless you want to.)

4.2. Assume that both IEEE 16-bit and bfloat treat exponents the same way IEEE 64-bit does, with the largest exponent reserved for infinity and all the exponents shifted to represent about the same number of negative exponents as positive exponents. (I don’t actually know whether this is true for bfloat.) What is the largest non-infinite positive number that can be represented exactly in IEEE 16-bit floating-point? In bfloat? Give your answers both as exact arithmetic expressions and as approximate base-10 numbers.

4.3. Name one advantage of bfloat over IEEE-16, and one advantage of IEEE-16 over bfloat.

2
