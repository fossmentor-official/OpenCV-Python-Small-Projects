# OPENCV PYTHON SMALL PROJECTS

OpenCV (Open Source Computer Vision Library) is a powerful, open-source library primarily used for computer vision and image processing tasks. Developed by Intel, it is written in C++ but has bindings for multiple languages including Python, Java, and MATLAB, making it accessible to a wide range of developers. OpenCV supports numerous algorithms and functions for real-time image and video processing, object detection, face recognition, edge detection, and more.

<h1>Getting Started</h1>
<p>These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.</p>

<h2>Prerequisites</h2>
<code>python== 3</code>

<h2>Installing</h2>
<pre>open terminal and type</pre>

<code>git clone https://github.com/FOSSMentorOfficial/OpenCV-Python-Small-Projects.git</code><br><br>

<h4>or simply download using the url below</h4>
<code>https://github.com/FOSSMentorOfficial/OpenCV-Python-Small-Projects.git</code><br>

<pre> Create and Activate a Virtual Environment</pre>
<code>python3 -m venv venv
source venv/bin/activate # On Windows, use `venv\Scripts\activate`</code>

<pre>Install OpenCV:</pre>
<code>pip install opencv-python</code>

<pre>If you need the headless version (without GUI features), you can install opencv-python-headless: </pre>
<code>pip install opencv-python-headless</code>

<pre>Verify the Installation: After installing OpenCV, you can verify the installation by importing cv2 in a Python shell.</pre>
<code>
python<br/>
>>> import cv2 <br/>
>>> print(cv2.__version__)
</code>

<pre>If installing opencv-python is taking too long in PyCharm, it might be due to the process of building the package from source, which can be resource-intensive. Here are a few steps to troubleshoot and potentially resolve the issue: </pre>
<pre> 1) Install a Precompiled Wheel:

Sometimes, precompiled wheels can be installed faster than building from source. You can specify to install the precompiled version using pip. Ensure that you have pip and setuptools updated to the latest version:</pre>
<code>pip install --upgrade pip setuptools</code>

<pre>Then try installing OpenCV again:</pre>
<code>pip install opencv-python</code>

<pre>2) Increase Resource Allocation:<br/>
Ensure that your system has enough resources allocated for the build process. If you are running other heavy applications, close them to free up resources.</pre>

<pre>3) Use opencv-python-headless:<br/>
If you don't need the GUI features of OpenCV (like imshow), you can install opencv-python-headless which might be faster to install.
</pre>
<code>pip install opencv-python-headless</code>

<pre>4) Check for Network Issues:<br/>
Ensure you have a stable and fast internet connection as downloading large packages can take time on slow or unstable connections.
</pre>

<pre>5) Install from a Different Source:<br/>
Sometimes, the package might be downloaded faster from a different repository or mirror. You can specify an alternative PyPI mirror:
</pre>
<code>pip install opencv-python -i https://pypi.douban.com/simple</code>

<pre>Manual Download and Installation:<br/>
Download the precompiled wheel manually from PyPI or from Unofficial Windows Binaries for Python Extension Packages. Then install it using pip.
</pre>
<code>pip install path/to/downloaded/opencv_python.whl</code>