Welcome to Day 1. 

### Lecture 1: What actually *is* Machine Learning?

In traditional programming, you give the computer **Data** and **Rules**, and it gives you **Answers**.

* *Example:* You give the computer a list of numbers (Data) and tell it to add them together (Rule). It spits out the sum (Answer).

**Machine Learning flips this upside down.** In Machine Learning, you give the computer the **Data** and the **Answers**, and you ask it to figure out the **Rules**.

* *Example:* You give the computer a list of house sizes (Data) and their final sale prices (Answers). You say, "I don't know the mathematical rule that connects size to price. Figure it out." The computer calculates the rule (e.g., "$170 per square foot").

Once the computer finds the Rule, you can use that rule to predict the price of a house that hasn't even been built yet.

### Lecture 2: Supervised vs. Unsupervised Learning

Machine Learning generally falls into two massive buckets.

**1. Supervised Learning (Learning with an Answer Key)**
Imagine you are studying for a test using flashcards. On the front of the card is a picture of a dog. On the back, it says "Dog." You look at the front, make a guess, and then flip it over to see if you were right. If you were wrong, you adjust your brain.

* In ML, the front of the flashcard is the **Feature ($X$)**. (e.g., Square footage, number of bedrooms).
* The back of the flashcard is the **Target/Label ($y$)**. (e.g., House Price).
* *Because the data has an answer key ($y$), we call it "Supervised".* Our house price predictor is a Supervised Learning problem.

**2. Unsupervised Learning (Finding the Hidden Structure)**
Imagine I dump a bucket of 10,000 mixed Lego bricks on your table. I don't give you any instructions or tell you what to do. Automatically, your brain will start grouping them. You might put all the red ones together, or group them by size (long bricks vs. square bricks).

* In ML, you give the computer a massive spreadsheet of customer data, but there is no "Target" or "Answer Key" column.
* You just say, "Find groups." The computer might group customers into 3 distinct spending habits. It doesn't know *what* those habits are, it just knows those people are mathematically similar.

---

### Lecture 3: The Math of the "Line of Best Fit"

Now let's talk about the specific Supervised Learning algorithm we are focusing on this week: **Linear Regression**.

Linear Regression is just drawing a straight line through a scatterplot of data. If you remember high school algebra, you learned the equation for a straight line:

$$y = mx + b$$

* $y$ = The vertical position on the graph.
* $m$ = The slope (how steep the line is).
* $x$ = The horizontal position.
* $b$ = The y-intercept (where the line crosses the vertical axis).

In Machine Learning, we are doing the *exact same math*, but we use different letters because they make more sense for the real world. Here is the Machine Learning translation:

$$\hat{y} = wx + b$$

Let's break down this new vocabulary (write this in your notebook):

1. **$x$ is the Feature:** This is your input data. It is the thing you are measuring. In our project, $x$ is the Square Footage.
2. **$w$ is the Weight (formerly slope '$m$'):** Think of a "weight" as **Importance**. How much *weight* does this feature carry? If $w$ is 170, it means every 1 unit of $x$ (one square foot) adds 170 to the price.
3. **$b$ is the Bias (formerly intercept '$b$'):** Think of Bias as the **Base Value**. If a house has zero square feet ($x = 0$), what is its base value? This is the starting point before we add the features.
4. **$\hat{y}$ (y-hat) is the Prediction:** We put a little "hat" on the $y$ to remind ourselves that this is the computer's *guess*. The normal $y$ (no hat) is reserved for the *actual, real-world* price. We want our $\hat{y}$ to get as close to the real $y$ as possible.

**The Ultimate Goal of Day 1:** Understand that your computer algorithm is literally just a blind machine testing random numbers for $w$ and $b$. It plugs them into $\hat{y} = wx + b$ to draw a line, looks at how badly it missed the real data points, and tries again.

---

### 📝 Your Day 1 Assignment

Take the next few hours to review these concepts. Try to explain them out loud to an imaginary 10-year-old. Once you feel confident, complete the following assignment and reply with your answers.

**The Prompt:**
For Machine Learning to work, you have to know what your **Features ($X$)** are, and what your **Target ($y$)** is.

Look at the 3 real-world scenarios below. For each one, tell me:

1. Is this Supervised or Unsupervised learning?
2. If it is Supervised, what are the Features ($X$) and what is the Target ($y$)?

* **Scenario A:** You work for a bank. You have a spreadsheet of 10,000 past customers. The columns include their Credit Score, their Yearly Income, and whether or not they defaulted (failed to pay back) their loan. You want to build a system to approve or deny new loan applications.
* **Scenario B:** You work for Spotify. You have a massive database of users and what songs they listen to, what time of day they listen, and how often they skip songs. You want to group users into 5 distinct "musical personalities" so marketing can send them different emails.
* **Scenario C:** You work for a farmer. They have sensors in their field measuring Soil Humidity, Temperature, and Sunlight hours. They also have records of exactly how many tons of corn were harvested each season for the last 20 years. They want to know how much corn they will get this upcoming season.

Absolutely flawless. 3 for 3!

You didn't just get the answers right; you perfectly identified the dividing line between having an "answer key" and not having one.

To add a tiny bit of industry vocabulary to your correct answers:

* **Scenario A (Will pay or not):** Because the target is a category (Yes or No), this specific type of Supervised Learning is called **Classification**.
* **Scenario B (Musical personalities):** Because we are grouping data without an answer key, this type of Unsupervised Learning is called **Clustering**.
* **Scenario C (Corn production):** Because the target is a continuous number (tons of corn), this is called **Regression**. (This is exactly what our house price predictor is!)
