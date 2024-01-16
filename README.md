# In Class Exercise 1 - Deep Neural Networks

(1) Install Tensorflow (this is what we will use to build a DNN) using the following command: 
`pip install tensorflow`

(2) Install Black for Jupyter (this will allow the formatting / debug checker to run on *.ipynb files):
`pip install black[jupyter]`

(3) Fork this repository.

(4) Open DNN_ICE1.ipynb. Follow the instructions within the notebook to edit the code. **Note: if you are using VS Code, you will likely be prompted to install a Jupyter extension. Do this.

(5) Run Black to check your code for minor errors and improper formatting using the following command (I did this in the terminal within VS code):
`black --check .`
If the output does not say "All done! ✨ 🍰 ✨ 1 file would be left unchanged.", you'll need to edit the code to resolve the issue. You can take a look at how Black would reformat your code using `black --diff .` Edit the code accordingly to resolve the issue and run again. Repeat until the output is "All done! ✨ 🍰 ✨ 1 file would be left unchanged.". You could also simply run `black .` to automatically make the changes, but I strongly recommend you understand what changes are made prior to submitting your file. For troubleshooting and more ways to use Black: https://black.readthedocs.io/en/stable/usage_and_configuration/the_basics.html

(6) Upload your GitHub repository into Gradescope under "ICE1 - DNN" assignment by TX, 1159. If the autograder fails, you did not successfully run Black. You can resubmit as many times as needed prior to the due date. You are also encouraged to schedule time for EI to debug as needed: [Book here](https://outlook.office.com/bookwithme/user/94f514961fa3476ab9598d4a2173d076@afacademy.af.edu?anonymous&ep=plink)


# In Class Exercise 2 - Deep Neural Networks in Nengo

(1) You will need to create a new environment with the following packages: python 3.10, nengo 3.2, tensorflow 2.10.1, nengo-dl 3.6.0, nengo-gui, black[jupyter], matplotlib, and scikit-learn. The process is to create a new environment, activate the environment, then download the packages as usual. If you are using conda, these commands should do the trick:
`conda create --name py3.10-nengo3.2 python=3.10` -- This command gives your new environment a name of *py3.10-nengo3.2*
`conda activate py3.10-nengo3.2` -- This command activates the environment so that you can install other programs within that environment. You'll see the name inside of your brackets change from *base* to the name of your new environment.
`pip install python==3.10`
`pip install nengo==3.2.0`
`pip install tensorflow==2.10.1`
`pip install nengo-dl==3.6.0`
`pip install nengo-gui`
`pip install black[jupyter]`
`pip install matplotlib`
`pip install scikit-learn`

(XX) Fork this repository.

(XX) From your activated terminal, launch VS code: `code .`

(XX) Open nengoDNN_ICE2.ipynb. Follow the instructions within the notebook to edit the code. 

(XX) Run Black to check your code for minor errors and improper formatting using the following command (I did this in the terminal within VS code):
`black --check .`
If the output does not say "All done! ✨ 🍰 ✨ 1 file would be left unchanged.", you'll need to edit the code to resolve the issue. You can take a look at how Black would reformat your code using `black --diff .` Edit the code accordingly to resolve the issue and run again. Repeat until the output is "All done! ✨ 🍰 ✨ 1 file would be left unchanged.". You could also simply run `black .` to automatically make the changes, but I strongly recommend you understand what changes are made prior to submitting your file. For troubleshooting and more ways to use Black: https://black.readthedocs.io/en/stable/usage_and_configuration/the_basics.html

(XX) Upload your GitHub repository into Gradescope under "ICE1 - DNN" assignment by TX, 1159. If the autograder fails, you did not successfully run Black. You can resubmit as many times as needed prior to the due date. You are also encouraged to schedule time for EI to debug as needed: [Book here](https://outlook.office.com/bookwithme/user/94f514961fa3476ab9598d4a2173d076@afacademy.af.edu?anonymous&ep=plink)
