unWind! is a powerful and novel way to automate any of your workflows by
using the unWind! Bot without having to write any scripts/code. These
automation workflows could be used by Development/Test Engineers or in
Operations. For example:

* Test a feature: Black box, White box (API) testing, Negative Testing.
  Configuring the feature, performing any actions and verification
* Troubleshooting (Triaging) a deployed feature, Automatically
  root causing failures as part of testing
* Dev-Ops workflows. Anything from provisioning, monitoring and SLAs guarantees.

A common use case of UnWind! is in Networking: routing, switching, security
It is Multi vendor - OS and Platform agnostic and helps you to test,
trouble shoot, and gain visibility into the network at scale. It uses advanced
AI Deterministic Reasoning techniques combined with Statistical Inteference
techniques.

Installation:

unWind! is predominantly deployed on Ubuntu. For installing on other OSes,
please refer unWind! Administrator's guide.

Prerequisites:
- pip, virtualenv, unpack, libarchive, libpq-dev, python-dev

To install the pre-requisites, run the following commands:

curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py

python get-pip.py

pip install virtualenv

sudo apt-get update

sudo apt-get install unzip

sudo apt-get install libarchive-dev

sudo apt-get install libpq-dev python-dev

To Install UnWind! from tgz file, use the command below. This installs UnWind!
in 'unwind_pkg' directory in the current working directory.  If you want to
untar in a different directory then use option as -C (specified directory).

tar -xvzf unwind.tgz

Start UnWind!:

cd unwind_pkg/unwind
./install_and_run.sh -p 11001

fire your browser at:
http://<your-server>:11001/static/unwind.html

Click the button 'Click here to get started' to learn unWind!.

For any questions, please email srikanth.seshadri@gmail.com

Note:
If you want to customize unWind! to pull in your own git repositories for
Models, etc. edit 'unwind_startup_conf' file and make the changes there before
running 'install_and_run.sh' script.
