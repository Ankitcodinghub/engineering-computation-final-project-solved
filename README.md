# engineering-computation-final-project-solved
**TO GET THIS SOLUTION VISIT:** [Engineering-Computation Final Project Solved](https://www.ankitcodinghub.com/product/engineering-computation-final-project-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94683&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Engineering-Computation Final Project Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
&nbsp;

Write a C++ program that randomly samples from the Watt Fission Spectrum.

</div>
</div>
<div class="layoutArea">
<div class="column">
Say you have a Monte Carlo neutronics code. Part of this code will involve randomly sampling what energy a new neutron created from fission will have. This can be done using the Watt distribution. For this problem, we will assume the probability distribution of the energy is

P (E) = 0.4865 sinh(√2E) e−E

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
<ol>
<li>Setup.
<ol>
<li>First create a lambda function ​fx​ within main() which is passed ​E​ and returns the
value of P(E) from the equation above.
</li>
<li>Check that you have ​fx​ correct by integrating using ​trapezoidal​ from [0,8] and
showing your result is 1.00 (accurate to about the hundredth place). Print the

integral to the screen.
</li>
</ol>
</li>
<li>Find the ​maximum​ of ​fx ​( P(E) )​.</li>
</ol>
a. You can do this either by finding the roots of the derivative of ​fx ​(ie using finite_difference_derivative ​and ​bisect​) and evaluating fx at the root, or by using minima​. Print the (E, P(E)) to the screen.

3. Random point.

a. Randomly create a point in the range x=[0,8] and y=[0,max from part 2]. You will

need to randomly select two values. Create this as a pair called ​point​. 4. Use rejection method.

a. Check to see if the ​point​ selected in part 3 is under the P(E) curve. If it is, save the energy to a vector of doubles called ​sample​. If it is not, reject the point and randomly create a new one and check again. Repeat until a valid point is found and the selected energy is stored.

5. Create a sample.

a. Randomly sample 100,000 energies from the Watt Fission Spectrum. They should

be stored in ​sample​. Print the size of ​sample​ to the screen. 6. Binning.

a. Create a vector of 100 energy bins, from 0 to 8 MeV, called ​bins​. Find the number of energies in ​sample​ that are in each bin. Print to the screen the number of selections found in each of the 100 bins.

7. Histogram plot.

a. Make sure your random sampler works by plotting a histogram of ​sample,​ by

plotting the value in each bin of ​bins​. You can use Excel, Python, C++, etc. If not in your C++ code, then attach the other file with the image of the plot.

Attach all relevant code and screenshots.

</div>
</div>
</div>
</div>
