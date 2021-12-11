### Set-up the Environment

We will use `Jupyter Notebook` with `Python3` for this coding assignment. 
You can find tutorials for [Python](https://docs.python.org/3/tutorial) and [Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable) here if you are not familiar with these.

We recommend you to run the codes in a virtual environment, using [conda](https://docs.conda.io/en/latest) or [virtualenv](https://virtualenv.pypa.io/en/latest). Here is an example with `virtualenv`. You can simply install it with `pip install virtualenv`. After that, do the following steps to set up a virtual environment with necessary packages.

1. Open a terminal under the same directory as this file.
    
2. Create a virtual environment named FoRL (or something you like).

    `virtualenv FoRL`

3. Activate the environment.

    `source FoRL/bin/activate`

    If you are using Windows, the command is

    `FoRL\Scripts\activate.bat`

4. Install Jupyter and other required packages.

    `pip install -r Requirements.txt`

5. Add the new kernel to Jupyter.

    `ipython kernel install --user --name=FoRL`

6. Open the Jupyter Notebook and Assignment3.ipynb.

    `jupyter notebook`

7. Switch the kernel to FoRL in the notebook menu: Kernel $\rightarrow$ change Kernel.
   
8. Deactivate the environment after you finish if you wish.

    `deactivate`

For the second time, you only need steps 6 (and 7) to open the notebook and test your implementation.

Alternatively, you may use `conda` to manage your environment. For this, use the command

`conda create -n FoRL python=3.8`

and activate it using

`conda activate FoRL`

and deactivate it using

`conda deactivate`.

The rest is similar to steps 4-7 above.


### Hand-in the Assignment
We have provided the skeleton code for the assignment in `Assignment3.ipynb`, including how to use [Openai Gym](https://gym.openai.com/). 
You only need to fill in the missing code marked in the notebook as well as several markdown cells for questions.

When you finish the assignment, please rename the notebook to `Assignment3-Lastname-Firstname.ipynb`. 
You only need to hand in this single notebook on Moodle with the following link:
<https://moodle-app2.let.ethz.ch/mod/assign/view.php?id=678123>.


### Grading
As long as your codes are meaningful and run successfully to produce some useful results, you will get at least half of the points. 
If you satisfy the requirements as specified in the notebook, you will get full grades.
Your code should be in a state that allows us to follow the main logic, you may use comments to facilitate this.

The deadline to submit your notebook on Moodle is Jan 21, 2022. Late submissions will be penalized. 
You must write the code yourself. 
Copying code from external sources is not allowed. Collaboration with other students on the course is not allowed.


### Contact
If you have any questions, feel free to send emails to
<yardima@ethz.ch> (for Part 1 of the assignment) or
<lianzhang@student.ethz.ch> (for Part 2 of the assignment).

However, we encourage you to post your questions in the [Assignments](https://moodle-app2.let.ethz.ch/mod/forum/view.php?f=32429) Forums on Moodle. In this way, other students facing the same issues can check the answers there and participate in the discussion.
