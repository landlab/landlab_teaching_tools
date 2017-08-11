
[![Landlab header](./landlab_header.png)](http://landlab.github.io)

# Landlab teaching tools :raising_hand:

This repository includes Jupyter Notebooks that implement Landlab for use in teaching undergraduate and graduate courses. Jupyter Notebooks combine formatted text with code that can be run. Students can run small parts of code bit by bit as they follow along with the text.

The notebooks illustrate examples of physical processes implemented numerically. These notebooks are designed to teach about processes. The notebooks are not designed to teach students to code, or to teach students to use Landlab. No coding experience is needed to successfully carry out these activities - just the ability to read and a classroom introduction of the specific processes being discussed.

The notebooks are primarily designed for use as homework assignments or laboratory assignments. However, they can be used to illustrate concepts on-the-fly in the classroom.

The easiest way to see what is in the notebooks is through this website: https://nbviewer.jupyter.org/github/landlab/landlab_teaching_tools/tree/master/.

For an introduction to using Jupyter Notebooks, check out this site that has a tutorial using statistics, but a notebook is a notebook! (http://www.randalolson.com/2012/05/12/a-short-demo-on-how-to-use-ipython-notebook-as-a-research-notebook/)

The notebooks can be run locally by installing Landlab on your computer or they can be run remotely using Hydroshare.

# To install Landlab and run locally: :octocat::computer:

If following this method, every student will need to install Landlab on their personal computer, or it will need to be installed on classroom computers. All software needed to run Landlab locally is opensource (so free!). This link (https://landlab.github.io/#/) will take you to directions on how to install Landlab and information on preferred Python distributions. 

The next step would be for the class instructor to hit the _Clone or download_ button (on this webpage (https://github.com/landlab/landlab_teaching_tools), green, upper right) and download this repository locally. Choose which Jupyter Notebooks you would like the students to run, and then distribute the notebook to the students. You can edit them to your class' needs if you use this method. Note that some notebooks require supporting files to run, so make sure those are copied to the students.

# To use the notebooks on Hydroshare: :umbrella::computer:

These notebooks can all be run remotely using HydroShare, an online collaboration environment for sharing data, models, and code (there are no costs, fees or subscriptions). To have your students run the Notebooks without any software installation required, all of your students will need to join HydroShare.  For the first time set up, follow these steps: 

Initiation steps:
1. Go to https://www.hydroshare.org/
2. Hit blue button _Sign up now_ and follow steps. (remember your user name and password!)
3. Once signed up, on the top bar hit _Collaborate_.
4. Search for the Landlab Group and _Ask to join_
5. Once you have permission, enter the Landlab Group page.
6. Hit the _Resources_ tab.
7. Enter the collection _Landlab\_classroom\_notebooks_
8. Scroll down to _Collection Contents_ and hit on whatever notebook you want to run.
9. Hit the blue _Open with..._ button on the top right, and choose JupyterHub NCSA
10. Scroll down to the first code block, put your cursor in the code block, and hit _shift enter_. Provide your password.
11. Run the next two code blocks. **In this first notebook, you only want to run the first three code blocks!**
12. After the third code block is run, you will get a link to classroom notebook. Hit the link to the classroom notebook. (When this notebook opens, you will be asked to choose a kernal. Python 2 or 3 both work.)
13. Now you are running the notebook remotely!

Streamlined access:
After you and your students have successfully run through the steps above, in the next work sessions you can also access your personal user space on the supercomputer that makes this magic happen, simply by typing in this URL into your browser: https://jupyter.cuahsi.org  You will be prompted for your HydroShare login, and you can navigate the folders to find the resources you have downloaded and created in previous work sessions.

# More information: :question::open_mouth:

Please contact Nicole Gasparini [ngaspari@tulane(dot)edu] for help with using and improving these notebooks, developing new ones, and solutions to the current notebooks. These notebooks will be improved based on your feedback. I am happy to consult with you on learning the process of running a notebook. It's easy once you learn! 

The development of these Notebooks has been made possible by the Landlab project funded by the National Science Foundation.  Launching these Notebooks from HydroShare is made possible by a collaboration between HydroShare researchers, the Consortium of Universities Allied for Hydrologic Science, Inc. (CUAHSI), and National SuperComputer A  (NCSA) and funding by the National Science Foundation.  For more details on the software architecuture behind how to run Jupyter Notebooks from HydroShare, please contact [support@hydroshare(dot)org]. 
