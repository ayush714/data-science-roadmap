
# Detailed Project Guides

_Asides from dedication to discovery and exploration, to succeed in a Data Science project, you must understand the process and optimize it to ensure that the results are reliable and the project is easy to follow, maintain and modify where necessary._ 

_And the best and fastest way to go about this is to structure your project using a template._

## Steps in a Data Science Workflow
_There are no fixed frameworks or defined templates for approaching Data Science projects. Each new dataset and each new problem will lead to a different roadmap. But, there are similar high-level steps applied when approaching many Data Science different problems, irrespective of the dataset._

_So let’s look at a clean workflow that can be used as a basis for data science projects._

_However, you should note that the steps outlined below are in no way linear. Instead, most Data Science projects are largely iterative, requiring multiple steps to be repeated and revisited._

- Acquisition
- Inspection
- Preparation
- Modeling
- Evaluation
- Deployment

### Step 1: Acquisition
_The process of training machine learning algorithms is a little like teaching a toddler an object’s name for the first time, then allowing them to identify it alone when next they see it. But human beings only need a few examples to recognize a new object. That is not so for a machine, as it needs hundreds or thousands of similar examples to become familiar with an object. And these examples or training objects need to come in the form of data._

### Step 2: Inspection
_After you have acquired the data to be used, the next step is to get a first impression of the data quality by inspecting it. The primary goal at this stage is to sanity-check the data, and the best way to accomplish this is to look for things that are either impossible or highly unlikely. Check for outliers and missing values, check the data types to see if they are correct, and check the most extreme cases. Do they make sense? A good practice is to run some simple statistical tests on the data and visualize it to get a quick overview of the statistical properties of the data and to detect possible outliers._

### Step 3: Preparation
_When you are confident you have your data in order, next you will need to prepare it by placing it in a format that is amenable to modelling. This stage encompasses several processes, such as filtering, aggregating, imputing, and transforming. The type of actions you need to take will be highly dependent on the type of data you’re working with, as well as the libraries and algorithms you will be utilizing._

### Step 4: Modeling
_Once the data preparation is complete, the next phase is modeling. Selecting an appropriate algorithm will depend on the type of data. For example, if the data is continuous you will apply regression modeling, if the data is categorical you will apply classification or logistics regression modeling. As a data scientist, you will try lots of models to get the best-fitted model._

### Step 5: Evaluation
_After building the model you need to measure its performance. The good news is there are several ways to do that, and again this step is largely dependent on the type of data you are working with and the type of model used, but on the whole, this step seeks to answer the question of how close the model’s predictions are to the actual value._

### Step 6: Deployment
_Working with data is one thing, but deploying a machine learning model to production is another. Once you are comfortable with the performance of your model, you’ll want to deploy it so it can reach the intended audience. This can take several forms depending on the use case, but a common scenario is utilization as a feature within another larger application._
