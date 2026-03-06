Install Required Tools

You need these three things:
Python (for Jupyter)
Jupyter Notebook
OpenJDK

Check installation in terminal:
python --version
java -version
javac -version

Install Jupyter Notebook
pip install notebook
jupyter notebook

Install Java Kernel:
curl -L https://github.com/SpencerPark/IJava/releases/download/v1.3.0/ijava-1.3.0.zip -o ijava.zip
Extract it:
unzip ijava.zip
Install kernel:
python install.py

Now restart Jupyter.
New → Java
<img width="1366" height="682" alt="{14EFBA12-2454-49B2-B56D-8322F92DA1F0}" src="https://github.com/user-attachments/assets/cdda7e55-883c-4613-a8fb-6f4a35c97649" />
