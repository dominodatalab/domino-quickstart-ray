### Welcome to your very own Ray on Domino quick-start project!

Ray is a extensive distributed computing library of tools for parallel and distributed applications.  Ray provides:

1. Simple primitives for building and running distributed applications.
2. Enables users to parallelize single machine code, with little to zero code changes.
3. Includes applications, libraries and tools for deep learning.

Ray has programming interfaces for Python, Java and C++ (Experimental).

This quick-start project has examples for running remote functions using Ray and some of its libraries.  This includes performing basic reinforcement learning using RLLib, use of Tune for distributed data parallelism, and a fun example of trying to predict a stock market values of US and Bitcoin currency.

_Before you get started, you might want to check out [our product tour video](https://www.dominodatalab.com/p/weekly-live-demo-ungated/)._

### Starting a Ray Workspace

To start a Ray workspace you will need to design two environments.  The first is an environment that will be used for the workspace.  This environment should have Ray installed, preferably the latest version.  One can build the workspace environment using the latest Domino Analytics Distribution as its base.  The second environment -- the workers environment should also have the identical version of Ray installed.  An example of how to build the docker image for your environments is available upon request.

Then when starting a workspace you will go through the following steps

1. Choose create new workspace
2. Choose the workspace environment for Ray, for example Domino-Analytics-Distribution-Ray-1.9 as well as the appropriate hardware tiers.
3. Review the datasets associated with the project.  In general this is just a matter of checking through the list.
4. Choose the worker's environment, hardware tier and memory allocated.  

See for more information on starting and using workspaces see: [Domino Documentation on Workspaces](https://docs.dominodatalab.com/en/latest/get_started/3-start_workspace.html?highlight=workspace)

### Run Remote Functions

Ray makes it easy to parallelize your work with the ``ray.remote`` decorator above each function. The first part of our interactive workbook entitled **Basic Ray Tutorial and Deep Q Learning.ipynb** demonstrates the techniques and benefits of using remote functions. The notebook will walk you through making and calling remote functions.

### Perform Reinforcement Learning

Ray has a helpful library called RLLib.  This library aids in productionalizing reinforcement learning on multiple GPU or CPU machines.  In the notebook **Basic Ray Tutorial and Deep Learning.ipynb** we walk through an example of deep reinforcement q-learning.  The first example addresses the cart-pole problem, using parallellism.  The second example will demonstrate optimizing a robot's ability to walk down a corridor.

### Use Ray and Tune for a Simple Computer Vision Task
We examine the task of using a distributed and parallel system to address a simple computer vision problem.  We using distributed data parallel format to parallelize training of deep learning pipeline designed to help predict digits based on the dataset MNIST.  The notebook is titled **Simple Computer Vision MNIST using Distributed Data Parallel.ipynb**.


### An example of using Ray for Stock Market Predictions

The final notebook, **Model Creation and Training-DQN** involves creating a reinforcement learning algorithm to predict investment outcomes.  Putting it all together we can see Ray in action.

### Knowledge Management and Sharing

Right now, you're reading the `README.md` file which is a great place to explain what your project is all about.  We suggest every project have a README file -- it helps others onboard onto your project quickly and helps you remember what the point of your project was in the first place :)

README files get shown on a project's overview page and, like all files, get automatically versioned for your convenience and time traveling needs. You can even embed images from the web or your project, for example `benefits.png`: ![Benefits](benefits (1).png)

Want to share this project with others? Domino makes it easy for multiple people to collaborate on a project, or to share your projects publicly. [You can add collaborators to this project or adjust its visibility here.](settings#sharing)
_____

**Need some extra help?**

* Simply email [support@dominodatalab.com](mailto:support@dominodatalab.com) or click the blue circular help icon to ask for help without leaving Domino.
* We've also got a ton of great content on [docs.dominodatalab.com](https://docs.dominodatalab.com)
