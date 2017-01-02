# Sonar_Vision_ROS
## Mobile Robot Navigation Based on Sonar Vision Algorithm and Omnidirectional Vision
### Author: [Mohammad Hossein Bamorovat Abadi](https://bamorovatwo.wordpress.com/).

This code implemented with C++ programing Language under C programing Language Standard and Open CV Library.
This package implemented in ROS environment.
Implementation of the Sonar-Vision algorithm described in:

1. Bamorovat Abadi,M.H, Asghari Oskoei,M. “Effects of Mirrors in Mobile Robot Navigation Based on Omnidirectional Vision.” 8th International Conference, ICIRA 2015, Portsmouth, UK, August 24-27, 2015.[[pdf]](https://bamorovatwo.files.wordpress.com/2016/12/intelligentroboticsandapplications.pdf)[[bibtex]](https://bamorovatwo.wordpress.com/bibtex1)
2. Bamorovat Abadi,M.H., Asghari Oskoei,M. , Fakharian,A. “Mobile robot navigation using sonar vision algorithm applied to omnidirectional vision.” AI & Robotics (IRANOPEN), 2015,IEEE, {1-6}, 2015.[[pdf]](https://bamorovatwo.files.wordpress.com/2016/12/the-7th-robocup-iranopen-international-symposium-and-the-5th-joint-conference-of-ai-robotics.pdf)[[bibtex]](https://bamorovatwo.wordpress.com/bibtex2)

If you use Sonar_Vision_ROS in an academic work, please cite it via above bibtex links.

The program takes video and find and show a free path.

The parameters are (see the paper for details):

Ns: Number of Sonars.

KK1: The number of first Sonar that we want to use.

KK2: The number of last Sonar that we want to use.

ii: Start point in each Sonar.

Typical parameters are Ns=24, KK1=10, KK2=27, ii=60.
