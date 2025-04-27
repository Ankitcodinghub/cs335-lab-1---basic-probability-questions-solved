# cs335-lab-1---basic-probability-questions-solved
**TO GET THIS SOLUTION VISIT:** [CS335 Lab 1 – Basic Probability Questions Solved](https://www.ankitcodinghub.com/product/cs335-lab-1-basic-probability-questions-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121093&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS335 Lab 1 - Basic Probability Questions Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Note – Please read the instructions mentioned in the questions carefully. We have provided boilerplate code for each question. Please ensure that you make changes in the areas marked with TODO.

Question 1 – Random number generator

Complete the function generate_uniform to generate n numbers sampled from a uniform distribution on the interval [0,1] and save the generated numbers to a file named “uniform.txt”.

Each number must be on a new line.

You will need to use the function to generate random numbers from the np.random module. You will also need to set the seed in numpy before starting the random number generation. Function signature – def generate_uniform(seed: int, num_samples: int)

seed – The seed for random number generation that needs to be set num_samples – The number of samples you need to generate

Question 2 – Inverse transform sampling

Complete the function inv_transform which generates samples from a given probability distribution using uniform random samples from [0,1].

The function takes a file_path, target distribution name and some extra keyword arguments (which store the target distribution parameters) as input.

The file corresponding to the file_path will contain 100 numbers sampled from a uniform distribution on [0,1]. Each number will be separated by a newline character.

The second argument will be the target distribution name which will be one out of – “categorical”, “exponential” and “cauchy”.

The kwargs (parameters) will depend on the second argument

Function signature – def inv_transform(file_name: str, distribution: str, **kwargs)

For “categorical”, the kwargs will be of the form –

{

“values” : &lt;list-of-numbers&gt;,

“probs” : &lt;list-of-probability-values-associated-with-the-numbers&gt;

}

For “exponential”, the kwargs will be of the form –

{

“lambda” : &lt;float&gt;

}

For “cauchy”, the kwargs will be of the form –

{

“peak_x” : &lt;float&gt;,

“gamma” : &lt;float&gt;

}

Question 3 – Find the best distribution!

Complete the function find_best_distributions to find the distributions (from the options given below) which are most likely to have generated the given data.

The distributions are –

0. Gaussian distribution with μ = 0, σ = 1

1. Gaussian distribution with μ = 0, σ = 0.5

2. Gaussian distribution with μ = 1, σ = 1

0. Uniform distribution on [0, 1]

1. Uniform distribution on [0, 2]

2. Uniform distribution on [-1, 1]

0. Exponential distribution with λ = 0.5

1. Exponential distribution with λ = 1

2. Exponential distribution with λ = 2

The function takes a list of numbers as the only argument. It must return the three indices corresponding to the best distribution from each type which is the most likely to have generated the data.

Function signature – def find_best_distributions(samples: list)

Hint – Be wary of floating-point underflow

Question 4 – Confidence intervals

P(|û – μ| &gt;= ∈i ) &lt;= δi

Function signature – def marks_confidence_intervals(samples: list, variance: float, epslions: list)

The function returns a tuple containing the sample mean and the n probabilities δi.

Submission instructions

Complete the functions in assignment.py. Keep the file in a folder named

&lt;ROLL_NUMBER&gt;_L1 and compress it to a tar file named &lt;ROLL_NUMBER&gt;_L1.tar.gz using the command tar -zcvf &lt;ROLL_NUMBER&gt;_L1.tar.gz &lt;ROLL_NUMBER&gt;_L1

Submit the tar file on Moodle.

The directory structure should be –

&lt;ROLL_NUMBER&gt;_L1

| – – – – assignment.py

Replace ROLL_NUMBER with your own roll number. If your Roll number has alphabets, they should be in “small” letters.
